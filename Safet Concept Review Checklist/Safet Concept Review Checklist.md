# Task List for Safet Concept Review Checklist - v1.0

- [ ] Schedule and Status

  - [ ] Was the Safety Concept completed and reviewed within the appropriate timeframe?

  - [ ] Is the Safety Concept based on the most recent version of the applicable process?</p>

<p><u><a href="https://inside-ilm.bosch.com/irj/go/nui/cmd/plugin/zversioning/linktoversion/2096a279-3f6c-3110-4496-fed144ff539f?cmd=followlink&amp;guid=/guid/2096a279-3f6c-3110-4496-fed144ff539f&amp;linktype=valid" target="_blank">[LINK] Develop and Maintain Safety Concepts</a></u>

  - [ ] Is front page information completed?

  - [ ] Is the document stored under configuration management, per Project CM plan, in the location defined in the relevant Work Instruction?

  - [ ] All safety concept documents, and the requirements they are based on, and any relevant safety analysis, baselined?&nbsp;&nbsp;&nbsp;

- [ ] <strong>Change Status, Planning</strong>

  - [ ] Where necessary, have changes identified through Impact Analysis resulted in Safety Concept update?

  - [ ] Where necessary, have all safety concept changes been advised to customers &nbsp;and suppliers?</p>

<p>E.g. as indicated in DIA

  - [ ] Have internal safety concepts been revised following safety requirement or safety concept changes from the customer or suppliers?</p>

<p>If no chance in concept was necessary, update history list with the date on which this was checked, and document appropriately

  - [ ] Have safety concepts which were updated been re-verified&nbsp; after update&nbsp; and before release?

  - [ ] Have all changes to safety concepts been reflected into FMEA, FTA and, if needed, DRBFM and FMEDA?</p>

<p>Rate &ldquo;N/A&rdquo; if these documents do not exist yet

  - [ ] Are all open issues relating to safety concepts either in the Closed state, or traceably managed?

  - [ ] Have the safety concepts and all changes been advised to the project security team?</p>

<p><strong>Expected : joint review of concepts, to prevent conflict, duplication and misunderstandings</strong>

- [ ] <strong>Input Requirement (Item Definition) Status</strong>

  - [ ] Is the relevant part of the vehicle architecture and all safety-related requirements from the customer completely available?

  - [ ] Is the configuration of the system to be covered by the safety concept clearly documented?&nbsp; [E.g. exact versions and variants covered, as specified by baselines]&nbsp;&nbsp;

  - [ ] Are scope, system boundary, interfaces and dependencies of the safety-related item clearly identified?</p>

<p>Consider how the boundaries set for this concept may influence or overlap other safety concepts; avoid duplication.&nbsp;

  - [ ] Has the customer provided all required information, including (preliminary) vehicle architecture&nbsp;, functional safety concept, safety goals, ASIL ratings, and the ASIL ratings for all signals at the interface?

  - [ ] Has the vehicle manufacturer supplied sufficient information to allow analysis of failure consequence (including &ldquo;downstream&rdquo; systems) ? If not, has the OEM been informed clearly of the limits of RB Analysis?

  - [ ] If insufficient information is available from the customer, has the product been formally identified as a Safety Element out of Context (SEooC), and the customer notified (using relevant legal template from PDI)?&nbsp;

  - [ ] Are all assumptions about the vehicle, architecture, functional behaviour and other inputs documented and transferred to requirements management system&nbsp; (and issues tracking system, if these are separate)?</p>

<p>Intent : track assumptions like safety requirements, until the assumptions are traceably resolved into actual requirements.

  - [ ] Is it clear what represents a state-of-the-art safety concept for this item, at this ASIL?&nbsp;

  - [ ] Has the safety team considered security vulnerabilities, and incorporated information from the security Threat Analysis (TARA)?

  - [ ] Does the safety concept include provision for misuse of diagnostic interfaces?

  - [ ] Have preconditions that are required for safety relevant functions been communicated to the customer and documented ?

- [ ] <strong>Methodology</strong>

  - [ ] Is all mandatory prerequisite information available, and referenced in the safety concept?

  - [ ] Is information single-sourced, with references used to avoid duplication?

  - [ ] If the safety concept is developed for a Safety Element out of Context (SEooC, see ISO26262-10), are the assumed requirements (including safety goals) accessible and clear?</p>

<p>And are they agreed with the customer ?

  - [ ] Is the safety concept clear, and comprehensible?</p>

<p>Does the document comply with the &ldquo;7 Cs&rdquo; : Clear, Concise, Comprehensible, Coherent, Complete, Consistent, Confirmable&nbsp;?

  - [ ] Is every safety requirement, and the overall safety concept (the complete set of safety requirements), feasible?</p>

