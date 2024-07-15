# Task List for Safety case checklist - v1.1

- [ ] <strong>Schedule and Status</strong>

  - [ ] Is the Safety Case sufficiently complete for this phase of the safety lifecycle ?</p>

<p><br />
<strong>Expected</strong>:<br />
a)&nbsp;&nbsp; Development component complete before Development release phase;<br />
b)&nbsp;&nbsp; Manufacturing component complete before Product release.<br />
c)&nbsp; Structure of safety case is available to review before QGC2

  - [ ] Was the Safety Case review concluded within an appropriate timeframe ?</p>

<p><br />
<strong>Expected:</strong><br />
a) safety argument structure reviewed early (before QCG1)<br />
b) &hellip; and not 30 seconds before the release is required

  - [ ] Is the Safety Case report based on the correct (most recently released, or project baselined) version of relevant templates (report, argument) ?

  - [ ] Is the front page information completed ?<br />
(including team membership, scope, and independence)

  - [ ] Is all referenced material stored under configuration management, per Project CM plan ?</p>

<p><br />
Archiving according to CD02981 &ldquo;Information Governance&rdquo; must be established.<br />
<br />
<strong>Implied:</strong> There must be an approved project CM plan.

  - [ ] Is a baseline for Safety Case review available, containing all items to be included in (or reviewed as part of) the safety case (label given in table above) ?<br />
<br />
Is each document to be reviewed or referenced under CM control and baselined according to CM plan / naming convention?</p>

<p><br />
<strong>Note</strong>: baseline may not be complete yet: some evidence may not be available yet; this confirmation review won&rsquo;t be.<br />
<br />
<strong>Experience</strong>: very often the document is reviewed late, and it is under active development whilst review is performed. The document is therefore changing as the review takes place and WHICH version was reviewed&nbsp; may be unclear.&nbsp; Whether required changes have been implemented can also be unclear.<br />
<br />
<strong>Experience</strong>: Key documents are usually not baselined to align with safety-case review, so it&rsquo;s difficult to tell which version of the Product Spec, Vehicle Wiring Diagram, Sales Drawing or Customer Spec was used at different phases. This is critical when arguing that customer safety requirements have been met. CMM or PDMM can be accepted a baselines as long as they record exact versions of each key document.

  - [ ] Have the appropriate processes or standards for the safety case been baselined ?</p>

<p><br />
<strong>Expected:</strong> The project plan, or project safety plan, contains a baseline section listing applicable processes (and tailoring, if applied)

  - [ ] Has the safety case been developed and reviewed by an appropriately-competent team been trained in the agreed process, with disciplines adequately represented?

- [ ] <strong>Change Status</strong>

  - [ ] Is the Safety Case up-to-date ?<br />
Does it correctly refer to the right version(s) of the product ?</p>

<p><br />
<strong>Expected</strong>: the safety case is up-to-date, and it contains a &quot;versions table&quot; listing all product versions and variants to which the safety case applies.

  - [ ] Are all Open Issues either closed or traceably managed to closure, with a deadline and assigned responsibility ?</p>

<p><br />
<strong>Expected</strong>: the safety case references a current project OPL, in which safety-related issues and their status can be clearly and separately identified.<br />
<br />
<strong>Experience</strong>: it is often the case that safety open issues are scattered across multiple OPLs (for example, a customer-visible OPL, and a project-visible OPL, and special-purpose OPLs).

  - [ ] Are all Safety Case revisions listed on the Change History Sheet ?

  - [ ] Do all claims refer to the <em>current</em> version of the product ?</p>

<p><br />
<strong>Example</strong>: a safety case that refers to test results from a previous release. Functions or modules had been changed but not re-tested.&nbsp; No documented (regression) test strategy existed.&nbsp; Appeared to be a blatant attempt to cover up lack of testing &ndash; but may in fact have been a simple mistake or misunderstanding.

  - [ ] Do all change projects have an adequately complete safety impact analysis, with resulting approved planning?&nbsp;</p>

<p><br />
<strong>Expected</strong>: Relevant for entire projects (facelift, release for new model or variant&hellip;) but also in cases where an existing project changes in safety-related ways.

