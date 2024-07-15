# Task List for Software Detailed Design Documentation Review Checklist - v2.0

- [ ] <strong>Formalities</strong>

  - [ ] Are all documents needed for this review available? (i.e. the document itself, any recommended additional documents and criteria etc.)&nbsp; are these controlled per configuration management (documents must be identifiable e.g. versioned, labeled, etc. )?

  - [ ] Is the document written in its proper template?<br />
(if not: Is the reason known?)

  - [ ] Does the document has its proper ID, title, version history (version nr. and date), author(s), status?

- [ ] <strong>Completeness (generic)</strong>

  - [ ] Is there a description of the fault conditions including worst case calculation (e.g. of the HW team)? Are the monitoring thresholds documented in Artisan?&nbsp;

  - [ ] Does the SW design address all issues from the SW requirements (all software requirements were assigned corresponding software architecture elements)?<br />
Is traceability and consistency including verification criteria between<br />
1. SW requirements and the SW architecture<br />
2. SW architecture and module design<br />
given¿¿?

  - [ ] Are all areas within the module design provided with intended contents?

  - [ ] Are there any unresolved TBD&#39;s or TO DO&#39;s?

  - [ ] Are all SW interfaces described (internal and external) sufficient?<br />
Name, type, value ranges, information protocols, ASIL, verification criteria

- [ ] <strong>Understandability</strong>

  - [ ] Is the module design sufficiently clear and understandable by all intended readers (formulations, diagrams...)?

  - [ ] Were the Task Manager, the interrupt management, state machines and other dynamic behavior in a suitable representation (models, graphs, tables, etc.) visualized?

  - [ ] Are all abbreviations and technical terms defined and clear?

  - [ ] Are the statements sufficiently concise stated (i.e. no unnecessary complicated and long sentences)?

  - [ ] Are all functions and macros of the module in the SW-module-design described correctly and understandable?&nbsp;

  - [ ] Are all used global variables in the SW-module-design described correctly and understandable (description, conversion formula, value range, init value)?

- [ ] <strong>Correctness</strong>

  - [ ] Is the module design free of obviously wrong or superseded statements?

  - [ ] Are the UML diagrams that are eventually available correct?&nbsp;

  - [ ] Do the design elements match the naming conventions?

- [ ] <strong>Consistency</strong>

  - [ ] Is the module design free of any ambiguous or inconsistent statements?

  - [ ] Is the terminology used consistently? (i.e. the same item is always referred with the same term)?

- [ ] <strong>Scheduling, Interrupts</strong>

  - [ ] Has the Scheduling, including cyclic tasks, event driven tasks and interrupts been documented?

  - [ ] Have interrupts been defined? Have interrupt triggers been identified?

  - [ ] Have Priorities of interrupts been set? Have interruptible Interrupts been identified?

  - [ ] Has the brown out situation been considered?

  - [ ] Is it ensured that all tasks are finished before power off?

  - [ ] Is reaction to wake up signals during Power Off ensured?

  - [ ] Has the case of loss of interrupt events been considered, e.g. if interrupts are disabled?

  - [ ] Do any of the ISRs call another software module? If so, is it ensured that the software module is re-entrant (no static variables have been used)?

  - [ ] Has the maximum runtime for all interrupt procedures been defined?&nbsp;

- [ ] <strong>NVM</strong>

  - [ ] Has a protection method against data change during write cycles been defined?

  - [ ] Has a mechanism been defined for detecting power failure?

  - [ ] Has a mechanism been defined for detecting transmission failure (e.g. multiple reading)?

  - [ ] Has a protection mechanism against reentrancy been defined?

  - [ ] Have the RB standard NVM handler been used?

  - [ ] Has a procedure on a page change been defined ?

  - [ ] Has all data with corresponding properties (backup, CRC, number of write cycles) been listed?

  - [ ] If the NVM is of retention type, have<br />
