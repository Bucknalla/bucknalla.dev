---
layout: post
title:  "Intro to Zedboard and Xilinx Zynq SoC"
description: "Documenting my learning process with the Xilinx Zynq SoC Platform"
date:   2017-12-15 19:19:43
image: /images/ZedBoard_RevA_sideA_0_0.png
keywords: "Xilinx, Zynq, FPGA, SoC, ARM"
comments: true
category: zynq
---

As I start down the road of building complex systems with the Xilinx Zynq platform, I’ve decided to document what I’m learning from using the device as a record of what I’m doing as well as documentation for others using this PSoC (Programmable System on Chip) and tool chain.

## What is the Zedboard and the Zynq?

The Zedboard is a Digilent Development Board for the Xilinx Zynq-7000 SoC (AP SoC). The Zynq platform is particularly interesting as it includes both a processing systems (PS) and programmable logic layer (PL). In essence, this means that the user has access to a full general purpose processor, which is accompanied by the logical fabric of an FPGA.

## What will I be using it for?

My interest for using the Zedboard relates to two aspects of the development board; the SoC and the FMC connector (the port on the right side of the board). I’m intending to use the Xilinx Zynq SoC as an adaptive baseband controller of a Software Defined Radio System. This is in part, to the lead up of my thesis, of which this research will help me to determine the topic.

<div style="text-align:center">
<img src="/assets/images/zynq.png" width="400px">
<h5 align="center">Zynq-7000 SoC Block Diagram — fig 1.</h5>
</div>

## Who are these posts for?

These posts are for anyone looking at getting into programmable logic development, software defined radio or simply interested in following what I’m working on. My philosophy is that the best way to learn is to teach and hopefully by sharing these posts and tutorials, I’ll reinforce what I’ve been working on as well as create a record for my own sanity!

## What will I be talking about?

I intend to use these medium posts as a way to talk in more detail about some of the following topics.
- Software Defined Radio (SDR)
- System Verilog and various hardware description languages (HDLs)
- SoC and how to utilize the power/flexibility of general purpose processing as well as the PL fabric
- A number of other related topics; Micro controllers, C/C++, Git, etc.

### References
*[figure 1.](http://www.zedboard.org/product/zedboard)*