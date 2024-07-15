# Task List for System Requirements Review Checklist - v1.0

- [ ] General

  - [ ] Is each requirement Correct, Clear, Consistent, Compliant, Complete? And Uniquely identifiable?<br />
Are all abbreviations, acronyms, definitions and technical terms defined in Glossory are clear and consistently used?

  - [ ] Are the requirements well-defined and understandable for the readers?<br />
Are the statements sufficiently/concisely stated <em>(i.e. no unnecessary complicated and long sentences)?</em><br />
Is the document free of any ambiguous or inconsistent&nbsp; or contradictory statements?<br />
Are the requirements free of redundancies? <em>(Same requirement(s) mentioned in more than one place should be recognized and removed)</em>

  - [ ] Are the contents of the requirements compliant with the requirements development process and requirements formulation guideline as described in the Systems Engineering process [project defined process as defined in PMP] and are there objective evidence that the requirements development process was actually used when developing the requirements?

- [ ] Clarity

  - [ ] Are the requirements defined at the Correct level? (<em>Segregrate requirements at System level, Software level, implementation conventions etc</em>)<br />
Are all requirements actually requirements, not implementation solutions? (<em>Separation of the &ldquo;what?&rdquo; and the &ldquo;how?</em>)

  - [ ] Are all the functional requirements:<br />
Measurable? <em>(E.g. Avoid requirements like: The output should be good or response should be fast. Correct Way: The response time&nbsp; should be within 10 milliseconds) </em><br />
Verifiable? <em>(Acceptance test or review criteria can be given?&nbsp; ) </em><br />
Feasible? <em>(Are all functional requirements possible to implement?)</em>

- [ ] Completeness

  - [ ] Are all required functions, interfaces (incl. test requirements), scenarios (during the project lifecycle incl. possible defects and exception situations), qualities and design constraints (incase of existing reference architecture) considered?<br />
<em>Examples:<br />
- timing constraints<br />
- each operating mode of the vehicle, the system, or the hardware, and their impacts<br />
- shared and exclusive use of hardware resources (including memory mapping, allocation of registers, timers, interrupts, I/O ports</em>

  - [ ] Are all Safety, security and legal requirements and special charecteristics properly identified and classified accordingly?<br />
Are the special characteristics in the project identified, documented and communicated to customer?<br />
<em>(Refer Safety, security and legal requirements review checklist for complete review of these SSL requirements)</em>

- [ ] Consistency:</p>

<p>Are all requirements:<br />
Relevant and necessary?<em> (Traceable to its provider/source? - trace to a user need) </em><br />
Tip: Is each requirement linked <em>(reference, link, naming convention etc.)</em> according to traceability strategy to its requirements source (e.g. SysRS) and vice versa?

- [ ] Correctness

  - [ ] Are the verification criteria unambiguously assigned to each single system requirement and that each requirement can be verified/evaluated with its verification criteria? <em>(In practice, many requirements may already contain all relevant information regarding verifiability of a requirement.. In such cases, an explicit verification criteria is not needed)</em>

  - [ ] Does the verification criteria define the qualitative and quantitative criteria for the verification of a requirement?<br />
Are the requirements verification criteria addressing :<br />
- What specific aspects, corner cases, combinations to verify?<br />
- What specific quality characteristics have to be covered?<br />
- What are the dynamic aspects related to the requirement to be considered, eg: States, control flow