- prevention mechanisms (e.g. refresh cycles)<br />
- detection mechanisms (e.g. checksum)<br />
- reaction mechanisms (write data new)<br />
been defined against corrupted-data?

  - [ ] If the NVM has a limited number of write cycles (s. NVM Data sheet), has a prevention mechanism against exceeding the maximum number been defined (e.g. avoiding unneeded write cycles)

  - [ ] Has a method for detecting a defect NVM cell during writing and during reading been defined? Has a mechanism for preventing loss of data been defined (e.g. Backup)?

- [ ] <strong>State Machines</strong>

  - [ ] Are there any hidden states in a state machine (e.g. flags) that are used to determine the behaviour of the state machine? They must be avoided.

  - [ ] Is ensured that&nbsp; any edge detection will be done by comparing the current value to some older value from the previous cycle?

  - [ ] Is the state of the state machine modified in several functions? In particular, are there any subfunctions that modify the state? Is in this case the consistency of state given?

- [ ] <strong>ECU State Machine</strong>

  - [ ] Have the major operating modes of the software and the ECU(e.g. Boot, Sleep, Active, Diagnostic, Low/High Voltage, Fault) been defined and described?<br />
Are the conditions/actions for each transition to/from each of these major modes specified?

  - [ ] Is it ensured that transitions, especially critical ones (e.g. from application to test mode) only can occur as defined?

  - [ ] Is it ensured that all functions are orderly finished and data is written into EEPROM before sleep mode?

  - [ ] Has Memory inititalisation (for RAM, ROM and NVM) after warm and cold boot been defined and described?

  - [ ] Has the behaviour during reset (software reset, watchdog reset) been defined and described?<br />
- Memory initialisation<br />
- Software controlled power supply (e.g. Co- and Main processor)

  - [ ] Can data be lost after voltage drop or watchdog reset?&nbsp;&nbsp;

  - [ ] Has a data integrity verification method for RAM and EEPROM been defined and described (e.g. checksum)?

  - [ ] In case of corrupted data after reset (warm boot) , has a Recovery method been defined?

  - [ ] Is it ensured that only relevant and important Wake up interrupts are activated during start up?

  - [ ] Are the interrupts monitored during sleep mode?<br />
Is it ensured that relevant interrupts are active (monitored) during sleep Mode, and the rest has been disabled before changing?

- [ ] <strong>Diagnosis</strong>

  - [ ] Is there any output fault detection?<br />
Describe the retry strategy in case of output faults.

  - [ ] Is the following documented:<br />
- What is the debounce time of DTC logging within this voltage range?<br />
- What is the debounce time of analogue inputs?

  - [ ] Is it documented, when Continuous DTC logging is enabled and disabled?</p>

<p>&nbsp;

  - [ ] Are all conditions listed that could cause a defective ECU DTC to be set? (e.g. NVRAM, ROM, Relais)

  - [ ] Is it documented, how long it takes to set a defective ECU DTC for each of the conditions listed above?

  - [ ] Is there any output fault detection?<br />
Describe the retry strategy in case of output faults

- [ ] <strong>IO/DIO</strong>

  - [ ] Has the input operation i.e. de-bounce strategy, analog data processing been specified?

  - [ ] Has the voltage mapping technique for battery voltage (voltage monitor) been specified (input filters between the measured battery voltage and the A/D-channel being sampled must be matched)?

  - [ ] Based on worst-case analysis, at what battery voltage level can digital or analog inputs be misread.<br />
How do you guarantee that the power supply is still on before starting a new I/O?<br />
(Any external device shall be accessed only while its power supply is stable)

  - [ ] Which inputs are capable of &ldquo;timing-out&rdquo;? How were the values of time-outs determined?<br />
(e.g.: max. Time-out to recognize broken Hall-Sensor)

  - [ ] For all off-micro resources that use multi-bit communication (spi, sci, uart&hellip;), describe how data integrity is preserved.

  - [ ] Are all module outputs performed at the same time (e.g. cyclic) or are the outputs performed at the time the dataflow changes (e.g. ISR)?

  - [ ] How often are registers cyclically refreshed during normal operation?<br />
