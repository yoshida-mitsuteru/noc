# Network-on-Chip (NoC)

A compact, implementation-oriented reference for Network-on-Chip
architectures, from router microarchitecture and flow control to traffic
analysis and RTL implementation.

The initial target is a parameterizable packet-switched 2D mesh network
implemented in SystemVerilog and evaluated using reproducible traffic
patterns.

## Scope

The material will cover NoC implementation and performance evaluation,
including:

- Parameterizable 2D mesh topology
- Multi-port packet-switched routers
- Flit-based packet transmission
- Deterministic XY routing
- Input buffering
- Virtual channels
- Flow control
- Arbitration
- Deadlock-aware routing structure
- Self-checking verification
- Synthetic traffic generation
- Latency and throughput measurement
- Synthesis and FPGA validation

The implementation will also document architectural trade-offs involving
router pipeline structure, buffer depth, virtual-channel count, arbitration,
link utilization, saturation behavior, scalability, and implementation cost.

Future extensions may include an AXI-to-NoC interface, QoS mechanisms,
processor and accelerator traffic, and comparison with simpler shared
interconnect structures.

## Repository Status

Implementation is planned.

Architecture notes, source code, traffic experiments, verification results,
and measured performance will be added incrementally as the project
progresses.
