# Assignment 00 — Student Answer Sheet

## Student Information

| Field | Student Response |
|---|---|
| Full name | `[Rutuja Falke]` |
| GitHub username | `[rutujafalke07]` |
| Class/college | `[BCA 3rd year SKC college]` |
| Submission date | `[10 Aug 2026]` |

---

## Section A — Industrial Automation Fundamentals (15 marks)

### Q1. What is industrial automation? Explain it in 3–5 sentences. (5 marks)

`[Industrial automation is the use of control systems, computers, robots, PLCs, and sensors to operate industrial processes with minimal human intervention. It helps control and monitor machines and production processes automatically. Industrial automation improves productivity, accuracy, safety, and efficiency. It is widely used in manufacturing, power plants, chemical industries, and other production systems.]`

### Q2. State any four reasons industries use automation. (4 marks)

1. `[Increased productivity – Automation enables faster production and higher output.]`
2. `[Improved quality – Automated systems provide consistent and accurate results.]`
3. `[Reduced labor cost – Machines can perform repetitive tasks with less human involvement.]`
4. `[Enhanced safety – Automation can handle dangerous or hazardous operations, reducing the risk of accidents.]`

### Q3. Give three examples of processes that can be automated using PLC and SCADA. (3 marks)

1. `[Water treatment and pumping – Controls water levels, pumps, and valves while monitoring the process.]`
2. `[Conveyor belt systems – Controls the starting, stopping, speed, and movement of materials]`
3. `[Industrial temperature control – Monitors and controls temperature in furnaces, boilers, or processing tanks]`

### Q4. Complete the automation sequence. (3 marks)


_Input/Sensor → PLC → Control/Decision → Output/Actuator → Process → SCADA Monitoring

Explain the meaning of each stage:

`[Input/Sensor – Detects information from the process, such as temperature, level, pressure, or object presence.
PLC (Programmable Logic Controller) – Receives the input signals and makes decisions according to the programmed logic.
Control/Decision – The PLC determines what action should be taken based on the input conditions.
Output/Actuator – Devices such as motors, valves, pumps, and relays perform the required action.
Process – The actual industrial operation takes place, such as moving a conveyor or filling a tank.
SCADA Monitoring – SCADA displays the process status, values, alarms, and system information to the operator.]`

---

## Section B — PLC Fundamentals and Working (25 marks)

### Q5. Expand PLC and explain why it is called an industrial computer. (5 marks)

`[A PLC is called an industrial computer because it can receive input signals from sensors, process them according to a programmed logic, and control output devices such as motors, valves, and pumps.

It is specially designed to work in industrial environments and can withstand dust, vibration, temperature changes, and electrical noise.

Example: In a conveyor system, the PLC receives signals from sensors and controls the motor to start or stop the conveyor automatically.]`

### Q6. Classify each device as a PLC input or PLC output. (5 marks)

| Device | Input or Output? |
|---|---|
| Push button | `[input]` |
| Proximity sensor | `[input]` |
| Motor contactor | `[input]` |
| Indicator lamp | `[output]` |
| Temperature sensor | `[output]` |

### Q7. Write the three main PLC working steps in the correct order. (6 marks)

1. `[Input Scan - The PLC reads the signals from all input devices such as sensors and switches.]`
2. `[Program Scan / Logic Execution - The PLC processes the inputs according to the user-programmed logic and makes decisions]`
3. `[Output Scan - The PLC updates the output devices such as motors, lamps, and valves based on the program results.]`

### Q8. What is a PLC scan cycle? Why must it repeat continuously? (5 marks)

`[A PLC scan cycle is the continuous process in which a PLC reads inputs, executes the control program, and updates outputs.

The main steps are:

1. Input Scan - Reads the status of sensors, switches, and other input devices.

2. Program Execution - Executes the programmed logic using the input information.

3. Output Scan - Sends the required signals to output devices such as motors, valves, and lamps.

4. Repeat - The PLC starts the cycle again continuously.]`

### Q9. Identify the PLC section responsible for each function. (4 marks)

| Function | PLC Section |
|---|---|
| Executes the user program | `[Answer]` |
| Stores the program and data | `[Answer]` |
| Reads field-device signals | `[Answer]` |
| Controls external devices | `[Answer]` |

---

## Section C — SCADA Fundamentals (20 marks)

### Q10. Expand SCADA and explain its purpose. (5 marks)

`[SCADA stands for Supervisory Control and Data Acquisition.

It is an industrial control system used to monitor, control, and collect data from machines and processes in real time.

Purpose of SCADA:

1. It monitors industrial processes and equipment.

2. It collects data from sensors and

a

PLCS.

3. It displays process information on computer screen (HMI).

4. It allows operators to control equipment remotely.

5. It provides alarms, data logging, and reports to improve safety and efficiency.]`

### Q11. State five important functions of a SCADA system. (5 marks)

