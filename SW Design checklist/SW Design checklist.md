# Task List for SW Design checklist - v1.0

- [ ] <strong>Generic questions : Formalities</strong>

  - [ ] Are all documents needed for this review available? (i.e. the document itself, any recommended additional documents and criteria etc.)&nbsp; are these controlled per configuration management (documents must be identifiable e.g. versioned, labeled, etc. )?

  - [ ] Is the document written in its proper template?<br />
(if not: Is the reason known?)

  - [ ] Does the document has its proper ID, title, version history (version nr. and date), author(s), status?

- [ ] <strong>Generic questions : Completeness (generic)</strong>

  - [ ] Are all areas within the module design provided with intended contents?

  - [ ] Are there any unresolved TBD&#39;s or TO DO&#39;s?

  - [ ] Is the fault behaviour described completely and correctly (error condition)? Is described which faults are detected including their fault conditions?&nbsp;

  - [ ] Is there a description of the fault conditions including worst case calculation (e.g. of the HW team)? Are the monitoring thresholds documented in Artisan?&nbsp;

  - [ ] Are all SW interfaces described (internal and external) sufficient?<br />
Name, type, value ranges, information protocols, ASIL, verification criteria

  - [ ] Does the SW design address all issues from the SW requirements (all software requirements were assigned corresponding software architecture elements)?<br />
Is traceability and consistency including verification criteria between<br />
1. SW requirements and the SW architecture<br />
2. SW architecture and module design<br />
given¿¿?

  - [ ] Were objectives on resource usage for all software components determined and documented (ROM, RAM, EEPROM, CPU load, etc.)?

  - [ ] Were verification criteria for each component, taking into account their dynamic behavior, their interfaces and their use of resources based on the software design defined (e.g. reaction times, defined parameter combinations, HIS metrics)?

- [ ] <strong>Generic questions : Clarity</strong>

  - [ ] Is the module design sufficiently clear and understandable by all intended readers (formulations, diagrams...)?

  - [ ] Were the Task Manager, the interrupt management, state machines and other dynamic behavior in a suitable representation (models, graphs, tables, etc.) visualized?

  - [ ] Are all abbreviations and technical terms defined and clear?

  - [ ] Are the statements sufficiently concise stated (i.e. no unnecessary complicated and long sentences)?

  - [ ] Are all functions and macros of the module in the SW-module-design described correctly and understandable?&nbsp;

  - [ ] Are all used global variables in the SW-module-design described correctly and understandable (description, conversion formula, value range, init value)?

- [ ] <strong>Generic questions : Correctness</strong>

  - [ ] Is the module design free of obviously wrong or superseded statements?

  - [ ] Are the UML diagrams that are eventually available correct?&nbsp;

  - [ ] Do the design elements match the naming conventions?

- [ ] <strong>Generic questions : Consistency</strong>

  - [ ] Is the module design free of any ambiguous or inconsistent statements?

  - [ ] Is the terminology used consistently? (i.e. the same item is always referred with the same term)?

  - [ ] Is the content&#39;s consistency given between a superordinate document (e.g. SAD or SRS) and module design?&nbsp;

- [ ] <strong>Completeness (detailed aspects) : Scheduling, Interrupts</strong>

  - [ ] Has the Scheduling, including cyclic tasks, event driven tasks and interrupts been documented?

  - [ ] Have interrupts been defined? Have interrupt triggers been identified?

  - [ ] Have Priorities of interrupts been set? Have interruptible Interrupts been identified?

  - [ ] Has the brown out situation been considered?

  - [ ] Is it ensured that all tasks are finished before power off?

  - [ ] Is reaction to wake up signals during Power Off ensured?

  - [ ] Is it ensured that no illegal opcodes are used?

  - [ ] Has the case of loss of interrupt events been considered, e.g. if interrupts are disabled?

  - [ ] Do any of the ISRs call another software module? If so, is it ensured that the software module is re-entrant (no static variables have been used)?

  - [ ] Has the maximum runtime for all interrupt procedures been defined?&nbsp;

  - [ ] Is there shared data (for example flags) between interrupts and task? If so, is this shared data necessary or could it be avoided? If it is neccesary, is it protected against concurrent access? Are there any critical windows where the data could become inconsistent?

- [ ] <strong>Completeness (detailed aspects) : NVM</strong>

  - [ ] Has a protection method against data change during write cycles been defined?

  - [ ] If the NVM has a limited number of write cycles (s. NVM Data sheet), has a prevention mechanism against exceeding the maximum number been defined (e.g. avoiding unneeded write cycles)

  - [ ] Has a method for detecting a defect NVM cell during writing and during reading been defined? Has a mechanism for preventing loss of data been defined (e.g. Backup)?

  - [ ] Has a mechanism been defined for detecting power failure?

  - [ ] Has a mechanism been defined for detecting transmission failure (e.g. multiple reading)?

  - [ ] Has a protection mechanism against reentrancy been defined?

  - [ ] If the NVM is of retention type, have<br />
- prevention mechanisms (e.g. refresh cycles)<br />
- detection mechanisms (e.g. checksum)<br />
- reaction mechanisms (write data new)<br />
been defined against corrupted-data?

  - [ ] Have the RB standard NVM handler been used?

  - [ ] Has a procedure on a page change been defined ?

  - [ ] Has all data with corresponding properties (backup, CRC, number of write cycles) been listed?

