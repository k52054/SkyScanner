# SkyScanner — Development Journal
**Date:** November 16, 2026

## Today's Progress

Today, I continued developing the SkyScanner PCB project using KiCad. My main focus was learning how to expand the initial LED circuit and prepare the design for PCB development.

### What I worked on

- Continued developing the ATtiny412-based LED circuit.
- Added a USB-C receptacle to the schematic for USB-powered operation.
- Learned the difference between USB-C plugs and receptacles.
- Configured the USB-C connector for a power-only design.
- Connected the CC pins using pull-down resistors.
- Left unused USB data and auxiliary pins (D+, D−, SBU1, SBU2, and VCONN) unconnected.
- Ran the Electrical Rules Checker (ERC) multiple times and reviewed the remaining power-related warnings.
- Explored voltage regulator options for converting USB 5V to the circuit's 3.3V supply.

### What I learned

- How USB-C CC pins work in a power-only configuration.
- The purpose of SBU pins and why they aren't needed for this project.
- The difference between USB VBUS (5V) and the MCU's 3.3V supply.
- How voltage regulators provide a stable voltage for electronic components.
- How KiCad's ERC identifies potential electrical issues.

### Next Steps

1. Move the schematic into KiCad PCB Editor.
2. Update the PCB from the schematic.
3. Verify component footprints.
4. Arrange components on the board.
5. Define the PCB outline.
6. Begin routing connections.
7. Run the Design Rules Checker (DRC).

### End-of-Day Reflection

Today was primarily about understanding the USB-C power configuration and getting more comfortable with KiCad. I haven't started PCB layout yet, so that's my main goal for the next development session.

**Progress:** Schematic development underway. PCB layout is the next milestone.