<p>Feasible didn&rsquo;t start with &lsquo;C&rsquo;.</p>

<p>&nbsp;

  - [ ] Has each safety concept been updated to include all safety requirements derived from&nbsp; applicable safety analyses (DRBFM, FMEA, FMEDA, FTA, DFA, Safety Impact Analysis&hellip;)?</p>

<p>Don&rsquo;t focus only on technical safety mechanisms implemented in the product.

  - [ ] Does the safety concept adequately describe both safety measures and safety mechanisms?</p>

<p>Don&rsquo;t focus only on technical safety mechanisms implemented in the product.

  - [ ] Have Safety Goals (with accompanying Safe State and FTT information) been completely and traceably transferred into the requirements repository (e.g. DOORS&nbsp;)?

  - [ ] Is a safe state&nbsp; specified (and consistent across safety concepts) for all hazards where a safe state is feasible?

  - [ ] Has it been clearly agreed with the customer, in writing, who is responsible for developing the safety concept, reviewing the safety concept, approving the safety concept, and developing each element of the safety concept?</p>

<p>For example, in a Development Interface Agreement.

- [ ] <strong>Functional Safety Concept</strong>

  - [ ] Are all of the safety mechanisms assumed in the Hazard Analysis included in the Functional Safety Concept?</p>

<p>Specific transfer of assumptions to the requirements repository

  - [ ] Is the functional safety concept traceably derived from the Hazard Analysis (or customer safety goals, or assumed safety goals), and the vehicle architecture?&nbsp;&nbsp;

  - [ ] Does every safety goal have at least one derived functional safety requirement?</p>

<p>Key to safety concept : is the safety concept <em>complete</em>?

  - [ ] Is the <em>set</em> of functional safety requirements that is derived (traceable) from each safety goal <em>complete</em> and <em>adequate</em>?&nbsp;&nbsp;</p>

<p>If this set of requirements is correctly and completely implemented, will the safety goal be met to the extent required for the applicable ASIL?&nbsp;

  - [ ] Is bidirectional traceability implemented between the Functional Safety Concept, and the Safety Goals from Hazard Analysis (or from the customer)?</p>

<p>Can each functional safety requirement be traced to the safety goal(s) from which it is derived?

  - [ ] Is the functional safety concept consistent with, and compliant with, the Safety Goals?

  - [ ] Does the functional safety concept demonstrably prevent or mitigate each associated Hazardous Event&nbsp; (leading to the safety goals covered by the concept)?</p>

<p>A hazardous event can be mitigated by&nbsp; multiple safety goals, and each safety goal can cover multiple hazardous events.

  - [ ] Is the transition&nbsp;to an appropriate safe state clearly specified for each detected fault?&nbsp;</p>

<p>Completeness criterion.</p>

<p>Is the timing for each transition clear, and does it meet the FTTI requirements?</p>

<p>Is it clear when and how the system may leave the safe state once entered?</p>

<p>Does the Functional Safety Concept include the conditions and methods required to enter and remain in every safe state documented&nbsp;in the Hazard Analysis?

  - [ ] Does the Functional Safety Concept include the conditions and methods required to retry and/or resume normal operation after entry into each safe state?</p>

<p>Completeness criterion.

  - [ ] Where necessary, does every functional safety requirement specify an appropriate safe state (and the entry and exit criteria and timing)?</p>

<p>Assess <em>per requirement.</em>

  - [ ] If a safe state cannot be reached with safety time constraints, is an emergency operation and an emergency operation interval specified?

  - [ ] Is each requirement in the Functional Safety Concept allocated, and bi-directionally traceable, to one or more architectural components?

  - [ ] Does the Functional Safety Concept follow the Hierarchy of Controls; that is, does it prioritise prevention / avoidance over technical solutions?

  - [ ] Is the Functional Safety Concept as <em>simple</em> as possible?&nbsp;</p>

<p>If not, where is the complexity, and can it be removed?

  - [ ] Does the Functional Safety Concept specify (for each safety-related function) which faults / failures&nbsp; must be detected&nbsp;, and how they will be detected?&nbsp; [A measure of expected failure rate&nbsp;, and detection coverage is ideal if achievable]</p>

<p>Aim : completeness against the functional model used in safety analysis (e.g. FMEA / FTA) and completeness against every safety requirement. E.g. How can Functional Safety Requirement XYZ fail? How will this be detected? Consider both transient and permanent faults : apply a fault model&nbsp;.

  - [ ] Does the Functional Safety Concept specify (for each safety-related function) how failure will be mitigated (if it can&rsquo;t be prevented&nbsp;)?</p>

