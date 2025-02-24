---
layout: page
title: Development
permalink: /development/
---

Source Code
===========

* [Development Trunk](https://github.com/verilog-to-routing/vtr-verilog-to-routing)

Developer Guide
===============

* [Developer Guide](https://docs.verilogtorouting.org/en/latest/dev/)

Build Status
============

* [Buildbot](http://builds.verilogtorouting.org:8080/waterfall) 
* [Travis CI](https://travis-ci.com/verilog-to-routing/vtr-verilog-to-routing)

<!---
Commenting out the automated QoR tracking, as we have moved away from this and it isn't maintained anymore.

Quality-of-Result Tracking
==========================

The main QoR tracking regression tests:

* [Nightly Regression](http://builds.verilogtorouting.org:8088/view?db=nightly.db)
  * VTR:
    * [Critical Path Delay](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vtr_reg_qor_chain&x=parsed_date REAL&y=critical_path_delay REAL&),
      [Minimum Channel Width](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vtr_reg_qor_chain&x=parsed_date REAL&y=min_chan_width INT&),
      [Routed Wirelength](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vtr_reg_qor_chain&x=parsed_date REAL&y=routed_wirelength INT&)
    * [Pack Time](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vtr_reg_qor_chain&x=parsed_date REAL&y=pack_time REAL&),
      [Place Time](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vtr_reg_qor_chain&x=parsed_date REAL&y=place_time REAL&),
      [Crit. Path Route Time](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vtr_reg_qor_chain&x=parsed_date REAL&y=crit_path_route_time REAL&),
      [VPR Peak Memory](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vtr_reg_qor_chain&x=parsed_date REAL&y=max_vpr_mem INT&)
  * MCNC:
    * [Critical Path Delay](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vpr_reg_mcnc&x=parsed_date REAL&y=critical_path_delay REAL&),
      [Minimum Channel Width](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vpr_reg_mcnc&x=parsed_date REAL&y=min_chan_width INT&),
      [Routed Wirelength](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vpr_reg_mcnc&x=parsed_date REAL&y=routed_wirelength INT&)
    * [Pack Time](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vpr_reg_mcnc&x=parsed_date REAL&y=pack_time REAL&),
      [Place Time](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vpr_reg_mcnc&x=parsed_date REAL&y=place_time REAL&),
      [Crit. Path Route Time](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vpr_reg_mcnc&x=parsed_date REAL&y=crit_path_route_time REAL&),
      [VPR Peak Memory](http://builds.verilogtorouting.org:8088/view?db=nightly.db&t=vpr_reg_mcnc&x=parsed_date REAL&y=max_vpr_mem INT&)
* [Weekly Regression](http://builds.verilogtorouting.org:8088/view?db=weekly.db)
  * VTR:
    * [Critical Path Delay](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=vtr_reg_qor_chain_predictor_off&x=parsed_date REAL&y=critical_path_delay REAL&),
      [Minimum Channel Width](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=vtr_reg_qor_chain_predictor_off&x=parsed_date REAL&y=min_chan_width INT&),
      [Routed Wirelength](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=vtr_reg_qor_chain_predictor_off&x=parsed_date REAL&y=routed_wirelength INT&)
    * [Pack Time](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=vtr_reg_qor_chain_predictor_off&x=parsed_date REAL&y=pack_time REAL&),
      [Place Time](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=vtr_reg_qor_chain_predictor_off&x=parsed_date REAL&y=place_time REAL&),
      [Crit. Path Route Time](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=vtr_reg_qor_chain_predictor_off&x=parsed_date REAL&y=crit_path_route_time REAL&),
      [VPR Peak Memory](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=vtr_reg_qor_chain_predictor_off&x=parsed_date REAL&y=max_vpr_mem INT&)
  * Titan:
    * [Critical Path Delay](builds.verilogtorouting.org:8088/view?db=weekly.db&t=titan_reg&x=parsed_date REAL&y=critical_path_delay INT&),
      [Routed Wirelength](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=titan_reg&x=parsed_date REAL&y=routed_wirelength INT&)
    * [Pack Time](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=titan_reg&x=parsed_date REAL&y=pack_time REAL&),
      [Place Time](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=titan_reg&x=parsed_date REAL&y=place_time REAL&),
      [Crit. Path Route Time](builds.verilogtorouting.org:8088/view?db=weekly.db&t=titan_reg&x=parsed_date REAL&y=crit_path_route_time INT&),
      [VPR Peak Memory](http://builds.verilogtorouting.org:8088/view?db=weekly.db&t=titan_reg&x=parsed_date REAL&y=max_vpr_mem INT&)

The following regression tests are run after every check-in:

* [Basic Regression](http://builds.verilogtorouting.org:8088/view?db=basic.db)
-->
* [Strong Regression](http://builds.verilogtorouting.org:8088/view?db=strong.db)

