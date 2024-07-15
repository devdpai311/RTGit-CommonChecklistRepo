# Task List for Implemented Software Component Review Checklist - v2.0

- [ ] Process&nbsp;

  - [ ] Have the Coding Guidelines been respected?

  - [ ] Are all documents needed for the review available? (Source Code, Code documentation, Design Document, ...) and are these controlled per configuration management (identifiable e.g. versioned, labeled, etc. )?

  - [ ] Does the document has its proper ID, title, version history (version nr. and date), author(s), status?

- [ ] BU specific questions

  - [ ] Is the code consistent with software design and SwRS? Is tracability established?

  - [ ] Adding/renaming files/artifacts checked with architect?

  - [ ] All Compiler/Linker/Tool (Davinci, BCT) warnings solved?

  - [ ] All warnings from static code/model analysis are solved or justification accepted

  - [ ] Manual MISRA checks are performed

  - [ ] No debugging code? (No unjustified volatile parameters?)

  - [ ] Code is maintainable? Enough comments? Standard implementation templates used?

  - [ ] No unjustified static variables?

  - [ ] Un-needed function calls? No empty runnables, functions?

  - [ ] CPU load intensive code (e.g. loops) in fast cyclic tasks?

  - [ ] No extra includes (except CDDs) ?

  - [ ] No unjustified global variables / No extern variables in global headers?

  - [ ] Input validation checked?

  - [ ] Pointer out of boundary checked?

  - [ ] Return values checked?

  - [ ] Buffer overflow checked?

  - [ ] Is freedom from interference assured

  - [ ] Has the possibility that the function is interrupted been considered

  - [ ] ISO_26262-6:2018 - Table 6<br />
1a One entry and one exit point in sub-programs and functions<br />
1b No dynamic objects or variables, or else online test during their creation (&quot;++&quot; from ASILB)<br />
1c Initialization of variables<br />
1d No multiple use of variable names<br />
1e Avoid global variables or else justify their usage (&quot;++&quot; from ASILC)<br />
1f Restricted use of pointers (&quot;++&quot; from ASILB)<br />
1g No implicit type conversions (&quot;++&quot; from ASILB)<br />
1h No hidden data flow or control flow (&quot;++&quot; from ASILB)<br />
1i No unconditional jumps<br />
1j No recursions (&quot;++&quot; from ASILC)

- [ ] 3rd Party Software Configuration specific questions (e.g. Autosar BSW)

  - [ ] Is the configuration instructions / integration manual available and applied?

  - [ ] In case of implementing a ASIL classified requirement:<br />
Is the safety manual available and applied? Are the assupmtions made by supplier for the usage as SEooC met?

  - [ ] Are the configuration parameters and settings with regards to the requirements correct?

  - [ ] Are deviations to the standard Specifications (e.g. Autosar) in place? If yes, are these documented?

- [ ] <strong>Functional correctness</strong>

  - [ ] Are all requirements met?

  - [ ] Are global ressources/data used as defined in the architecture?

  - [ ] Does the code match design specification?

  - [ ] Are there any unresolved TBD&#39;s or TO DO&#39;s?

  - [ ] Is the fault detection correctly implemented? (keywords: test conditions, fault conditions)

- [ ] <strong>Understandability</strong>

- [ ] <strong>Correctness</strong></p>

<p>[Source code] Is the &quot;Source code&quot; free of obviously wrong or obsolete statements?

- [ ] <strong>Consistency</strong>

  - [ ] [Source code] Do other components only get involved through the IH-files?&nbsp;

  - [ ] Is the &quot;Source code&quot; or the &quot;Source model&quot; unit-testable, maintainable and not unnecessary complex?

  - [ ] For model based development (e.g. Matlab/Simulink):<br />
Is the model and the generated code consistent?<br />
The following problems have to be checked:<br />
&bull; model is changed and checked in, code is generated but not checked in<br />
&bull; model is changed and checked in, but code is not generated and not checked in<br />
&bull; model is changed and not checked in, but code of modified model is generated and checked in

- [ ] <strong>Conformity,<br />
Coding Guidelines not checked by QA-C</strong></p>

<p>In case of an explicit cast, check the value range of the variable to be casted. Check undesired under/overstepping of the extreme values, as well as undesired re-interpretations of the variable content.<br />
(Examples: cast from signed -&gt; unsigned: loss of sign; cast from long -&gt; short: overstepping of value range; etc. )
