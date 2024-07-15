# Task List for Safety Plan Review Checklist - v1.1

- [ ] <strong>Project Planning &ndash; Project Schedule, PMP and Project Charter</strong>

  - [ ] Are the project plans (e.g. Project Schedule, PMP) present in correct location and under CM control?

  - [ ] Is project planning metadata (header, history, status) completed as required by each template ?

  - [ ] Is project planning approval status correct and valid for lifecycle phase ?

  - [ ] Are the project plans complete, correct, up-to-date&nbsp; with safety activities, to the degree appropriate for lifecycle phase ?

  - [ ] Do project plans contain relevant discipline-independent safety activities ?</p>

<p><br />
Needed for synchronisation<br />
<br />
&bull; Safety Plan creation and approval:<br />
- DIA creation, negotiation, review and approval<br />
- All customer-mandated safety tasks + deadlines (e.g. from DIA)<br />
<br />
&bull; Safety Audit planning and conduct<br />
&bull; Subsystem planning, and review of safety-related plans (HW, SW, Sys, Reliability, V&amp;V, PCB&hellip;)<br />
&bull; Safety Audits and Assessment(s)

  - [ ] Do project plans contain required dependencies between safety-related tasks (including synchronisation between disciplines and departments, and if necessary, between locations) ?

  - [ ] Are all quality gates present (QGs, QCGs, SWQAs) ?</p>

<p><br />
Each quality gate plays a part in assessing safety progress and has safety-related questions : ISO 26262-2

  - [ ] Has tailoring of QGs been carried out according to that permitted by CDQ0305 ? (Does not &ldquo;tailor out&rdquo; checks of any safety-related processes)

  - [ ] Does each task have a WBS ID for traceability (and are these consistent across projects?)

  - [ ] Does the PDP contain role assignment ? (Project Safety Manager, Systems Safety Engineer, Discipline safety engineers, Safety Auditor, Safety Assessor&hellip;)

  - [ ] Has validation of estimation been performed ? (resource adequacy)<br />
<br />
Is it clear that the resources provided will be sufficient to fulfil the plans ?

  - [ ] Has competence management (including required training) been adequately considered ?

  - [ ] Is the OPL reviewed and updated regularly ?<br />
<br />
Is the OPL content appropriate ? (not used as substitute project plan or risk list)<br />
<br />
&nbsp;

  - [ ] Has the assessment been planned to establish the safety state-of-the-art to be achieved ?</p>

<p>PJM responsible, according to AE-DI G28.

- [ ] <strong>Safety Plan</strong>

  - [ ] Has the AE-BE Review Report criteria for Safety Plan Confirmation Review been applied?

  - [ ] Is the Safety Plan present in the correct location and under CM control ?

  - [ ] Is the safety lifecycle to be applied clear, and consistent with other discipline plans?&nbsp; Baseline applied ?

  - [ ] Is the project category documented (e.g. new, platform, variant, etc) ?

  - [ ] Has tailoring been approved by the responsible person; QA by QA manager, safety-related tasks by Department Safety Manager&nbsp; ?&nbsp; [See SP1]</p>

<p><br />
Note that tailoring from some of the CoC-FS directives requires additional approval from CoC-FS; for example, changing the process for Software Tools Confidence in Use. See N102 FSxxx policies (read in conjunction with guidelines for Transition projects).

  - [ ] Is referencing of external information adequate ? (links work, information accessible (including to auditors), information not duplicated)

  - [ ] Is translation (including requirements) appropriately planned and resourced&nbsp;?</p>

<p>Lessons learned: resource adequacy for requirements engineering.

  - [ ] Is the project&#39;s CM plan complete, including storage location, archiving and CM control of all safety-related work products ?

  - [ ] Do discipline plans include appropriate metrics targets ?</p>

<p><br />
Hardware: PMHF, SPM, LFP, Diagnostic coverage, depending on ASIL<br />
(Note: this may determine safety analysis methodology selection).<br />
Software : structural coverage metrics<br />
Systems : requirements coverage<br />
<br />
&nbsp;

  - [ ] Is safety workload levelling appropriate ?<br />
<br />
(workload allocated to each person is known and reasonable&nbsp;)

  - [ ] If this project is implemented as planned, is it evident that an ASIL-appropriate degree of safety will be attained ? (That is, will adequate functional and technical safety concepts be implemented) ?

  - [ ] If this project is implemented as planned, is it clear that all evidence required to fulfil the safety case will be produced ?

  - [ ] Has the safety lifecycle been tailored and the task planning updated to include all tasks and work products required to be developed in order to fulfil the safety case?

  - [ ] Are adequate QGx, SWQG, PCOM, PDMM/Technical Reviews or other quality checks planned&nbsp;, and scoped to check the safety activities, or to provide evidence that the Quality Management System ensures the fulfilment of the requirements of ISO 26262 for QM ?</p>

<p><br />
Lesson learned: The QG process allows QGs to be scoped out of (in particular) change projects, and PCOM planning is audit-based, so it is often scoped to exclude specific disciplines (including safety).

  - [ ] Are tasks planned to<br />
<br />
&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Identify innovative processes, designs, architectures, and novel solutions or ideas arising during the safety lifecycle, and secure intellectual property<br />
<br />
&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Establish whether any used (or re-used) designs, implementations, algorithms, architectures or components may be the subject of 3rd-party property rights, and establish our license to use them ?

- [ ] <strong>Process and Methodology Planning</strong>

  - [ ] Have all methods to be applied been planned, with ASIL-appropriate justification?

  - [ ] Are the safety analysis methods to be applied included in the plan ?

  - [ ] Is Hazard Analysis adequately planned, with independent review ?

  - [ ] Is safety impact analysis and change management planned, with independent review ?

