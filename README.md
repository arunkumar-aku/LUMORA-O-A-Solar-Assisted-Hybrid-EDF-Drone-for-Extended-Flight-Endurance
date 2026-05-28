LUMORA-O: A Solar-Assisted Hybrid EDF Drone for Extended Flight Endurance
1. Title
Lumora-O: A Solar-Assisted Hybrid EDF Drone for Extended Flight Endurance
________________________________________
2. Abstract
The LUMORA-O is an innovative, donut-shaped UAV designed for extended flight endurance using a hybrid power system. This drone utilizes multiple Electric Ducted Fans (EDFs) for propulsion, combining the high-thrust capability of LiPo batteries with the long-duration energy sustainability of Li-ion batteries, which are continuously recharged in-flight via flexible solar panels (solar skin) integrated with Maximum Power Point Tracking (MPPT) controllers. The design is optimized for versatile applications such as surveillance, payload delivery, precision agriculture, and disaster relief operations. The LUMORA-O demonstrates cutting-edge integration of aerodynamics, modular payload capacity, hybrid power management, and in-flight solar energy harvesting, pushing UAV performance and endurance beyond conventional limits.
________________________________________
3. Objectives
1.	Design and develop a donut-shaped drone with a hybrid battery and solar energy charging system.
2.	Ensure high thrust and stable takeoff using high-discharge LiPo batteries.
3.	Maintain long-duration flight with solar-recharged Li-ion batteries.
4.	Integrate flexible solar panels with MPPT controllers to maximize in-flight recharging efficiency.
5.	Develop a modular frame supporting eight EDF propulsion units for redundancy and efficiency.
6.	Implement intelligent flight control to automatically switch between power sources based on environmental conditions and power demand.
________________________________________
4. System Overview
4.1 Drone Frame & Design
•	Shape: Donut-shaped to optimize aerodynamics and stability.
•	Material: Lightweight carbon fiber composite, balancing strength and low weight.
•	Propulsion: Eight EDF motors mounted symmetrically around the ring frame for balanced lift and thrust distribution.
•	Payload: Central modular bay for cameras, delivery pods, agricultural spraying units, or sensor modules.
•	Aerodynamic Advantages: Reduced drag due to smooth circular geometry, improved energy efficiency, and enhanced maneuverability.
4.2 Power System
•	LiPo Battery:
o	High-discharge capacity for takeoff and thrust-intensive maneuvers.
o	Enables instant power delivery without stressing the Li-ion system.
•	Li-ion Battery:
o	Sustains long-duration flight at lower current demands.
o	Recharged in-flight via integrated solar panels, minimizing dependency on ground charging.
•	Solar Skin:
o	Flexible, lightweight solar panels covering the outer ring.
o	Equipped with MPPT controllers to maximize energy harvest, even under partial shading or suboptimal angles.
o	Supplies continuous trickle charging to the Li-ion battery.
•	Battery Management System (BMS):
o	Ensures safe charging/discharging.
o	Monitors voltage, current, temperature, and prevents overcharge or deep discharge.
•	Power Distribution System (PDS):
o	Distributes power efficiently to EDFs, avionics, and payloads.
o	Facilitates automatic switching between LiPo and Li-ion batteries.
4.3 Electronics
•	Flight Controller:
o	Pixhawk or equivalent for stability control, waypoint navigation, and battery management.
o	Integrates automatic power source switching algorithms.
•	Electronic Speed Controllers (ESCs):
o	Control EDF motors with precise thrust modulation.
o	Capable of handling high peak currents during takeoff.
•	Sensors:
o	GPS: Position tracking.
o	IMU (Accelerometer + Gyroscope): Flight stability.
o	Barometer: Altitude control.
o	Telemetry module: Real-time monitoring of drone status and energy parameters.
•	Cameras/Modules:
o	HD cameras for surveillance and mapping.
o	Payloads such as delivery pods, spraying systems, or scientific sensors.
________________________________________
5. Advantages
1.	Hybrid Power System: Combines instantaneous high thrust (LiPo) with extended flight endurance (Li-ion + solar).
2.	In-flight Solar Charging: Reduces dependency on ground-based infrastructure.
3.	Redundancy: Multiple EDFs enhance safety and prevent mission failure if a single motor fails.
4.	Aerodynamic Efficiency: Donut-shaped frame reduces drag and allows modular payload options.
5.	Dynamic Power Management: Intelligent switching between battery types maintains continuous flight in varying weather conditions.
________________________________________
6. Applications
•	Disaster Relief: Rapid delivery of medical supplies, communication devices, or rescue equipment to inaccessible regions.
•	Surveillance & Mapping: Extended missions for agriculture monitoring, border surveillance, wildlife tracking, or urban planning.
•	Agriculture: Crop health monitoring, automated spraying, and precision agriculture interventions.
•	Research & Education: Testing of hybrid UAV systems, energy harvesting methods, and autonomous flight technologies.
________________________________________
7. Challenges
1.	Solar energy alone cannot support the full load of EDF motors; it serves as supplementary power.
2.	Weight optimization is critical to balance payload, solar panels, and battery mass.
3.	Thermal management for high-current LiPo and Li-ion batteries is essential.
4.	Complex power distribution requires robust electronics and fail-safes.
5.	Higher initial costs due to hybrid systems and advanced components.
________________________________________
8.Drone Design:
          
