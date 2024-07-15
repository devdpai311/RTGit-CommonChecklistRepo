# Task List for HARA checklist - v2.0

- [ ] Schedule and Status

  - [ ] Hazard Analysis completed and review concluded within appropriate timeframe?

  - [ ] Based on correct (most recent) version of template?

  - [ ] Front page information completed?

  - [ ] Stored under configuration management, per Project CM plan, in location per Department process?

  - [ ] Has Hazard Analysis review baseline been completed?

- [ ] Change Status

  - [ ] Is the Hazard Analysis up-to-date with requirements changes to project ?

  - [ ] Have changes identified through Impact Analysis resulted in Hazard Analysis update?

  - [ ] Are all changes to the Hazard Analysis reflected into FMEA, FTA and, if needed, DRBFM?

  - [ ] Are all Open Issues either closed or traceably managed to closure?

  - [ ] If the Hazard Analysis is updated as a result of changes, has the security team been informed ?<br />
Expected: Changes to Hazard Analysis may trigger a review of Threat Analysis (TARA).

- [ ] Requirement Status

  - [ ] Are requirements (in the Item definition) completely available?

  - [ ] All assumptions documented and transferred to management system?<br />
Expected: at the time of review of the Hazard Analysis, there should be no open assumptions, comments or &ldquo;TBA&rdquo;s in the hazard analysis documents. These should be formally managed to closure as safety items in the requirements tracking or other change-management or OPL system

  - [ ] Are the item scope, system boundary, interfaces and dependencies clearly identified in the Item definition?

  - [ ] Has the customer provided all required information, including safety goals, ASIL ratings, and the ASIL ratings for all signals at the interface?

  - [ ] Have the vehicle operating scenarios been defined and agreed?

  - [ ] Has the vehicle manufacturer supplied sufficient information to allow analysis of failure consequence (including &ldquo;downstream&rdquo; systems)?<br />
If not, has the OEM been informed clearly of the scope and limits of RB Hazard Analysis?<br />
Expected : this would be recorded in the TCD, but must also be advised early to the OEM.

- [ ] Methodology

  - [ ] Are operational situations clearly described and not confused with failures? Are they consistent with the item definition?<br />
Is the set of operational scenarios sufficently complete, and relevant?</p>

<p>Expected : The operational scenarios should include at least those recorded in ISO 26262, in SAE J2980, those included by the customer (if known) and those relevant from BASILICA.

  - [ ] Are hazards described in terms of vehicle-level behaviour (and not product-level) ?

  - [ ] Are the hazardous events clearly and correctly described ?<br />
Are the hazardous events sufficiently complete with respect to the operational scenarios ?<br />
Is the selection of hazardous events appropriate with respect to the operational scenarios?

  - [ ] All required parameters completed (S,E,C, safety goal, FTTI, and ASIL) for all hazards?

  - [ ] Are all parameters justified where required?</p>

<p>&nbsp;

  - [ ] Are the ASILs and QM ratings of the hazardous events correctly derived from the S, E and C parameters ?

  - [ ] Is a safe state specified (and consistent with other analyses) for each hazard where a safe state is feasible?

  - [ ] Are parameters, ASIL and QM ratings consistent with those in the AK-L list, Department guidelines, BASILICA, XC-AN HARA repository?<br />
Are parameters and ASILs consistent with those of the customer?</p>

<p><u><a href="https://sites.inside-share.bosch.com/sites/050195/Documents/Forms/AllItems.aspx?RootFolder=%2Fsites%2F050195%2FDocuments%2F02%5Fpublished&amp;FolderCTID=0x0120008C31339FB3B37C469D81B06673093FB8&amp;View=%7B921407E6%2D3885%2D4372%2DBC2B%2D111A48285B7B%7D" target="_blank">[LINK] BASILICA V6.2</a></u>

  - [ ] If Bosch is responsible for the creation of (any part of) the Hazard Analysis and Risk Assessment, including for platform projects, has the Hazard Analysis been provided to the customer for review and approval ?

  - [ ] Was Department data updated to include Exposure estimates if unique scenarios were analysed?</p>

