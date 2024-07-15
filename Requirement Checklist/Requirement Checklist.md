# Task List for Requirement Checklist - v1.0

- [ ] <strong>GENERIC QUESTIONS : FORMALITIES</strong>

  - [ ] Are all documents needed for the review available?

  - [ ] Is the document written in its proper template? (if not: Is the reason known?)<br />
Is the hierarchical structure of the document understandable?<br />
Is the structure of requirements sufficient to deal with possible changes of requirements and are there mechanisms defined to deal with requirements updates?

  - [ ] Are there configuration management rules defined for this Dokument? (if and which baselines have to be performed, is the document under version control?)<br />
<br />
Does the document have its proper ID (e.g. baseline label with date, title, version history, author(s)?

- [ ] <strong>GENERIC QUESTIONS : COMPLETENESS</strong></p>

<p>&nbsp;

  - [ ] Are all chapters provided with intended contents?

  - [ ] Are there any un-resolved issues and risks (e.g. tbd) and are these identifiable?

  - [ ] Is there a traceability strategy defined for the project, in appropriate granularity?<br />
Is each requirement (e.g. in SRS, HRS) linked (reference, link, naming convention etc.) according to traceability strategy to its requirements source (e.g. SysRS) and vice versa?<br />
Is each requirement linked to the next lower hierarchical level (e.g. architecture, design, specification of verification)

- [ ] <strong>GENERIC QUESTIONS : CLARITY</strong>

  - [ ] Are all abbreviations and technical terms defined and clear?

  - [ ] Are the requirements well-defined and understandable for the readers?<br />
Are the statements sufficiently concise stated (i.e. no unnecessary complicated and long sentences)?

- [ ] <strong>GENERIC QUESTIONS : CORRECTNESS &amp; CONSISTENCY</strong>

  - [ ] Is the document free of obviously wrong or superseded statements?

  - [ ] Is the document free of any ambiguous, unneeded or inconsistent statements?

  - [ ] Are safety requirements internally consistent?<br />
NOTE Unlike external consistency, in which multiple safety requirements do not contradict each other, internal consistency means that each individual safety requirement contains no contradictions within itself.

- [ ] <strong>GENERIC QUESTIONS : CHECKLIST FOR EACH STATED REQUIREMENT</strong></p>

<p><strong>Verifiable: </strong>Can an acceptance criteria or test(s) be given that can verifiy the correct implementation of the functional requirement?&nbsp; (Note: This criteria applies only for functional requirements)

- [ ] <strong>GENERIC QUESTIONS : CHECKLIST FOR THE SET OF ALL STATED REQUIREMENTS</strong>

  - [ ] <strong>Complete</strong>: Are all required functions, interfaces (incl. test requirements), scenarios (during the project lifecycle incl. possible defects and exception situations), qualities and design constraints considered?<br />
Examples:<br />
- timing constraints<br />
- each operating mode of the vehicle, the system, or the hardware, and their impacts<br />
- shared and exclusive use of hardware resources (including memory mapping, allocation of registers, timers, interrupts, I/O ports

  - [ ] <strong>Consistency1</strong>: &nbsp;Is each requirements technically not contradicting any other requirement?&nbsp;<br />
e.g.<br />
- consistence of requirements inside a specific function/feature<br />
- consistence of all provided outputs with expected input between different internal and external (if applicable) functionalities/compoenents?<br />
<u>Note:</u> Especially universal requirement (&quot;X is always valid&quot;) are a potential source for inconsistencies with exceptional sitations, and should be examined in detail.

  - [ ] <strong>Analyze</strong>: &nbsp;Are all requirements analysed in terms of the following criterias?<br />
- technical feasibility<br />
- risks<br />
- testability<br />
- cost<br />
- schedule

- [ ] <strong>GENERIC QUESTIONS : MANAGEMENT OF REQUIREMENTS</strong>

  - [ ] <strong>Tracking</strong>: Do all tracked requirements have a definite state?

  - [ ] <strong>Requirements Allocation:</strong><br />
Are requirements explicitly allocated to at least one domain?<br />
Are component-related requirements allocated to these components?

  - [ ] <strong>Baseline Planning</strong>: Are requirements allocated to delivery baselines (e.g. via function/feature release planning)?

- [ ] <strong>COMPLETENESS (DETAILED ASPECTS)</strong>

  - [ ] Are software based checks and diagnostic functions for the plant required? If yes, are the needed requirements specified?

  - [ ] Are requirements for the SW interface included (diagnoses, KWP2000, etc.)? (e.g. informations about the contents, protocol subsets to be implemented, communication sequences, communication baud rate).

  - [ ] Are requirements on filtering of measurements needed? (e.g. for noise reduction)<br />
Is it specified which noices have to be corrected and which quality of signal can be accepted?

  - [ ] For thresholds are hysteresis defined?

  - [ ] Have non-functional requirements (e.g. standards, customer and RB procedures, quality requirements) considered?

  - [ ] Are safety requirements unambiguosly identifiable as safety requirements?<br />
Are ASIL levels, FIT rates etc. specified? Are the attributes correctly inherited from superordinate requirements?

  - [ ] Are the requirements atomic?<br />
Note: This means they are formulated in a way that they can not be divided in more than one safety requirement.

  - [ ] Does the SRS consider the system and hardware configuration (e.g. clock prescaler)?

  - [ ] Are all safety requirements of the technical safety concept adressed?

  - [ ] Are constraints from linked sources considered?

  - [ ] Does the HRS include sufficient information to enable functional safety to be assessed effectively? For ASIL C+D the target values for HW architectural metrics and for random HW failures which will violate a safety goal have to be defined.

  - [ ] Are requirements for layout (incl. Requirements from production) defined in the specification &quot;HW Requirements for Layout&quot;?

  - [ ] Are all requirements from plant to layout defined in the specification &quot;HW Requirements for Layout&quot;?

  - [ ] Are there requirements for target architectural metrics for each safety goal e.g. &quot;single point faults metric&quot; (SPF) and &quot;latent faults metric&ldquo; (MPF) or violation due to random HW failures?

  - [ ] Have all safety goals and the resulting safety requirements for each domain been considered? Is the traceability given between them?

  - [ ] Are there customer safety requirements in addition to safety goals? If so, are they traceable to/from safety goals and system or directly to further domain requirements?

  - [ ] In what voltage range do you log DTCs (Diagnostic Trouble Code)?

  - [ ] What is the denounce time of DTC Logging Voltage Range?<br />
What is denounce time of analogue inputs?

  - [ ] When is Continuous DTC logging enabled and disabled?

  - [ ] List all the conditions that could cause a defective ECU DTC to be set? (NVRAM, ROM, Relais)

  - [ ] How long does it take to set a defective ECU DTC for each of the conditions listed above?

  - [ ] Has the input operation i.e., de-bounce strategy, analog data processing been specified?

  - [ ] Has the voltage mapping technique for battery voltage (voltage monitor) been specified?<br />
(Input filters between the measured battery voltage and the A/D channel being sampled must be matched )

  - [ ] Are the requirements from &quot;ISO/DIS 26262-8 Table 1 &mdash; Specifying safety requirements&quot; considered?

  - [ ] Are the requirements from &quot;ISO/DIS 26262-8 Table 2 &mdash; Methods for the verification of safety requirements&quot; considered?
