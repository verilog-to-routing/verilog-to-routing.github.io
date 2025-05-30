---
layout: page
title: Download
permalink: /download/
---

<figure style="width:100%">
    <div class="grid-container">
        <div style="grid-row-start: 1; grid-row-end: 2; grid-column-start: 1; grid-column-end: 2;">
            <video autoplay loop muted playsinline width="250">
                <source src="/img/bitcoin_placement_macros.mp4" type="video/mp4"/>
            </video>
            <figcaption>Placement</figcaption>
        </div>
        <div style="grid-row-start: 1; grid-row-end: 2; grid-column-start: 2; grid-column-end: 3;">
            <video autoplay loop muted playsinline width="250">
                <source src="/img/bitcoin_nets.mp4" type="video/mp4"/>
            </video>
            <figcaption>Logical Connections</figcaption>
        </div>
        <div style="grid-row-start: 1; grid-row-end: 2; grid-column-start: 3; grid-column-end: 4;">
            <video autoplay loop muted playsinline width="250">
                <source src="/img/bitcoin_routing_util.mp4" type="video/mp4"/>
            </video>
            <figcaption>Routing Utilization</figcaption>
        </div>
    </div>
</figure>

How to Cite
===========
The following [paper](https://dl.acm.org/doi/10.1145/3734798) may be used as a general citation for VTR (bibtex format):

@article{vtr9,
     author = {Elgammal, Mohamed A. and Mohaghegh, Amin and Shahrouz, Soheil Gholami and Mahmoudi, Fatemehsadat and Ko\c{s}ar, Fahrican and Talaei, Kimia and Fife, Joshua and Khadivi, Daniel and Murray, Kevin and Boutros, Andrew and Kent, Kenneth B. and Goeders, Jeff and Betz, Vaughn},
     title = {VTR 9: Open-Source CAD for Fabric and Beyond FPGA Architecture Exploration},
     year = {2025},
     publisher = {Association for Computing Machinery},
     address = {New York, NY, USA},
     url = {https://doi.org/10.1145/3734798},
     doi = {10.1145/3734798},
     journal = {ACM Trans. Reconfigurable Technol. Syst.},
     month = May
}

License
=======

Generally most code in VTR is under MIT license, with the exception of ABC which is distributed under its own (permissive) terms.
See the full license (LICENSE.md) included with VTR for details.

Official Release
================

The official VTR release is available from:

<https://github.com/verilog-to-routing/vtr-verilog-to-routing/releases>

Development Trunk
=================
The development trunk is hosted at:

<https://github.com/verilog-to-routing/vtr-verilog-to-routing>

Unlike the nicely packaged offical releases the trunk code in a constant state of flux. 
You should expect that the tools are not always stable and that more work is needed to get the flow to run.

Legacy releases
===============

Pre VTR 8 releases are no longer supported, but are available from:

<http://www.eecg.utoronto.ca/vtr/terms.html>
