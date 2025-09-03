# Characteristics
- Elements
	- Electrical loads
	- Power sources
	- System components (Control, Conversion, Protection devices)
	- Power distribution
- Simplified layout
	- Alternator (power source) used when the engine is running
	- Battery used when the system is not running or to start the engine. 
	- AC/DC converter is needed to charge the battery from an AC generator.
- Electrical system requirements:
	- Supply all electricity requirements for all modes of operation.
	- Supply additional capacity for growth loads.
	- Provide protection against unsuitable external power.
	- In case of failure, non-flight critical and pre-selected loads should be automatically disconnected to save power.
	- Recently certified airplanes must have enough battery power for critical items for IFR (Instrument Flight Rules) flight for 30 minutes.
### Electrical Loads
- Any device demanding electricity from the system
- Classification based on distribution
	- **Galley loads**: ovens, toilets, hot water machines.
	- **Utility loads**: cabin lights, air conditioners.
	- **Essential loads**: motors, external lights.
- Classification based on services
	- **Motors and actuation**
		- Drives valves and actuators
	- **Lighting services**
		- External lighting: Navigation, Aft, Strobe, Logo, Landing/Taxi, Inspection, Emergency evacuation, Searchlights.
        - Internal lighting: Cockpit, Passenger information, Passenger cabin, Emergency, Cargo bay lights.
	- **Heating services**
	- **Subsystem controllers and avionics systems**
### Power Generation
- **Batteries**
	- Used for short-term emergency power
	- Charged by the engine-driven generator
- **Generators**
	- Mechanical energy provided by engines/APU/Ram-air turbine (rarely)
	- Most systems on aircraft use AC, so AC power is converted to DC for use when needed
	
| AC Generators                                           | DC Generators                           |
| :------------------------------------------------------ | :-------------------------------------- |
| Use slip rings                                          | Use commutators                         |
| Generates a sine wave                                   | Supplies a constant voltage             |
| Higher output limit                                     | Limited to 400A                         |
| Generates more power for their size than weight than DC | Less efficient at power generation      |
| Produces more power at lower rpm                        | A higher RPM is needed to math AC power |
| Mainly used for larger planes                           | Mainly used for general aviation        |
### Generator Control Unit
- Functions:
	- **Voltage regulation**
		- Maintains working voltage under different loads and output
		- Achieved by adjusting field coil resistance
	- **Parallel operation**
		- Ensures uninterrupted power is provided in case of engine failure
		- Generators in DC systems are parallel to ensure loads are evenly distributed
	- **Protection functions**
		- Needed for: reverse current, overvoltage, undervoltage
		- Devices:
			- Circuit breakers
			- Solid state power controllers (circuit breaker + relay)
- Devices in GCU:
	- **Switches**
		To start, stop or change current direction
	- **Rheostats**
		Controls amount of current passing through
	- **Relays**
		Switching device to remotely control a large-current circuit
	- **Solenoids**
		Switching device for mechanical controls (e.g. valves)
	- **Conversion Devices**
		- Transformer
			Changes AC voltage levels
		- Rectifier
			Converts AC to high-amp, low-volt DC
		- Transformer-rectifier units
			Converts AC to DC
		- Inverters
			Converts 28 VDC to 26 VAC or 115 VAC
		- Transistors
			Convert AC to DC
# Primary Power Distribution
- Output from generator is sent to busbars before distribution to the entire system
- Each power source supplies one or more specific buses
- The primary power distribution system coordinates the aircraft electrical power input
- Buses are interconnected with circuit protection devices
- Types of electrical distribution:
	- Split-bus system
		- Each AC generator powers one AC bus
		- Two generators can never power the same bus simultaneously
	- Parallel system
		- All engine-driven generators connect together and power all AC loads
		- Generator output current must be phase regulated
		- Advantage: buses are already connected, defected generators only need to be isolated from the system
	- Split-parallel system
		- Employs both split-bus and the parallel-bus systems
		- All four generators are operated in parallel during normal flight
		- System is operated in split-bus mode in case of failure

| Parallel bus                                                                                                             | Split bus                                                                                         |
| :----------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------ |
| Provides continuous electrical supply                                                                                    | Loss of one generator and APU means a complete loss of power to loads connected to that given bus |
| Prolongs generator lifespan since load is distributed                                                                    | Generators take larger loads                                                                      |
| Readily absorbs large spike loads                                                                                        | Susceptible to spikes                                                                             |
| Single faults can propagate through the complete system, needing expensive protection circuitry                          |                                                                                                   |
| <span style="font-size: 15px;">Parallel operation does not meet the requirements for totally independent supplies</span> |                                                                                                   |
| <span style="font-size: 15px;">Load shedding is required when more than 2 generating sources failed</span>               |                                                                                                   |