Top view         Front view              inclined view


9. Cost Analysis
Component	Quantity	Approx. Cost (₹)	Remarks
EDF Motors (×8)	 8	53,760	High-thrust EDFs for sustained lift

ESCs (×8)	8	 20,160	Suitable for high-current handling

LiPo Battery (6S)	 1	10,080	High-discharge for takeoff


Li-ion Battery Pack	 1	12,600	Long-duration flight energy

Flexible Solar Panels	1 set	12,600	Lightweight solar skin with MPPT

MPPT Controllers	 2	4,200	Efficient solar energy harvesting

BMS + PDS	1	 5,880	Safety and power distribution

Flight Controller	 1	15,000	Pixhawk or equivalent

Sensors & Telemetry	  1set	8,400	GPS, IMU, barometer, telemetry

Frame Materials	  21set	10,000	Carbon fiber, structural components

Miscellaneous Wiring & Connectors	-	3,000	Electrical integration

Total Estimate	-	~1.9–3.7 Lakh	Depending on final specifications
________________________________________
10. Plan of Action (Step-by-Step Roadmap)
Phase 1: Research & Design 
•	Analyze EDF thrust vs. power requirements for payload lift.
•	Design donut-shaped carbon fiber frame using CAD software.
•	Select battery capacities (LiPo for peak load, Li-ion for endurance).
•	Choose lightweight flexible solar panels and compatible MPPT units.
•	Simulate weight distribution, aerodynamics, and center of gravity.
Phase 2: Component Procurement 
•	Procure EDF motors, ESCs, LiPo and Li-ion batteries.
•	Acquire MPPT units, BMS, flight controller, sensors, and frame materials.
•	Order flexible solar panels, connectors, and mounting hardware.
Phase 3: Prototype Development 
•	Assemble the donut-shaped frame and mount EDFs.
•	Wire ESCs through the PDS to batteries.
•	Integrate solar skin with MPPT controllers to charge Li-ion battery.
•	Install flight controller, sensors, telemetry module, and camera.
•	Conduct preliminary electronics and motor tests on the bench.
Phase 4: Testing & Integration 
•	Bench test EDF motor thrust and thermal performance.
•	Evaluate solar charging efficiency under varying light conditions.
•	Test automatic switching between LiPo and Li-ion batteries.
•	Conduct short hover and maneuvering tests.
•	Perform extended flight tests utilizing solar assist.
Phase 5: Refinement & Deployment 
•	Optimize structural weight distribution and reinforce frame if necessary.
•	Fine-tune MPPT controller parameters for maximum energy harvest.
•	Add and validate payload modules (camera, delivery pod, sprayer).
•	Conduct field trials simulating real operational scenarios.
________________________________________
Special Battery Swapping Mechanism
•	Detect reduced solar input via onboard light sensors and telemetry.
•	Automatically switch primary power source from Li-ion to LiPo to maintain stable thrust.
•	Revert to Li-ion primary usage when solar conditions improve.
•	Ensures continuous flight endurance, even in cloudy or disturbed weather conditions.
________________________________________
11. Expected Outcomes
•	A fully functional hybrid solar-assisted EDF drone capable of extended endurance flights.
•	Quantitative data on solar contribution, battery usage patterns, and overall energy efficiency.
•	Scalable, modular architecture suitable for industrial, research, and educational purposes.
•	Demonstrated feasibility of hybrid UAV systems with in-flight solar recharge.