- [ ] <strong>Prerequisites</strong>

  - [ ] Is the safety case mature enough to be reviewed ?</p>

<p><br />
Reviews can take place at different lifecycle stages, for different purposes (e.g. review of argument, review of structure, review for planning, review of evidence completeness).&nbsp;<br />
<br />
Maturity would be expected to be high for a Confirmation review (required by the Standard), but perhaps lower for a review requested to assist the authors to identify improvements.The document should be mature enough for the purposes of the current review type].

  - [ ] Are safety-case components (<em>including all referenced data and documents</em>) originating in a language other than English sufficiently and adequately translated to allow a judgement of functional safety ?</p>

<p><br />
Difficulties experienced in: letters to / from customer, contract offer, acceptance, legal issues, FMEA, safety analysis, RCM entries, test cases, test results.

  - [ ] Is information (evidence) sufficiently accessible ?<br />
<br />
&nbsp;&nbsp;&nbsp; - Presence and adequacy of summaries of key info<br />
&nbsp;&nbsp;&nbsp; - Correctness and completeness of links<br />
&nbsp;&nbsp;&nbsp;&nbsp;- Completeness of the information to which links refer<br />
&nbsp;&nbsp;&nbsp;&nbsp;- Required security access provided</p>

<p><br />
<strong>Experience</strong>: if you have to dig for an hour to find the system test results or other key evidence, it&rsquo;s an automatic fail.<br />
Preparation and presentation of the evidence is the responsibility of the safety engineer preparing the safety case.

  - [ ] Are acronyms avoided where possible, or explained where not ?</p>

<p>e.g. an open defect exists called &quot;Influence of LDS state on SRA&quot;.&nbsp;<br />
<br />
What is this, and what is the safety impact ?

  - [ ] Does the report clearly show whether&nbsp; compliance is achieved with safety goals / safety requirements ?&nbsp;

  - [ ] If compliance with the safety goals is not achieved, does the report clearly show which requirements have not been met ?

  - [ ] If compliance with ISO 26262 is not achieved, or compliance with the safety goals is not evident, how is safety of the product guaranteed ?</p>

<p><br />
<strong>Expected</strong>: An assessment according to RB/GF 182 must be able to establish that state-of-the-art in safety for a product of this type has been achieved.

  - [ ] Was Department data updated to include metrics and findings from this safety case, and this review, if appropriate ?</p>

<p><br />
<u><a href="https://inside-docupedia.bosch.com/confluence/display/FSAFERBUAU/Department+Hazard+Analysis+Ratings+Repository" target="_blank">[LINK]<br />
Lesson Learned: consistency between projects</a></u>

  - [ ] Are the responsibilities clear for the safety case ? Is it clear how handover will be managed to Production ?

  - [ ] Does the safety case include evidence of the fulfilment of allocated hardware architectural metrics targets?

  - [ ] Does the safety case include evidence of the effectiveness of safety mechanisms ?</p>

<p>(and, of course, a list of those mechanisms&hellip;)

  - [ ] Is evidence provided showing the specification of dedicated measures for all single-point faults in an ASIL C/D system?

- [ ] <strong>Argument</strong>

  - [ ] Is the Safety Case argument documented in an approved notation ?<br />
&nbsp;&nbsp;&nbsp;

  - [ ] Is the safety case argument structure correct ?&nbsp; Clear ?&nbsp; Consistent ? Complete ?

  - [ ] Does the safety case form a <em>convincing </em>argument that all safety requirements have been identified and have been fulfilled ?</p>

<p><br />
<strong>Expected</strong>: argument and evidence about completeness of safety requirements.<br />
<br />
<strong>Tailoring</strong>:&nbsp; consider how to manage this for transition projects, and change projects.

  - [ ] Is the overall Safety Argument strategy clear, and is it based on an appropriate pattern ?</p>

<p><br />
Typically, used for change projects, SEooC, and transition projects.<br />
<br />
e.g. At Least As Safe As<br />
Safe by Compliance with Standard<br />
Safe by Mitigation of all Hazards<br />
<br />
&lt;See references&gt;

  - [ ] Is each safety argument strategy completely and correctly implemented?</p>