1. `[Monitoring: Continuously monitors machines, equipment, and industrial processes in real time]`
2. `[Data Acquisition: Collects data from sensors, PLCs, and other field devices.]`
3. `[Supervisory Control: Allows operators to control and operate equipment remotely.]`
4. `[Alarm Management: Detects abnormal conditions and alerts operators through alarms.]`
5. `[Data Logging & Reporting: Stores process data and generates reports for analysis and decision-making.]`

### Q12. Why is SCADA described as the “eyes” of an automation system? (4 marks)

`[SCADA is called the "eyes" of an automation system because it allows operators to see and monitor the entire industrial process in real time.

1. It displays data collected from sensors and PLCs.

2. It shows machine and process conditions on a computer/HMI screen.

3. It provides alarms and warnings when abnormal conditions occur.

4. It helps operators monitor parameters such as temperature, pressure, speed, and level.

5. It enables operators to observe and supervise the process remotly]`

### Q13. Name four industries or services where SCADA can be used. (4 marks)

1. `[Power and electricity generation – Monitoring and controlling power plants and substations]`
2. `[Water and wastewater treatment – Monitoring water levels, pumps, and treatment processes.]`
3. `[Oil and gas industry – Monitoring pipelines, pressure, flow, and storage tanks.]`
4. `[Manufacturing industries – Monitoring and controlling production machines and processes]`

### Q14. What is the difference between monitoring and controlling? (2 marks)

`[Monitoring
Controlling
Monitoring means observing and collecting information about a process or machine.
Example: Checking the temperature of a machine.
Controlling means taking action to change or operate the process or machine.
Example: Turning a cooling fan ON/OFF to control the temperature.]`

---

## Section D — PLC, HMI and SCADA Relationship (15 marks)

### Q15. Complete the comparison table. (9 marks)

| System | Main purpose | Typical user/location | Example task |
|---|---|---|---|
| PLC | `[Controls machines

and industrial process 

Typical u location

Control plc [ control machine and industrial process]` | `[control panel / machine area]` | `[turning a model On/ off]` |
| HMI | `[Display process information and allow operator interaction]` | `[operator station/ control room ]` | `[Displaying temperature and motor status ]` |
| SCADA | `[supervises monotors and collect Data from a entire process]` | `[control room/ central monitoring station]` | `[monitoring multiple machines and generating alarms/report]` |

### Q16. Explain how information travels from a field sensor to a SCADA screen. (6 marks)

`[Freid Sensor → PLC/RTU
Communication Network → SCADA
Server → HMI/SCADA Software Operator Screen
1. Field Sensor: The sensor measures a physical quantity such as temperature, pressure, level, or flow.
2. PLC/RTU: The sensor sends its signal to a PLC or RTU, which reads and processes the data.
3. Communication Network: The PLC/ RTU sends the processed data through a communication network.
4. SCADA Server: The SCADA system receives and stores the data for monitoring and analysis.
5.
SCADA Software/HMI: The software converts the data into readable values, graphs, trends, and alarms.
6. SCADA Screen: The information is displayed on the operator's screen, allowing the operator to monitor the process and take control]`

---

## Section E — Industrial Application Challenge (15 marks)

### Scenario: Automatic Water Tank

A tank must fill automatically. A low-level sensor detects when water is low, and a high-level sensor detects when the tank is full. A pump supplies water. The operator should see the tank and pump status on a monitoring screen.

### Q17. Identify the PLC inputs and output. (3 marks)

- Inputs: `[PLC]`
- Output: `[Sensor/Push button → PLC → Motor/Lamp/Valve]`

### Q18. Write the required control behaviour in plain language. (4 marks)

`[When the start button is pressed, the motor should turn ON.

When the stop button is pressed, the motor should turn OFF.

If a fault or emergency condition occurs, the motor should stop immediately.

The motor should remain OFF until the start command is given again.]`

### Q19. State four items that should be visible on the SCADA/HMI screen. (4 marks)

1. `[Process values – such as temperature, pressure, level, or flow.]`
2. `[Equipment status – such as motor ON/OFF or valve open/closed.]`
3. `[Alarms and warnings – to indicate faults or abnormal conditions]`
4. `[Control buttons – such as Start, Stop, Open, and Close.]`

### Q20. Suggest one alarm and one value/event that should be recorded. (4 marks)

- Alarm: `[High-temperature alarm when the temperature exceeds the safe limit.]`
- Recorded value/event: `[Temperature value and time when the high-temperature alarm occurs.]`

---

## Submission Checklist

- [x] I entered my student information.
- [x] I answered Questions 1–20.
- [x] I used my own words.
- [x] I checked spellings and technical terms.
- [x] I completed `student-work/reflection.md`.
- [x] I made at least three meaningful commits.
- [x] I checked the Actions result.
- [x] I submitted my repository link to Prof. Dattaraj Vidyasagar.
