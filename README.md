# Umarell-Attacker-Carburos
Example of formal verification in ProVerif of a Multi-Factor Authentication (MFA) protocol (Carburos) under the Umarell attacker model. The model includes the attacker and the physical channel.

# scenario.pv
A standard DY attacker attempts to violate the MFA protocol security compromising the confidentiality of the authentication token. The attacker controls the network infrastructure, including the NLOS channels, but cannot interfere with the LOS channels. This scenario features a roadway with two RSUs and two vehicles.
The scenario is extended by introducing the Umarell attacker who interferes with the LOS channels. 
