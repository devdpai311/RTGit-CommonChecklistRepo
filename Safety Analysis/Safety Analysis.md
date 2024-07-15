# Task List for Safety Analysis - v2.0

- [ ] Basic

  - [ ] Was the Safety Analysis completed, and review concluded within appropriate timeframe?

  - [ ] Is the analysis based on the correct (most recently released) version of template?

  - [ ] Has the team been trained in the agreed process?<br />
Was the analysis conducted by an appropriately-competent team, with disciplines adequately represented?

  - [ ] Is front page information completed?

  - [ ] Has the Safety Analysis review baseline&nbsp; been completed?</p>

<p>&nbsp;

  - [ ] Has the team been trained in the agreed process? Was the analysis conducted by an appropriately-competent team, with disciplines adequately represented ?</p>

<p>&nbsp;

  - [ ] Has the appropriate combination of safety analyses (for this ASIL rating and project type) been selected, planned and documented ?</p>

<p>&nbsp;

  - [ ] Have the processes&nbsp; and standards for the safety analysis been baselined (and referenced in the safety plan or project plan)?</p>

<p>&nbsp;

  - [ ] Has the safety analysis been carried out according to the objectives&nbsp; recorded in the Safety Plan ?

- [ ] <strong>Change Status</strong>

  - [ ] Is the Safety Analysis up-to-date with requirements and architecture changes to the product (from all sources)?

  - [ ] Have changes identified through Impact Analysis resulted in updated Safety Analysis when appropriate?

  - [ ] Have all changes&nbsp; been reflected into FMEA, FTA and, if needed, DRBFM or Hazard Analysis?

  - [ ] Are all revisions listed on the Change History Sheet?&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

  - [ ] Are all Open Issues &nbsp; originating from the safety analysis (or affecting the analysis : e.g.&nbsp; issues open against other analyses, or documents on which the analysis depends) either closed or traceably managed to closure, with a deadline and assigned responsibility ?

  - [ ] Is the relevant Control Plan referenced on the Summary Sheet if special characteristics have been defined?</p>

<p>Has the Control Plan and Special Characteristics summary sheet been updated if necessary ?</p>

<p>&nbsp;

- [ ] Prerequisites and Requirement Status

  - [ ] Are architecture descriptions complete and clear for hardware, software, systems (as appropriate for the types of analysis)?&nbsp;&nbsp;

  - [ ] Does each architecture description [vehicle, systems, hardware, software , safety, network&hellip;] support visible and traceable allocation of safety goals or requirements to architecture elements?

  - [ ] Are requirements&nbsp; (including safety goals) completely available&nbsp; ?<br />
(Including timely translation if required)

- [ ] <strong>Reporting and Managing Results</strong>

  - [ ] Does the report clearly show whether or not compliance is achieved with safety goals / safety requirements?&nbsp;&nbsp;

  - [ ] If compliance with the safety goals is NOT achieved , does the report clearly show what mitigation measures must be implemented?&nbsp;

  - [ ] Have Lessons Learnt been considered ? For example, relevant 8D reports, PSS sheets and AE lessons learnt?

  - [ ] Was the ISO 26262-5:2011E Figure 3 / 4 flowchart used to determine when additional safety mechanisms were required?

  - [ ] Have the hardware metrics targets been documented, and clearly agreed with the customer?&nbsp;<br />
[PMHF , SPFM , LFM&nbsp; for each safety goal, diagnostic coverage for each hardware part]<br />
Has the proportion of each metric allocated&nbsp; to the RB product been clearly established?<br />
(For SEooC products, is this clearly recorded as a requirements assumption?)

- [ ] <strong>Failure Data and Fault Models</strong>

  - [ ] Have fault models&nbsp; been defined and agreed (for the appropriate ASIL ratings)?&nbsp;&nbsp;

  - [ ] Are the failure rates used based on correct parameters and calculations for each component?<br />
Is the failure-rate data based on an approved&nbsp; industry source (and supplier data where available)?

  - [ ] Is a correct and valid temperature profile known and applied to the calculation of failure rates for this analysis ?&nbsp;<br />
Has this been agreed with the customer ?

  - [ ] Is the failure-rate data for existing defined components re-used (e.g. sharing validated data between projects)?<br />
Have consistent values been used for each safety analysis of the same product?

  - [ ] Have new component models created for this project been validated, and updated into the Department repository for the use of other projects?

  - [ ] Is failure rate data used from an appropriate&nbsp; source (e.g. derived from Siemens Norm SN29500)?&nbsp;

  - [ ] Was Department data updated to include Exposure estimates if unique scenarios were analysed?

- [ ] <strong>Scope and Architecture</strong>

  - [ ] Are all assumptions&nbsp; (related to Item definition, architecture, safety issues and the safety analysis) documented and transferred to the requirements (or open-issue management) system?<br />
Are all independence assumptions explicit&nbsp; and documented?

  - [ ] Is the Item definition from the customer, and the systems design from RB, sufficiently complete to allow valid safety analysis ?<br />
Are the scope, system boundary , interfaces and dependencies clearly identified?

  - [ ] Was the analysis based on a clear system-level architecture / diagram, showing all affected components?