<p><u><a href="https://sites.inside-share.bosch.com/sites/050195/Documents/Forms/AllItems.aspx?RootFolder=%2Fsites%2F050195%2FDocuments%2F02%5Fpublished&amp;FolderCTID=0x0120008C31339FB3B37C469D81B06673093FB8&amp;View=%7B921407E6%2D3885%2D4372%2DBC2B%2D111A48285B7B%7D" target="_blank">[LINK] BASILICA V6.2</a></u>

  - [ ] Is the concept of parameter refinement used, consistent with the AK-L reference list ?</p>

<p><u><a href="https://inside-docupedia.bosch.com/confluence/display/ATW/Hazard+Analysis+and+Risk+Assessment" target="_blank">[LINK] Functional Safety Wiki - HARA</a></u>

  - [ ] Is foreseeable misuse (foreseeable conditions of use) included in the analysis ?

  - [ ] Does the exposure analysis consider only the probability of the road situation, and not the probability of the fault itself ?

  - [ ] Does the analysis avoid inappropriate &ldquo;credit&rdquo; taken from existing or intended internal safety systems ?

  - [ ] Has hazard granularity been chosen appropriately ?

  - [ ] Does the Hazard Analysis avoid specifying (product-related) causes of hazards in the analysis ?</p>

<p>[Note: it is appropriate to record possible causes as notes for further analysis].

  - [ ] Are the techniques used to determine the hazards systematic and adequate ?&nbsp;

  - [ ] Have any hazards outside the scope of ISO 26262 (e.g. mechanical, or non-functional) been clearly notified to the development team and/or the customer, and added to a respository to ensure they are not &ldquo;lost&rdquo; ?

  - [ ] Are the Hazard Analysis ratings appropriately conservative (that is, when in doubt, the higher rating is selected)?</p>

<p>Commented where necessary ?</p>

<p>&nbsp;

  - [ ] Is a rationale given for each case where Exposure has been rated E0, Severity S0, or controllability C0 ?<br />
Is the E0, S0, C0 rating justified and convincing ?<br />
Is the resultant rating of &quot;no ASIL&quot; correct ?

  - [ ] Do the specified safety goals adequately and verifiably cover the identified hazardous events ?

  - [ ] Have Safety Goals (with accompanying Safe State and FTT information) been completely, correctly and traceably transferred into the requirements repository (e.g. DOORS)?

  - [ ] Have Safety Goals been managed consistently as requirements (unique ID, reviewed, traceable etc) ?

  - [ ] Are safety goals and safe states internally consistent ?

  - [ ] Are the comments internally consistent ?</p>

<p>Lessons leaned: The AK-L list specifies a number of contradictory safe states for the same function (in some instances the safe state is &ldquo;off&rdquo;, whilst in other cases the safe state (for a different failure of the same function) is &ldquo;on&rdquo;).

  - [ ] If the Hazard Analysis has been carried out on a safety element out of context (SEooC), are the assumed requirements accessible and clear ?</p>

<p>Lesson Learned: Review of some Hazard Analyses has shown that copy-and-paste errors are common.

  - [ ] Has the safety team considered security vulnerabilities where appropriate ?

  - [ ] Has the Hazard Analysis team requested information from the project security team about identified or updated hazards ?

  - [ ] If an argument is used that several unlikely scenarios combine to result in an Exposure lower than E1, and a QM rating is subsequently claimed for a hazardous event (S3, C3), is this clearly documented with convincing rationale (equivalent to that expected for E0 ?)

  - [ ] When a Hazard Analysis has been created for a platform, or other SEooC, and the SEooC is applied to (integrated into) a specific vehicle, variant or context, have all assumptions in the HARA been explicitly and traceably reviewed for suitability for the target vehicle, including ; the conditions and context of use, relevant external interfaces, intended functionality, validity of assumed requirements, operating environments, assumptions from the Item Definition, and assumptions on the actions of users ?</p>

<p>&nbsp;

  - [ ] Are any Assumptions that are made during the HARA (including assumed actions of the driver or persons at risk, and assumptions regarding external measures) documented, transferred to the safety comcept if required, and validated ?
