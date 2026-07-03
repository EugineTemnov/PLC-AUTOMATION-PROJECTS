# PLC-AUTOMATION-PROJECTS
automation and safety projects based on CODESYS 3.5
Projects in Automation and Industrial Control - CODESYS 3.5 
This portfolio showcases control logic, safety protections, and process management written in Structured Text (ST) in accordance with the IEC 61131-3 standard.
The projects were built as a practical toolkit for maintenance work, troubleshooting, and the commissioning of production lines and machinery. 

Project 1: Smart Oven & Conveyors Control System (line simulation v2.project)
A comprehensive simulation of an industrial oven that includes an infeed conveyor, an outfeed conveyor, a heating element, and a cooling fan, all managed by a State Machine.
Engineering & Logical Highlights in the Code:
•	Safety Interlock & Reset Mechanism: Locks the system into a safe state if the emergency stop (STOP) button is pressed, and prevents a restart (Reset) until the temperature drops to a safe level.
•	Thermal Runaway Protection: The controller monitors the rate of temperature rise (Trend Protection). If heating is activated but the temperature fails to rise (due to a burned-out heating element or a disconnected sensor), the system immediately enters an EMERGENCY state to prevent damage.
•	Hardware Fault Detection: Detects implausible temperature sensor readings (below -40°C during operation) to trigger a hardware failure alarm.
•	Sensor Scaling Block: A simple and reusable functional block for the linear scaling of raw sensor outputs into engineering units (real values).
•	Sensor Logging/Recording Block: Enables change detection and prepares data for potential export to external analytics databases.

Professional Profile
•	Education: Certified Electrician Diploma + Assistant Electrician License.
•	Skills: Deep understanding of PLC logic, schematic reading, panel wiring, and integrated hardware and software troubleshooting. 