<p>(Mitigation can be at a higher level than the requirement under consideration, and one mitigation mechanism may cover many faults).&nbsp; Mitigation doesn&rsquo;t require detection.

  - [ ] Is a fault model documented for each component or function whose failures must be addressed?</p>

<p>If not, how can you demonstrate that all relevant failures have been managed?&nbsp;

  - [ ] Does the Functional Safety Concept specify fault -tolerance mechanisms&nbsp;, including degraded operation modes where applicable?</p>

<p>Are all degraded operation modes included in the safety manual, and the user manual?

  - [ ] Does the Functional Safety Concept specify <strong>warning</strong>&nbsp;<strong> concepts </strong>(for driver, passenger, operator, maintainer...) where needed?</p>

<p>Can really only be done by the OEM; if FSC is developed by Bosch, warning and degradation concept must be agreed with customer. Warning concept must be included in Safety Manual (Bosch-&gt;OEM)and in User Manual or Service Manual (OEM-&gt;Customer)

  - [ ] Does the Functional Safety Concept specify response priority and arbitration when multiple faults or other events occur simultaneously&nbsp;, or response overlaps?

  - [ ] Does the Functional Safety Concept comply with regulatory and legal requirements relating to the controlled system?&nbsp;</p>

<p>(See LDWS for example; a Euronorm exists and must be complied-with, for vehicles sold into Europe)

  - [ ] Is bidirectional traceability implemented between each requirement in each safety concept, and the verification and validation methods applicable to it?&nbsp;</p>

<p>Aim : the reviewer should be able to trace from the requirement to a set of adequate review and test methods, and that each test case (for example) is traceable to the requirements it tests. If a requirement (or architecture element) changes, the affected test cases or other verification methods must be traceable so the verification methods can be checked and changed.

  - [ ] Aim : the reviewer should be able to trace from the requirement to a set of adequate review and test methods, and that each test case (for example) is traceable to the requirements it tests. If a requirement (or architecture element) changes, the affected test cases or other verification methods must be traceable so the verification methods can be checked and changed.

  - [ ] If used, has ASIL decomposition been clearly justified (e.g. by Dependent Failures Analysis), documented in the Safety Concept, and any consequences transferred to all affected systems (including, if necessary, the customer or other suppliers via DIA)?

  - [ ] Does each Functional Safety Requirement subject to ASIL decomposition have a corresponding independence requirement, justified via a dependent failures analysis?</p>

<p>Expected : is it clear how this is implemented in the architecture?

  - [ ] Is State-of-the-Art and best practice from comparable products considered and implemented where required?</p>

<p>Expectation : this will be documented. (See 3.8)

  - [ ] Does the Functional Safety Concept include and address each assumption relating to controllability of the vehicle arising from the Hazard Analysis?</p>

<p>Can really only be resolved by the OEM; if FSC is developed by Bosch, controllability assumptions must be agreed with customer, or explicitly communicated as assumptions to be resolved..

  - [ ] Does the Functional Safety Concept include and address each assumption relating to behaviour of the driver&nbsp; or other participant, necessary to fulfil the safety goal?</p>

<p>Can really only be resolved by the OEM; if FSC is developed by Bosch, driver behaviour assumptions must be agreed with customer.

  - [ ] Does the Functional Safety Concept include and address each assumption relating to means and controls available to the driver or participants, to fulfil the safety goal?</p>

<p>Can really only be resolved by the OEM; if FSC is developed by Bosch, vehicle control&nbsp; assumptions must be agreed with customer.

  - [ ] Does the functional safety concept allocate safety requirements to both individual architectural elements&nbsp;, <em>and their interfaces</em>?</p>

<p>Interfaces are a common source of defects.

  - [ ] Does the Functional Safety Concept include the acceptance criteria for safety validation?

  - [ ] If the functional safety concept depends on requirements allocated to elements or technologies outside the scope of ISO 26262 (e.g. mechanical, pneumatic, hydraulic&nbsp;&hellip;)&nbsp;

  - [ ] If the functional safety concept depends on &ldquo;external measures&nbsp;&rdquo; (requirements allocated outside the boundary of the RB Product)&nbsp; &hellip;</p>

<p>That is, other subsystems in the vehicle, or external (e.g. infrastructure) systems, test or production systems, monitoring systems, or other deliverables such as user manuals, training, warning notices or component&nbsp; marking&hellip;&nbsp;

  - [ ] Are Safety Validation Criteria specified for all aspects of the safety concept that must be validated ?&nbsp;</p>

<p>Validation criteria can also be used for verification&nbsp;&hellip;

  - [ ] Does each functional safety requirement specify the mandatory attributes?</p>