Is the initial value consistent with the refreshed value?

  - [ ] Are you foreseeing a periodically refresh for the control registers of the critically output ports?<br />
Which for?&nbsp;&nbsp; (Example, power supply, critical actuator, etc.)

- [ ] <strong>Miscellaneous</strong>

  - [ ] Update in ISO_26262-6:2018 - Table 3<br />
1a Appropriate hierarchical structure of the software components<br />
1b Restricted size and complexity of software components<br />
1c Restricted size of interfaces (&quot;++&quot; from ASILD)<br />
1d Strong cohesion within each software component (&quot;++&quot; from ASILB)<br />
1e Loose coupling between software components (&quot;++&quot; from ASILB)<br />
1f Appropriate scheduling properties<br />
1g Restricted use of interrupts (&quot;++&quot; from ASILD)<br />
1h Appropriate spatial isolation of the software components (&quot;++&quot; from ASILD)<br />
1i Appropriate management of shared resources

  - [ ] Update in ISO_26262-6:2018 - Table 5<br />
1a Natural language<br />
1b Informal notations&nbsp; (&quot;++&quot; till ASILB)<br />
1c Semi-formal notations (&quot;++&quot; from ASILC)<br />
1d Formal notations

  - [ ] Update in ISO_26262-6:2018 - Table 6<br />
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

  - [ ] Update in ISO_26262-6:2018 - Table 2<br />
1a Natural language<br />
1b Informal notations&nbsp; (&quot;++&quot; till ASILB)<br />
1c Semi-formal notations (&quot;++&quot; from ASILC)<br />
1d Formal notations

- [ ] <strong>Sensor / Driver / ASIC</strong>

  - [ ] Are all initialisation values defined?

  - [ ] Is defined which Data has to be read or written and also their&nbsp; cycle time?

  - [ ] Is there timing relevant data while reading or writting are to be considered? Are these kept?

  - [ ] Do several Dirver / Sensor / ASICs use the same interface and is an access strategy constructed and documented?

  - [ ] Are possible monitoring borders defined, are described as well as a Worst Case interpretation are constructed?

  - [ ] Is there a strategy how to react if the data from the sensor / driver / ASIC is not correct detected in the microcontroller? Is therefor an error reaction defined?

  - [ ] Is a strategy defined if the sensor / driver / ASIC detect the data incorrect or does not accept the data? Is therefor an error reaction defined?

- [ ] <strong>Configurable SW component</strong>

  - [ ] Are the configuration values within the specified range of the component?

  - [ ] Are the configuration values compatible (dependency) to each other?

- [ ] <strong>SW component to be calibrated</strong></p>

<p>Are the calibration values within the specified range of the component?

- [ ] <strong>OSS in case of usage of external OSS components</strong>

  - [ ] Are the used external OSS components under copyleft open source licences?

  - [ ] If SWD83 &quot;yes&quot;:<br />
Is the SW architecture designed to avoid inadvertent or unwanted &quot;copyleft effects&quot;?

- [ ] <strong>Pitfalls</strong>

  - [ ] In case of integration of externally supplied software, do all development partners use the same development environment, especially the same compiler version?

  - [ ] Especially with respect to the initialization routine, has the worst-case (i.e. shortest) watchdog trigger time been taken into account?

  - [ ] Regarding <strong>EEPROM write-accesses</strong>: is it ensured for <u>all</u> EEPROM cells that the (hardware dependent) maximal number of write cycles will not be exceeded?&nbsp;

  - [ ] <strong>Programming of flash: </strong><br />
Have the following aspects been considered?<br />
- Worst case cycle time.<br />
&nbsp; (Cycle time depends e.g. on the environmental<br />
&nbsp; temperature and may increase with rising number<br />
&nbsp; of write-/erase-cycles)<br />
- Maximum permissible number of programming<br />
&nbsp; cycles, granted by hardware.<br />
&nbsp; Behaviour of the ECU if this number is exceeded<br />
&nbsp; (robustness!).

  - [ ] Are <strong>open port pins</strong>, i.e.port pins which are not connected to a defined electric potential - either on chip or on the PCB -,&nbsp; configured as output pins or configured as inputs with a defined state (pull-up or pull-down)?<br />