- [ ] <strong>Development Interface Agreement</strong>

  - [ ] Does the DIA include agreement on integration, including responsibilities for integration and test at each level ?</p>

<p><br />
Lesson learned: Care: integration of models, for example, can be fraught. If the OEM supplies a model, is it complete ? Has it been validated ? Is it suitable to generate automatic code from ? Who is responsible for updating it; how is it CM-controlled ? On change, who will re-validate it and what is the regression strategy?<br />
Is it in a suitable format ? Who is responsible for translation ?<br />
If separate functions are modelled, how are the separate functions integrated into a systems design, and who is responsible ?

  - [ ] Are targets recorded for hardware metrics and diagnostic coverage (and aligned between customer target and ISO26262 requirements) ?

  - [ ] If the customer refuses a DIA, have the SEooC expectations of Bosch been communicated clearly to them ?&nbsp; Have all subsequent assumptions regarding safe use of the SEooC product been included in the TCD / TKU and communicated to the customer ?

  - [ ] Is the ownership (and permitted use) clearly agreed for any IP<br />
<br />
&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; developed in the project<br />
&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; which the customer requires to be used ?

- [ ] <strong>Planning of Verification and Confirmation Reviews, Audit, Assessment&nbsp;</strong>

  - [ ] Are Verification and Confirmation Reviews scheduled at appropriate times per Review Concept ?

  - [ ] Have all mandatory item reviews been completed, and open issues been managed to closure ? (Is effort to close open issues included in estimates ?)

  - [ ] If ASIL decomposition is applied, are confirmation measures planned at the ASIL of the safety goal&nbsp;?

  - [ ] Is safety auditing planned, with appropriate depth, scope, and (early) schedule ?

  - [ ] Is safety assessment planned (see template), and a Safety Assessor available with sufficient competence and independence ?

- [ ] <strong>Test, Quality and Release Planning</strong>

  - [ ] Have test plans been reviewed and approved ?

  - [ ] Are test coverage targets planned for all disciplines ?&nbsp;

  - [ ] Has release planning been performed&nbsp;? Is it evident that complete safety requirements test coverage will be achieved for each release&nbsp; ?

  - [ ] Has test planning for all changes been performed and reviewed ?

  - [ ] Is the strategy for regression testing / verification planned at all levels; documents, code, integration, systems, communications, interfaces, in-vehicle, safety requirements&nbsp; ?</p>

<p><br />
Lesson learned : the basis for regression testing is often unclear in change projects; sometimes it&rsquo;s &ldquo;test everything&rdquo;, sometimes it&rsquo;s :only test the changes&rdquo; (which does not adequately support an argument that changes have not interfered with safety functionality. Strategy rarely refers to interfaces and dependencies.

  - [ ] Is the strategy for dealing with verification results agreed&nbsp; and enforced?</p>

<p><br />
Lesson learned: A project that was happily heading towards release, with 58,000 unmanaged QA-C warnings. Nobody was looking, nobody had a plan to deal with them, no resources were allocated, nobody had any idea of the risk. The project had no rules for which verification results had to result in action, and clearly no process for checking for verification fails.

  - [ ] Is the strategy for dealing with verification results agreed&nbsp; and enforced?</p>

<p><br />
Lesson learned: A project that was happily heading towards release, with 58,000 unmanaged QA-C warnings. Nobody was looking, nobody had a plan to deal with them, no resources were allocated, nobody had any idea of the risk. The project had no rules for which verification results had to result in action, and clearly no process for checking for verification fails.

- [ ] <strong>Tools and Re-Use Planning</strong>

  - [ ] Is tool classification / qualification of safety-related project-specific tools planned&nbsp;and status reasonable ?</p>

<p><br />
Expected: Project has a (current) complete list of tools which will be used in the project.<br />
Project understands which tools are being assessed by RB or AE and which it must assess itself.

  - [ ] If ASIL D -&gt; ASIL B(D) decomposition is used, is tool management planned to fulfil ASIL D requirements&nbsp;?

  - [ ] Is the safety lifecycle tailored as necessary to provide checks of the output from safety-related tools, where qualification has not been performed&nbsp;?

  - [ ] Are Make/Buy/Re-use decisions conducted (or planned) to determine <strong>software </strong>and <strong>hardware </strong>component re-use?<br />
<br />
Is Qualification of re-used software and hardware components planned&nbsp;?

  - [ ] Are activities&nbsp; (including quality checks) planned to ensure that tailored lifecycle consistently enforces the lifecycle activities that were planned to manage tool-related risks?</p>

<p><br />
Lesson Learned : When confidence-in-use-of-tools planning specifies that an activity (say, a check step downstream in the lifecycle) is necessary to manage safety risk of tools, that activity becomes safety-related. So it has to be planned, it has to be done, and it has to be checked by quality checks, to provide evidence that it was done.&nbsp;<br />
If that doesn&rsquo;t happen, then the safety risk from the tool has not been adequately managed.

- [ ] <strong>Progress Monitoring</strong>

  - [ ] Is progress tracked and visible&nbsp; ?<br />
<br />
Is actual effort or duration complete appropriately ?<br />
<br />
Are &ldquo;completed&rdquo; / &ldquo;% completed&rdquo; fields maintained ?</p>

<p><br />
Example Criteria: Open Gannt Chart, filter by safety tasks; plan is complete, is based on the right template, contains expected activities and tailoring, has assigned resources for all safety tasks, resources are approved and allocated. Effort estimates appear reasonable. Due dates are present and appear reasonable, sequence is appropriate, dependencies are met. See safety plan review criteria.

  - [ ] Are assumptions being appropriately managed and systematically &ldquo;closed&rdquo; ?