- [ ] <strong>Methodology</strong>

  - [ ] Are faults and failures which could lead to a breach of the safety goals or safety requirements systematically&nbsp; identified ?

  - [ ] Does the safety analysis include analysis of compliance with temporal safety requirements (including Fault-Tolerance Time and derived timing parameters )?

  - [ ] Is the level of detail&nbsp; of each safety analysis set appropriately?

  - [ ] Have all parameters (failure rates, safety relevance, failure mode distributions, coverage) been reviewed, are they consistent, justified where required?&nbsp;

  - [ ] Has software been included comprehensively in the analysis&nbsp;&nbsp; as:<br />
&bull; potential cause for failures<br />
&bull; detection method, and<br />
&bull; mitigation action?

- [ ] <strong>Safe States</strong>

  - [ ] Was Department data updated to include specific component failure-rate data generated or acquired for this project?

  - [ ] Are diagnostic features&nbsp; defined which support field monitoring and reporting of safety-related issues during operation?

  - [ ] Was analysis performed on a safety element out of context (SEooC) ? If so, have all assumptions been clearly documented, and are the assumptions valid?

  - [ ] Does the analysis evaluate and provide evidence of the effectiveness&nbsp; of safety mechanisms (e.g. by estimating diagnostic coverage)?

  - [ ] Does the Safety Analysis consider any potential causes (or additional investigations) noted in the Hazard Analysis?

  - [ ] Are systematic and adequate techniques used to determine the failure modes, diagnostic coverage and safety mechanisms?

  - [ ] Has an adequate diagnostic and warning concept been developed for each safe state?<br />
(How does the driver and the rest of the vehicle know that a safety mechanism has been triggered and safe state entered?)

  - [ ] Have dependent failures&nbsp; been systematically sought in the safety analysis ?&nbsp;<br />
If identified, has the effect of dependent failures been taken into account in calculation of failure rates and development of safety mechanisms?<br />
Could a fault that causes a safety function to fail also affect the safety mechanism?

- [ ] <strong>Safety Mechanisms</strong>

  - [ ] Have any safety mechanisms or identified safety requirements outside the scope&nbsp; of ISO26262 (e.g. mechanical, or non-functional) been clearly notified to the development team and/or the customer, and added to a repository to ensure they are not &ldquo;lost&rdquo;?

  - [ ] Have identified Safety Mechanisms been completely and traceably transferred into the requirements repository (e.g. DOORS)?

  - [ ] Have Safety Mechanisms been managed consistently as requirements&nbsp; (unique ID, reviewed, traceable, test cases defined)?

  - [ ] Has the impact of variants been taken into account ? Is it clear that all necessary safety mechanisms are present on all variants?

  - [ ] Is a clear justification&nbsp; provided for the % coverage claimed for each safety mechanism (via completed tests, analysis, or reference to ISO26262 Part 5 Annex D)?

  - [ ] Are safety goals and safe states internally consistent?

  - [ ] Are dedicated measures&nbsp; specified for all single-point faults in an ASIL C/D system?

  - [ ] Have all additional safety mechanisms&nbsp; identified by the safety analysis been specified by traceable requirements, implemented and tested?

  - [ ] Is it shown that all failure modes which may result in violation of a safety goal are covered by safety mechanisms&nbsp;.

- [ ] <strong>FTA</strong></p>

<p>If PMHF metric is not used, and evaluation&nbsp; of individual failures is required :<br />
<br />
a) Have individual hardware-part faults (which may result in a single-point fault violating a safety goal) been fully evaluated, and evidence provided to show that each fault meets the required probability of failure?<br />
b) Where evidence&nbsp; for probability of failure is not adequate, what alternative methods are used to protect against this fault?<br />
<br />
(NB: Bosch currently requires PMHF method to be used (9.4.2) and not 9.4.3)

  - [ ] If FTA contributes to Dependent Failures Analysis, have selected cut-sets of order 2 or greater been assessed for independence between events in the cut-set&nbsp;?</p>

<p>Expected : where cut-sets include a safety function, and a safety mechanism protecting that function, DFA must be considered for ASIL B and above.</p>

<p>&nbsp;

- [ ] <strong>FMEDA</strong> - Specific

  - [ ] Has the diagnostic coverage&nbsp; (by safety mechanisms) of residual and latent faults&nbsp; been estimated for all safety-related hardware?<br />
<br />
Have the estimates for diagnostic coverage been justified (e.g. from Standard source, or from statistical analysis of test results)?

  - [ ] If expert judgement&nbsp; was used to estimate component failure rates (for example, where no data was available from standard sources, or the manufacturer), has clear, documented criteria for the estimate been established and used?<br />
If field data has been used, has an adequate confidence level been established?

- [ ] <strong>Hardware Metrics</strong>

  - [ ] Have dedicated measures been specified for all cases where hardware parts have an estimated diagnostic coverage&nbsp; &lt; 90% (For ASIL C and D safety goals)?

  - [ ] Does the safety report adequately assess&nbsp; potential weaknesses of the safety concept?<br />
