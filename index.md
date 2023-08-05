---
layout: default
---

The Verilog to Routing (VTR) project provides open-source CAD tools for FPGA architecture and CAD research. This project, along with the benchmark suites, is released under the MIT license. This means that you are free to use, modify, and distribute the software and benchmark files, subject to the terms and conditions of the MIT license.



<figure style="float:right">
    <img src='/img/vpr_placement.png' alt='VPR Placement' width="350px" />
    <figcaption>Device Floorplan & Placement</figcaption>
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

<figure style="width:100%">
    <figcaption>VPR Optimization: Placement & Routing</figcaption>
    <div class="grid-container">
        <div style="grid-row-start: 1; grid-row-end: 2; grid-column-start: 1; grid-column-end: 2;">
            <video autoplay loop muted playsinline width="250">
                <source src="img/neuron_placement_macros.mp4" type="video/mp4"/>
            </video>
            <figcaption>Placement</figcaption>
        </div>
        <div style="grid-row-start: 1; grid-row-end: 2; grid-column-start: 2; grid-column-end: 3;">
            <video autoplay loop muted playsinline width="250">
                <source src="img/neuron_nets.mp4" type="video/mp4"/>
            </video>
            <figcaption>Logical Connections</figcaption>
        </div>
        <div style="grid-row-start: 1; grid-row-end: 2; grid-column-start: 3; grid-column-end: 4;">
            <video autoplay loop muted playsinline width="250">
                <source src="img/neuron_routing_util.mp4" type="video/mp4"/>
            </video>
            <figcaption>Routing Utilization</figcaption>
        </div>
    </div>
</figure>
