# OSI Model – Packet Tracer Simulation

## Objective

Understand how network communication can be analyzed through the different layers of the OSI model using Cisco Packet Tracer.

## Topology

The lab uses a preconfigured network topology to observe the protocols and technologies involved in network communication.

![Network Topology](Topology.png)

## OSI Layer Analysis

| OSI Layer | Protocol / Technology | Role |
|---|---|---|
| Layer 7 – Application | DHCP | IP configuration |
| Layer 4 – Transport | UDP | Transport of DHCP messages |
| Layer 3 – Network | IPv4 | Logical addressing |
| Layer 2 – Data Link | Ethernet | Frame delivery |
| Layer 1 – Physical | Ethernet | Transmission |

## Simulation

Packet Tracer Simulation Mode was used to inspect the PDUs exchanged through the network.

![DHCP Simulation](Simulation-PDUs.png)

## Key Observation

The simulation demonstrates the concept of encapsulation: application data is transported using UDP, encapsulated into an IPv4 packet, 
and then into an Ethernet frame.

## Skills

- OSI Model
- Encapsulation
- Decapsulation
- Cisco Packet Tracer