<br />
Are areas where safety mechanisms may be ineffective (for example in detecting latent faults, multiple-point faults, common cause failures and cascading failures) clearly identified?

  - [ ] Is it shown that for each safety goal, the product hardware meets the Single Point Fault Metric (SPFM) target&nbsp; of ISO26262-5 (8.4.5) appropriate for the product&rsquo;s ASIL rating ?</p>

<p>[As recorded in 4.5 above. The hardware must meet the most conservative target : either from ISO26262 Table 4, or as allocated to this hardware element of the Item by the customer].

  - [ ] Is it shown that for each safety goal, the product hardware meets the Latent Fault Metric (LFM) target&nbsp; of ISO26262-5 (8.4.6) appropriate for the product&rsquo;s ASIL rating. &nbsp;</p>

<p>[As recorded in 4.5 above. The hardware must meet the most conservative target : either from ISO26262 Table 5, or as allocated to this hardware element of the Item by the customer].</p>

<p>&nbsp;

  - [ ] Is it shown that for each safety goal, the product hardware meets the Probabilistic Metric for Random Hardware Failures (PHMF) target&nbsp; of ISO26262-5 (9.4.2.1) appropriate for the product&rsquo;s ASIL rating. &nbsp;</p>

<p>[As recorded in 4.5 above. The hardware must meet the most conservative target : either from ISO 26262 Table 6, or as allocated to this hardware element of the Item by the customer].</p>

<p>Table 6:</p>

<p>ASIL B, C= 100 FIT; ASIL D=10 FIT</p>

<p>&nbsp;

- [ ] Dependent Failures Analysis-specific

  - [ ] Are systematic and adequate techniques used to determine the potential for dependent failures?</p>

<p>Expected : a defined process was followed as planned

  - [ ] Have all requirements for independence, ASIL decompositions, co-existence of elements with different ASILs, and requirements for non-interference been identified and considered systematically for potential dependent failures ?</p>

<p>&nbsp;

  - [ ] Has each element with independence requirements been considered in the analysis ?</p>

<p>&nbsp;

  - [ ] Are potential dependent-failure initiators (DFIs) and coupling factors identified by using defined criteria&nbsp; (checklist for HW, SW, Systems, including communications)</p>

<p>&nbsp;

  - [ ] Have operating modes and operating scenarios been considered&nbsp;?</p>

<p>&nbsp;

- [ ] Safety Impact Analysis-specific Element scope

  - [ ] Does the impact analysis record the project (change) type ?</p>

<p>Is it clear if the analysis is carried out at the Item or element level?&nbsp; Reused as a Safety Element Out of Context&nbsp;?</p>

<p>Expected : complete the relevant sections in template header</p>

<p>Expected : if the analysis is at Item level (unusual) &ndash; review compliance with 6.4.3.2, if at element level, review compliance with 6.4.4</p>

<p>&nbsp;

  - [ ] Does the impact analysis identify all changes&nbsp; to design, to implementation, and to environment ?</p>

<p>Expected&nbsp;, for both Item and Element analysis.</p>

<p>Expected: implementation changes in hardware identified to the block or HW part level; in SW, to model and source code level.&nbsp; (Necessary to check dependencies, and to check adequacy of testing)</p>

<p>&nbsp;

  - [ ] Was the impact analysis carried out prior to the changes being implemented ?</p>

<p>&nbsp;

  - [ ] Does the analysis identify expected and potential impacts on safety-related elements ?</p>

<p>&nbsp;

  - [ ] Was an adequate safety plan&nbsp;created as an output of the analysis ?</p>

<p>&nbsp;

  - [ ] Is each recommended action in the safety impact analysis template planned&nbsp;?</p>

<p>&nbsp;

  - [ ] Have assumptions about the affected elements been identified and revalidated in light of the planned changes ?</p>

<p>&nbsp;

  - [ ] Has the result plan been tailored&nbsp;appropriately to the ASIL, with justification?</p>

<p>&nbsp;

  - [ ] If specific techniques or methods have been tailored in the resultant plan, is this clearly documented ?</p>

<p>&nbsp;

  - [ ] If potential safety impact has been identified, has further detailed analysis been planned (for example, DRBFM)?</p>

<p>&nbsp;

  - [ ] Has adequate independence of review been planned and resourced ?</p>

<p>&nbsp;

  - [ ] Does the impact analysis evaluate&nbsp;how each allocated safety requirement is complied with, after the planned changes (or re-use) ?</p>

<p>&nbsp;

  - [ ] Does the modularity of the software architecture deliberately designed to limit the impact of the changes ?</p>

<p>&nbsp;

  - [ ] Has appropriate regression testing been planned, covering all potential areas of safety impact identified in the analysis ?</p>

<p>&nbsp;

  - [ ] Does the planning resulting from impact analysis include an update of all dependent documentation&nbsp;?</p>

<p>Is that documentation sufficient to permit safe integration and production of the product ?</p>

<p>&nbsp;

  - [ ] Have each of the following been planned and resourced&nbsp; :</p>

<p>- Confirmation and verification reviews of all required WPs<br />
- Safety case update (both argument and evidence) and review<br />
- Safety audit (unless tailored out)<br />
- Safety assessment</p>

<p>&nbsp;