<p><br />
For &ldquo;At Least As Safe As&rdquo; (product+process) or &ldquo;Safe by Compliance&rdquo; (process) strategies, where the argument used is &ldquo;product is safe because it was produced using the same processes as previously safe products&rdquo;:<br />
<br />
- what evidence is available that the previous / comparable products are acceptably safe?<br />
- was the same process baseline used ?<br />
- was the same degree of review, testing, analysis done (e.g. to demonstrate freedom from interference)<br />
- was compliance with the processes demonstrated comprehensively ?<br />
- were the processes applied by an equivalently-skilled team ?

  - [ ] Does the safety argument include adequate measures to manage systematic faults ?</p>

<p>Evidence of adequacy?<br />
<br />
All Software problems are systematic, so any safety case involving software requires a process argument (including at least strong V&amp;V, and possibly modelling) showing that &ldquo;best practice has been used to identify and avoid SW-systematic faults&rdquo;.&nbsp;

  - [ ] Does the safety argument include adequate measures to manage random hardware faults ?</p>

<p>Evidence of adequacy ?

  - [ ] Does the argument that the &ldquo;overall system is acceptably safe&rdquo; include adequate argument that the system is safe in the presence of failure modes ?</p>

<p><br />
And not just safe under nominal / normal operation.<br />
<br />
Implies fault injection or other robustness testing methods.

  - [ ] Does the argument include compliance with relevant legislation, regulations and standards?

  - [ ] Does the argument adequately show that interactions between features are identified and tested-for in acceptance testing?

  - [ ] Have known argument fallacies and typical argument flaws been avoided?&nbsp;</p>

<p><br />
Typical flaws in argument : discoverable versus undiscoverable hazards.

  - [ ] Is the argument both credible and defensible ?<br />
(Process, people, product)</p>

<p><br />
<strong>Credible</strong>:<br />
e.g. widely used in industry for some time<br />
-other people in industry recognise it as a proper system to use<br />
<br />
<strong>Defensible</strong>:<br />
e.g. qualified tools, trained operators<br />
-training in processes<br />
-beware proprietary tools

  - [ ] Does the argument include people?<br />
<br />
(Trained and competent, using a suitable technique, with a good process, adequate resources and know-how, to complete and interpret an analysis correctly).</p>

<p><br />
Elements of process argument<br />
-competency of personnel<br />
-Suitability and reliability of methods<br />
-Qualification of tools<br />
-suitability and clarity of notations<br />
-Independence (personnel and organisational)

  - [ ] If expert judgement was used, is the expertise justified and relevant ?<br />
<br />
Is the judgement well-founded, documented, based on defined criteria, and reviewed?

  - [ ] Is the (regression) test strategy clearly documented ?<br />
<br />
Is the regression test strategy applied consistently ?

  - [ ] If tests were omitted (based on expert judgement or ITCB decision) are the omitted tests, and the justification for omission clearly recorded?</p>

<p><br />
Otherwise, when we look at test results and see missing data, it is not possible to tell if the tests were deliberately or accidentally omitted.

  - [ ] Is past tense used for each argument, and future tense avoided ?</p>

<p><br />
That is, is the safety argument based on what was performed rather than good intentions?<br />
If you ever see the words &ldquo;will be&rdquo;, &ldquo;should be&rdquo; or &ldquo;expected&rdquo;, be suspicious.

  - [ ] Have Lessons Learnt from previous products of similar type been considered ?

  - [ ] Was the safety case created for a safety element out of context (SEooC) ?<br />
<br />
If so, have all assumptions been clearly documented, and are the assumptions valid?&nbsp;

  - [ ] Are all assumptions documented and transferred to requirements and task management system ?</p>

<p><br />
Especially those related to SEooC<br />
<br />
<strong>Expected</strong>: Assumptions related to customer use or behaviour, or related to controllability or safety validation, must be in the TCD.<br />
<br />
&nbsp;

  - [ ] Is evidence presented that project safety Open Issues are closed or appropriately managed to closure (for this project phase)?</p>

