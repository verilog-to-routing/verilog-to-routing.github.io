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
The following [paper](http://www.eecg.utoronto.ca/~kmurray/vtr/vtr8_trets.pdf) may be used as a general citation for VTR (bibtex format):

    @article{vtr8,
      title={VTR 8: High Performance CAD and Customizable FPGA Architecture Modelling},
      author={Murray, Kevin E. and Petelin, Oleg and Zhong, Sheng and Wang, Jai Min and ElDafrawy, Mohamed and Legault, Jean-Philippe and Sha, Eugene and Graham, Aaron G. and Wu, Jean and Walker, Matthew J. P. and Zeng, Hanqing and Patros, Panagiotis and Luu, Jason and Kent, Kenneth B. and Betz, Vaughn},
      journal={ACM Trans. Reconfigurable Technol. Syst.},
      year={2020}
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
