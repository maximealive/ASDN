# Advanced Software Defined Network Lab

Here are three experiences, each accompanied by a file outlining the objectives to achieve and the corresponding ".pkt" file.

## Outline
### Experience 1
### Experience 2
### Experience 3

### Software
Cisco Packet Tracer v. 8.2.1.0118

### Common Issues and Observations
- If unexpected problems occur --> Exiting and Relaunching Packet Tracer
- If the protocol is down (e.g., between two directly connected routers) --> Delete the link and recreate it.
- Fully specified static routes are not working with the routers used or their current software version --> Use either of these alternative static route types instead: Directly Connected Static Route or Next-Hop Static Route (also called recursive static route, for multi-access networks)
- Pay attention to the Packet Tracer version you're using and the operating system (Windows, Linux, macOS, etc.). Running it on a specific O.S. or different version may cause unexpected issues (e.g., crashes, missing features, or lab failures).
- Keep in mind that Cisco Packet Tracer is a __simulator__, not a full emulator. As a result, you may encounter occasional unexpected behavior or limitations compared to real hardware. If a configuration doesn’t work as expected, verify the syntax and logic, and consult official Cisco documentation or forums for simulator-specific quirks.
- VTP Transparent Mode Warning --> As highlighted in Experience 2 - Errata Corrige and within the project report, exercise caution when using VTP Transparent mode. Misconfiguration can lead to unintended VLAN propagation or database mismatches across switches. Always verify VLAN synchronization and ensure consistent domain names/passwords.
