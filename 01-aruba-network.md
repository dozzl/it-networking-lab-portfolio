# Aruba network configuration

**Context:** CSP450 academic group project. The original reports were prepared by a team; individual contributions are not separated here.

## Objective
Build and document a segmented network using Aruba switches and Ubuntu virtual machines. The group report describes VLANs, switch-based DHCP, inter-VLAN communication, SSH and Wireshark checks.

## Environment and approach
- Aruba 6300 switch, Ubuntu clients, VLAN interfaces and DHCP pools.
- Client switch ports were assigned to VLANs; VLAN interfaces provided gateways and DHCP pools were defined for the client networks.
- The report describes checking client addresses and routes, connectivity between machines, SSH access and DHCP leases.
- A later project phase documented two Aruba 6300 switches, two Aruba 2530 switches, four clients, DHCP relay, OSPF and link aggregation.

## Evidence and limitations
The original group report includes configurations, packet captures and screenshots. Those materials have not been published here. Some configuration values in the report differ between its narrative and examples, so this is a conceptual project record rather than a tested configuration guide. The report does not identify which individual completed each step.
