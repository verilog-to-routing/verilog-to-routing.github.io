---
layout: default
---

The Verilog to Routing (VTR) project provides open-source CAD tools for FPGA architecture and CAD research.

<figure style="float:right">
    <img src='/img/vpr_placement.png' alt='VPR Placement' width="350px" />
    <figcaption>VPR: Placement</figcaption>
</figure>

Open source CAD tools enable the investigation of new FPGA architectures and CAD algorithms, which are not possible with closed-source tools.

The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture. It then perfoms:

* Elaboration & Synthesis (ODIN II)
* Logic Optimization & Technology Mapping (ABC)
* Packing, Placement, Routing & Timing Analysis (VPR)

to produce FPGA speed and area results.
VTR can also produce the information required for bitstream generation to target real FPGA devices.

<figure style="float:left">
    <img src="/img/vpr_sb.png" alt="FPGA Routing Switchbox" width="200"/>
    <figcaption>FPGA Routing Switchbox</figcaption>
</figure>

VTR is flexible and can taget a wide range of hypothetical, commercial-like and commercial FPGA architectures, and includes benchmark designs suitable for evaluating FPGA architectures.


For more information see the [documentation](https://docs.verilogtorouting.org).

<figure style="float:right">
    <img src="/img/vpr_routing_utilization.png" width="400px" alt="Routing Utilization"/>
    <figcaption>VPR: Routing Utilization</figcaption>
</figure>