- [ ] <strong>Completeness (detailed aspects) : State Machines</strong>

  - [ ] Are there any hidden states in a state machine (e.g. flags) that are used to determine the behaviour of the state machine? They must be avoided.

  - [ ] Is ensured that&nbsp; any edge detection will be done by comparing the current value to some older value from the previous cycle?

  - [ ] Is the state of the state machine modified in several functions? In particular, are there any subfunctions that modify the state? Is in this case the consistency of state given?

- [ ] <strong>Completeness (detailed aspects) : ECU State Machine</strong>

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

- [ ] <strong>Completeness (detailed aspects) : Diagnosis</strong>

  - [ ] Is there any output fault detection?<br />
Describe the retry strategy in case of output faults.

  - [ ] Is the following documented:<br />
- What is the debounce time of DTC logging within this voltage range?<br />
- What is the debounce time of analogue inputs?

  - [ ] Is it documented, when Continuous DTC logging is enabled and disabled?

  - [ ] Are all conditions listed that could cause a defective ECU DTC to be set? (e.g. NVRAM, ROM, Relais)

  - [ ] Is it documented, how long it takes to set a defective ECU DTC for each of the conditions listed above?

  - [ ] Is there any output fault detection?<br />
Describe the retry strategy in case of output faults

- [ ] <strong>Completeness (detailed aspects) : IO/DIO</strong>

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

- [ ] <strong>Completeness (detailed aspects) : Miscellaneous</strong>

  - [ ] Are the steps for integrating the individual software units hierarchically into software components until the embedded software is fully integrated are described? Is the following considered:<br />
a) the functional dependencies that are relevant for software integration; and<br />
b) the dependencies between the software integration and the hardware-software integration?

  - [ ] WHILE loops: risk to use external termination criteria, which cannot be reached in some circumstances.<br />
<em>Recommendation:</em> use timeout to avoid deadlock situations.<br />
<em>Example: </em>AD Converter does not generate &#39;Conversion complete flag&#39;

  - [ ] Does the software architectural design exhibit<br />
the following properties:<br />
a) modularity;<br />
b) encapsulation; and<br />
c) simplicity.<br />
Are the principles from ISO 26262-6:2011 Table 3 used for the architectural design?

  - [ ] Are the necessary software safety mechanisms for error handling at the software architectural level specified, based on the results of the safety analysis?<br />
Are the appropriate mechanisms used as recommended in ISO 26262-6:2011 Table 5?

  - [ ] Is the software unit design described by the notations recommended in ISO 26262-6:2011 Table 7 to ensure that the software unit design captures the information necessary to allow the subsequent development activities to be performed correctly and effectively?

  - [ ] Are the design principles for software unit design and implementation at the source code level as listed in<br />
ISO 26262-6:2011 Table 8 applied to achieve the following properties:<br />
a) correct order of execution of subprograms and functions within the software units, based on the software<br />
architectural design;<br />
b) consistency of the interfaces between the software units;<br />
c) correctness of data flow and control flow between and within the software units;<br />
d) simplicity;<br />
e) readability and comprehensibility;<br />
f) robustness;<br />
g) suitability for software modification; and<br />
h) testability.

  - [ ] Is the software architectural design described with appropriate levels of abstraction to ensure that the software architectural design captures the information necessary to allow the<br />
subsequent development activities to be performed correctly and effectively?<br />
Are the appropriate notations (informal, semi formal or formal) used to describe the architecture as is suggested in ISO 26262-6:2011 Table 2?

  - [ ] Are appropriate mechanisms for error detection specified at the software architectural level, based on the results of the safety analysis.<br />
Are the recommended mechanisms in ISO26262-6:2011 Table 4 applied in the software architecture.

  - [ ] Are there any HW specific features used/enabled that could potentially inhibit/interfere with SW features? If so, have they been thoroughly analysed and reviewed with Bosch Software Architect experts and HW vendor Hardware Architects?

- [ ] <strong>Completeness (detailed aspects) : Sensor / Driver / ASIC</strong>

  - [ ] Are all initialisation values defined?

  - [ ] Is defined which Data has to be read or written and also their&nbsp; cycle time?

  - [ ] Is there timing relevant data while reading or writting are to be considered? Are these kept?

  - [ ] Do several Dirver / Sensor / ASICs use the same interface and is an access strategy constructed and documented?

  - [ ] Are possible monitoring borders defined, are described as well as a Worst Case interpretation are constructed?

  - [ ] Is there a strategy how to react if the data from the sensor / driver / ASIC is not correct detected in the microcontroller? Is therefor an error reaction defined?

  - [ ] Is a strategy defined if the sensor / driver / ASIC detect the data incorrect or does not accept the data? Is therefor an error reaction defined?

- [ ] <strong>Completeness (detailed aspects) : Configurable SW component</strong>

  - [ ] Are the configuration values within the specified range of the component?

  - [ ] Are the configuration values compatible (dependency) to each other?

- [ ] <strong>Completeness (detailed aspects) : SW component to be calibrated</strong></p>

<p>Are the calibration values within the specified range of the component?

- [ ] <strong>Completeness (detailed aspects) : OSS in case of usage of external OSS components</strong>

  - [ ] Are the used external OSS components under copyleft open source licences?

  - [ ] If SWD83 &quot;yes&quot;:<br />
Is the SW architecture designed to avoid inadvertent or unwanted &quot;copyleft effects&quot;?
