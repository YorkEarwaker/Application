# Data Distribution Service dds

P2P sysetem of systems, 

See also
* Micro grid, Hybrid Power, <todo: consider, include link to gh project >
* NEXUS-1, robot systems,  <todo: consider, include link to jh repo>

stub

## Notes
Likely a lot of use for the AGW project

Objectives
* Composability
* Interoperability

Use Cases
* Weather Station
* Power, micro grid
* Health
* Robot Systems, consider as model for composable systems

## Status
TODO
* <todo: consider, first project, AGW focus, >

DONE
* <done: consider, intent to commit>
* <done: consider, first cut whats out there, survey of implementations, >

## Libs

Implementation - FOSS
* <todo: markdown table>
* eProsima Fast DDS, C++, bindings; Python, Java via wrapper, . lisense; Apache 2.0, . notes; default in ROS 2, e2e latency best OSS/FOSS. OSS DDS adopted most.
* Eclipse Cyclone DDS, C, bindings; C++, Python, . lisense; EPL 2.0, . notes; embedded, small footprint, ~8MB idle, 
* OpenDDS, C++, Java (JNI), Python, . lisense; custom BSD like, . notes; object computing inc. oldest OSS DDS, CORBA history on ACE, secure, ~25MB
* PrismTech Vortex OpenSplice Community Ed., bindings; C, C++, Java, . lisense; Apache 2.0 . notes; Vortex commercial prod subset

Implementation - FOSS, emerging RUST, immature as of Q3 2026, reasses best use case in q2/q3 2027, 
* HDDS, RUST, bindings; C, C++, Python, TypeScript, . lisense; Apache 2.0 / MIT . notes; paid tier, no paywall, no ce features gate, interop tested wit RTI, FastDDS, CycloneDDS, OpenDDS, . 257 ns latency claim, 
* ZeroDDS, RUST, bindings; C, C++, C#, Java, Python, TypeScript, Flutter, . lisense; Apache 2.0 . notes; paid tier, no paywall, no ce features gate

Implementation - Proprietry, Commercial
* RTI Connext DDS, bindings; C, C++, Java, C#, . lisense; expensive, .  notes; most deployed aerospace defence, automotive, robotics , best all round benchmark performance. 
* PrismTech Vortex Opensplice, bindings; C, C++. Java, C#, .Net . lisense; mid range? . notes; long history, strong IoT

Organisations
* DDS Foundation
* Object Management Group
* ...

## References

* DDS, OMG