Is this also assured for pins which exist on the die but are not bonded out to physical package pins?

  - [ ] <strong>In cases where resources (hardware, variables, functions) are used in several partitions of the software, which can interrupt each other (e.g. interrupts, preemptive systems):</strong><br />
Is it ensured that no conflicts can arise from &quot;simultaneous&quot; usage of these resources or are the resources excluded from simultaneous usage?<br />
<br />
<br />
Example1: A function is called within the normal program sequence as well as within an interrupt routine.<br />
AlternativeA: The routine is to be implemented as re-entrant.<br />
AlternativeB: During the execution of this routine in the context of the normal program the corresponding interrupt is inhibited.<br />
<br />
Example2: The instruction &quot;variable_x = ~variable_x&quot; results in a sequence of assembler instructions; a higher priority task which becomes active during this sequence and is using the same variable, may destroy its content.<br />
Alternatives:<br />
- usage of a resource mechanism which is dependent from the used operating system,<br />
- configuration of the task as non-preemptive,<br />
- assignment of same priority for both tasks, ...

  - [ ] Have any sporadic failures or other abnormalities occured during&nbsp; development and have these been followed up?

  - [ ] <strong>At usage of (EEPROM-) variant encoding:</strong><br />
a) Is it ensured that onboard diagnostic functions are only executed for HW- and SW-elements of the selected variant?<br />
b) Is it alternatively to a) ensured that only defect entries, that are relevant for this variant, are transfered to the diagnostics tester?<br />
c) Is it ensured that the complete defect memory can be deleted by the diagnostics tester, i.e. including the entries which are not relevant for the selected variant?

  - [ ] <strong>At carry-over of existing, proven SW-modules check the following:</strong><br />
- Have SW interfaces for this module changed?<br />
- Has the SW environment with respect to these interfaces changed?<br />
- Are new functions (which were not in the SW, the module was taken over from) depending on the carry-over module?<br />
- Can the module carried-over have any influence on requirements specific for the new SW ?<br />
- Has the author of the original module been asked about integration issues which may arise at the integration in the new SW ?<br />
- Is the system functionality confirmed with the specified worstcase parameters of the components used (e.g. test with boundary patterns, worst case calculation)?<br />
- Has an update of the Impact Analysis or Focus Matrix been performed on the module used?<br />
- Is the maturity level of the module to be implemented known? Does it correspond to series status and is there a corresponding release? If not, what additional hedging needs to be done?<br />
- Has the integration of the modules used been subject to an expert review (CoC)?

  - [ ] <strong>For systems which allow simultaneous access by the main core and other components (like co-processors):</strong><br />
Access to ports registers on the hardware level normally is neither atomic (non-interruptible) nor bit-oriented. All port bits will be written on every access.<br />
Such interleaved read-modify-write cycles can lead to unpredicable results on dual core systems.<br />
Countermeasures such as the usage of semaphores or RAM buffers have to be employed.

  - [ ] <strong>At validity checks of RAM areas, especially after supply voltage drops</strong>, have the following aspects been considered:<br />
- pattern length at least 32 bit<br />
- asymmetrical pattern<br />
- ideally CRC checksum<br />
&nbsp; (standard solution available at CC/ESB1<br />
&nbsp; J. Brachert)<br />
<br />
Apart from this, CC/ESB1 as &quot;design support&quot; offers support for all problems concerning data security, verification of datasets, probabilities of data loss and corresaponding measures.<br />
&nbsp;<br />
&nbsp;&nbsp;

  - [ ] <strong>If test routines have been implemented for development purposes:</strong><br />
Is it ensured that these test routines have been removed and/or deactivated for series releases?

- [ ] <strong>Business Unit specific questions</strong>

  - [ ] Is the architecture/unit design complete as per Standards? (e.g. Names Conventions, Design guidelines)&nbsp;

  - [ ] Core deployement concept considered and data consistency is ensured.