<p>Inherited ASIL, unique ID, status, timing constraints including FTTI, operating modes, safe state, emergency operation + interval, fault tolerance&hellip;

  - [ ] Is validation of each functional safety requirement feasible, specified and scheduled?

  - [ ] Are the partitioning requirements complete and clear at the Systems level? Have all independence requirements and freedom from interference requirements been considered?

- [ ] <strong>Technical Safety Concept</strong>

  - [ ] Is bidirectional traceability implemented between the Functional Safety Concept, and the Technical Safety Concept?

  - [ ] Is the re-use concept clear, for elements of the technical safety concept, and for hardware and software components?

  - [ ] If any programmable hardware is to be utilised (separate from microcontrollers) is an appropriate safety development lifecycle for that element specified, consistent with the highest ASIL of any requirement allocated to the device?

  - [ ] &nbsp;Are the functional and safety requirements for both hardware and software components specified in sufficient detail to allow correct qualification of re-used components?

  - [ ] Is each Technical Safety Requirement at System (product) level allocated to elements of the system design?

  - [ ] Is each Technical Safety Requirement refined to the discipline level (HW, SW) and allocated to elements of the hardware or software design, or their interfaces?&nbsp;

  - [ ] Have Safety Requirements developed as part of a safety concept been managed consistently as requirements (unique ID, reviewed, traceable etc)?</p>

<p>Including, for example, safety mechanisms derived during safety analysis, safety mechanisms derived in order to increase diagnostic coverage, and functional requirements (e.g. from customer spec) that are required by the safety concept but not identified as safety requirements by the originator of the requirement?&nbsp;

  - [ ] Have the assumptions (related to Technical Safety Concept) originating at the higher architectural / functional safety concept level been resolved, or traceably documented and managed?&nbsp;&nbsp;

  - [ ] Are the assumptions made at the technical safety concept level consistent with those from the functional safety concept?&nbsp;</p>

<p>That is, are we assuming different things in the different concepts?&nbsp;&nbsp;

  - [ ] Does the system design fully implement the technical safety concept?

  - [ ] Is the system design verifiable (testable) ?&nbsp; Can each safety requirement at the system level be tested at the system level&nbsp; (or at another level or phase, such as integration)?</p>

<p>And is it agreed by all affected disciplines when and where this will be tested, and who is responsible?

  - [ ] Is it clear that hardware can support the software safety requirements, and software can implement technical safety requirements necessary for safe operation of the hardware?&nbsp;</p>

<p>Example :diagnostics and feedback, comms loopback; self-test of hardware and software; MCU for software partitioning&hellip;

  - [ ] Does system and hardware-software integration strategy include plans to conduct safety verification tests of technical safety requirements, derived according to ISO 26262 requirements?

  - [ ] Does system and hardware-software integration strategy include plans to provide evidence that the (safety) test goals are met, and target coverage is achieved?

  - [ ] Does the technical safety concept include measures to address both transient and non-transient random hardware failures during operation?

  - [ ] Does the systems design, and each discipline design, comply with partitioning requirements?</p>

<p>See 4.42

  - [ ] Has a review been performed to establish and document if there is any aspect of the functional or technical safety concept or implementation that</p>

<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; May be subject to 3rd-party intellectual property rights?&nbsp;</p>

<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; May be a novel and innovative solution to a problem, and therefore patentable and a competitive advantage to RB?</p>

<p>&nbsp;</p>

<p>Expected : both of these issues must be considered. Each is checked in QG or SWQG.</p>

<p>&nbsp;

  - [ ] Does the safety concept adequately consider safety-related configuration, calibration, and variant management?</p>

<p>Are configuration and calibration requirements, processes, specifications, data, component loading, and verification considered &ndash; in Development, and in Production?

  - [ ] Is the configuration and calibration data that could affect safety correctly specified, in compliance with ISO 26262 requirements?</p>

<p>Is the verification of configuration and calibration data, and verification of each variant (the configured and calibrated product) specified and planned?&nbsp;

  - [ ] Has the maximum ASIL of any parent requirement been allocated to derived requirements?&nbsp;&nbsp;</p>

<p>Has an ASIL been allocated to configuration or calibration data, according to the maximum ASIL of any safety requirement that it can violate&nbsp; ?

  - [ ] Are plausibility, integrity and security checks in Production specified for calibration and configuration data?&nbsp;&nbsp;

  - [ ] Are plausibility, integrity and security checks in the product at runtime specified for calibration and configuration data?&nbsp;&nbsp;

  - [ ] Are version checks specified for calibration and configuration data, and checks to prevent use of incompatible&nbsp; parameters or sets?
