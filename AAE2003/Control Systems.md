# Primary Flight Control
- Controls pitch, roll and yaw, stabilizes flight
- Tail designs:
	- T-tail configuration: 
		- Elevator is above most downwash effects. 
			- Popular for light and large aircraft. 
				- Can have issues like flutter and susceptibility to deep stall.
				- Elevator action can cause large moment on VTH, requiring stronger materials
	- Canard design: 
		- Uses two lifting surfaces in front of main wings for stabilisation. 
		- Canard mainly provides force for nose-up. 
		- Aft-tail (elevator) mainly provides lift to prevent nose-up. 
	- V-Tail design: 
		- Uses two slanted tails to perform elevator and rudder functions.
		- Fixed parts act as stabilisers.
		- Movable parts are called ruddervators

| Control Surface | Location              | Affects |
| :-------------- | :-------------------- | :------ |
| Alieron         | Wings                 | Roll    |
| Elevator        | Horizontal tail plane | Pitch   |
| Rudder          | Vertical tail plane   | Yaw     |
# Secondary Flight Control
- Assists primary controls for better flight control
- **High Lift Devices**
	- Used during takeoff and landing
	- Flap: ==inboard trailing edge of wings==
		- Reduces stall velocity
		- Increases wing camber and lift
		- Increases drag
		- Reduces take-off and landing distances
	- Slat: ==mid-outboard leading edge of wings==
		- Delay stall
		- Increase lift coefficient
- **Air Brakes**
	- High drag device commonly found on fighter jets
- **Spoilers**
	- Mounted on upper surfaces of wings
	- Reduces lift and increases drag
	- Controls descent rate for accurate landing and roll control
- **Trim Systems**
	- Compensates for unbalanced moments
	- **Trim Tab**
		- Assists control surface movement
	- **Balance tab**
		- Assists control surface movement
	- **Anti-balance tab**
		- Increases feel and effectiveness of primary control surface
# Control Linkage Systems
- Transmits manual inputs to control surfaces
- Could be mechanical, electric or hydraulic
- **Cable and pulley systems**
	- Cables are connected from the control in the cockpit to a bell crank, which is then connected to the control surface
	- Disadvantages: Tension must be periodically adjusted due to stretching/temp changes
- **Push-Pull control rod**
	- Uses metal rods connected to bellcranks or form coupler links
	- Commonly steel, also aluminum or composite
# Artificial Feel System
 - Used to ensure pilots sense the magnitude of the effect of their control actions. 
 - Produces opposition to pilot movement
 - **Spring feel system**: 
	 - Uses springs as the force producer.
	 - Pilot feels spring resistance as input is made.
	 - Effective at low speeds and with large deflections.
	 - Dominant at low speed/high deflection control demands
 - **"Q"-feel system**: 
	 - Q refers to dynamic pressure measured from pitot tube
	- Uses linear piston motion for feel resistance.
	- Realised by hydraulic system.
	- Dominant at high speed and for low deflection controls.
# Flight Control Actuation
- **Mechanical actuation**:
	- Fundamental parts (cables, pulleys, pushrods) transfer pilot input to surfaces. 
	- Complexity/weight increase with aircraft size, making manual handling impossible; hydraulic/electric systems needed.
- **Hydraulically powered mechanical actuation**: 
	- Hydraulic system provides force efficiently. 
		- Two main parts: 
			- Mechanical circuit (rods, cables, pulleys, chains linking cockpit to hydraulic circuit) 
			- Hydraulic circuit (pumps, reservoirs, valves generating pressure).
    - Basic operation: Pilot input -> mechanical circuit opens servo valve (SV) in hydraulic circuit -> hydraulic circuit powers actuator -> actuator moves control surface -> mechanical feedback linkage closes SV, stopping movement at desired position.
- **Mechanical actuation with electrical Signalling**: 
	- Mechanical signalling replaced by electric means.
- **Electro-hydraulic actuators (EHA)**: 
	- Often called "power by wire". 
	- Receives power from electric source and transform input command into motion.
# Fly-by-wire
- Replaces mechanical linkage with an electronic interface using flight control computers. 
- Pilot inputs converted to electronic signals transmitted by wires. 
- Flight control computers determine actuator movement for expected response. 
- Computers constantly evaluate aircraft motion and input commands without pilot knowledge to stabilise and alleviate gust loads, significantly easing pilot workload.