<p><br />
<strong>Example</strong>: CPC shows approximately 10 open defects and 5 open change requests. In a complete safety case, I would expect a summary showing that these had been analysed for safety impact, and if a potential impact was found, a statement of the risk.<br />
In the safety case for a product to be released, I would expect no open evidence items &ndash; or at least very few, and those risk-managed.

  - [ ] Does the argument appropriately include assessment and management of product security ?</p>

<p><br />
<strong>Expected</strong>: an assessment is performed, and the safety case references evidence that security has been achieved.. &ldquo;If it&rsquo;s not secure, it&rsquo;s not safe&rdquo;.

  - [ ] Does the argument include assessment and management of secure access via debug ports (and equivalent channels) ?</p>

<p><br />
<strong>Expected</strong>: a ruling was issued by RB Safety Control Board that threats to safety through accidental or malicious access via debugging facilities must be assessed. Security team may do this, but safety case must reference the outcome.

  - [ ] Does the safety case include weaknesses, challenges to validity, and areas of uncertainty ?

  - [ ] Is counter-evidence adequately considered?

- [ ] <strong>Evidence</strong>

  - [ ] Does the safety case evidence include the work products required by the safety plan, the DIA, (and the RB processes implementing ISO 26262) for this project?</p>

<p>Will vary based on ASIL, tailoring, chosen lifecycle, etc

  - [ ] Does the claimed evidence exist ?<br />
<br />
Were the tasks claimed performed (properly) ?</p>

<p><br />
<strong>Example</strong>: a safety case claimed compliance with MISRA rules, but no static analysis had been performed. This may be counter-evidence that the software team is not sufficiently competent in the development process.<br />
(The alternative seems to be either a copy-and-paste error, or an attempt to deceive the safety assessor, which is culpable). It&rsquo;s not a good look to have to choose between carelessness, incompetence, or duplicity.

  - [ ] Does the evidence show what the team claims it does ?</p>

<p><br />
Many fallacies seen, and (sometimes reasonable) assumptions that evidence supports the argument.&nbsp; When you look at the evidence, it&rsquo;s obsolete, incomplete, missing or inadequate.<br />
<br />
<strong>Examples</strong>: &ldquo;SWQA shows that we performed the appropriate processes properly.&rdquo;&nbsp; In fact, the SWQA showed that some safety related processes were omitted (without approved tailoring) and others performed inadequately, with many open issues unresolved.

  - [ ] Has the impact of variants been taken into account ? Is it clear that all relevant safety mechanisms are present on all variants ?

  - [ ] Is the Safety Case Report conclusion present and adequately justified ?

  - [ ] Does the safety case have (or refer to) an open-points list that identifies safety-related open issues ?</p>

<p><br />
e.g. pending results, pending customer decisions, etc that are needed to contribute to the argument or evidence.

  - [ ] Is there evidence that preconditions required for safety relevant functions have been fulfilled?</p>

<p>e.g. required battery excitation for battery monitoring by EBS

- [ ] <strong>Customer Interface</strong>

  - [ ] Does the safety case provide evidence that the jointly tailored lifecycle was followed, as agreed with the customer ?

  - [ ] Does the safety case report include all information agreed to be provided to the customer, (without unduly disclosing RB IP)?

  - [ ] Is all customer-specified testing carried out, and any remaining defects identified, tracked and results advised to, and approved by, customer?

  - [ ] Does the safety case include evidence of the safety of agreed common tools (including requirements for qualification when common tools are used to develop decomposed B(D) requirements)?

  - [ ] If the DIA requires us to contribute to the customer&rsquo;s safety case, is this provided for?

  - [ ] Are measures that were defined during customer communication that are required to achieve a proper higher level (customer) safety concept been document properly ?

  - [ ] Are functional restrictions clearly defined and documented ?&nbsp;</p>

<p>e.g.<br />
<br />
- For battery monitoring, only certain battery types are allowed to be used<br />
&nbsp;<br />
- Battery change expected every 4 years<br />
<br />
- etc.
