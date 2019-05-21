# Juniper_BGP-_S-IS_with_RR
Description
Devices:
  6 vMXs running Junos OS 18.3R1.9
  2 vRRs running Junos OS 18.1R2
Configured Interfaces:
  vMX
    ge interfaces for in-band traffic
    lo0 as loopback interface
  vRR
    em interfaces for in-band traffic
    lo0 as loopback interface
Configured protocols:
  BGP, 4 ASs
  IS-IS (Level 2) as IGP in each
IP addressing: all addresses are in the range 10.100.x.x/24
ISO NET addressing: all addresses are in the 49.000x.x range
