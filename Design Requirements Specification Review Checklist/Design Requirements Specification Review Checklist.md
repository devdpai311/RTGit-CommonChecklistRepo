# Task List for Design Requirements Specification Review Checklist - v1.0

- [ ] <strong>General</strong>

  - [ ] Are all requirements actually requirements, not implementation solutions?<em> (Separation of the &ldquo;what?&rdquo; and the &ldquo;how?)</em><br />
Are all requirements actually requirements, not constraints?<br />
Are all the functional requirements Feasible? (Are all functional requirements possible to implement?)<br />
Even if feasible, are they relevant and necessary?

  - [ ] Is there objective evidence that the requirements development process was actually used when developing the requirements?<br />
Is each requirement compliant with the SYS Eng process?

- [ ] <strong>Clarity</strong>

  - [ ] Are the requirements defined at the Correct level? (<em>Segregrate requirements at System level, Software level, implementation conventions etc</em>)<br />
Are the stated objects (nouns) in the requirement defined with the right context level?<br />
<em>(e.g. &quot;The vehicle shall...&quot; vs &quot;The ECU shall...&quot; vs &quot;The microcontroller shall&quot; vs &quot;The software module shall...&quot;)</em>

  - [ ] Are all the functional requirements Measurable, Verifiable and Feasible?<br />
<em>(E.g. Avoid requirements like: The output should be good or response should be fast. Correct Way: The response time&nbsp; should be within 10 milliseconds)&nbsp;</em>

  - [ ] Are the requirements well-defined and understandable for the readers?<br />
Are the statements sufficiently/concisely stated? <em>(i.e. no unnecessary complicated and long sentences)</em><br />
Are all abbreviations, acronyms, definitions and technical terms defined in Glossary are clear and consistently used?

- [ ] <strong>Completeness</strong>

  - [ ] <u>DRS-specific: Has every requirement been assigned to a single domain?</u>

  - [ ] Are all required functions, interfaces (incl. test requirements), scenarios (during the project lifecycle incl. possible defects and exception situations), qualities and design constraints (incase of existing reference architecture) considered?<br />
<em>Examples:<br />
- timing constraints<br />
- each operating mode of the vehicle, the system, or the hardware, and their impacts<br />
- shared and exclusive use of hardware resources (including memory mapping, allocation of registers, timers, interrupts, I/O ports</em>

  - [ ] Are all Safety, security and legal requirements and special charecteristics properly identified and classified accordingly?<br />
<em>(Refer Safety, security and legal requirements review checklist for complete review of these SSL requirements)</em>

- [ ] <strong>Consistency</strong>

  - [ ] Is the document free of any ambiguous or inconsistent&nbsp; or contradictory statements?<br />
Are the requirements free of redundancies? <em>(Same requirement(s) mentioned in more than one place should be recognized and removed)</em><br />
Is each requirement uniquely identifiable?<br />
(e.g. each requirement in DOORS is assigned an identification number.)<br />
Are there multiple requirements sharing the same identifier?<br />
Can the requirements be evaluated and prioritized? Are there appropriate attributes attached?<br />
e.g. InDate, OutDate, Variant, ASIL&hellip;

- [ ] <strong>Correctness</strong>

  - [ ] Are the verification criteria properly assigned to each single system requirement and that each requirement can be verified/evaluated with its verification criteria? (In practice, many requirements may already contain all relevant information regarding verifiability of a requirement.. In such cases, an explicit verification criteria is not needed)<br />
Does the verification criteria define the qualitative and quantitative criteria for the verification of a requirement?<br />
Are the requirements verification criteria addressing :<br />
- What specific aspects, corner cases, combinations to verify?<br />
- What specific quality characteristics have to be covered?<br />
- What are the dynamic aspects related to the requirement to be considered, eg: States, control flow
