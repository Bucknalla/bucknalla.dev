---
layout: post
title: "What is Software Defined Radio?"
date: 2017-12-25 16:42:24
comments: true
description: "Brief overview of SDR and learning resources"
keywords: "SDR"
image: /images/zed-sdr.png
category: blog
tags:
- sdr
---

The term, **Software Defined Radio** (SDR) often gets conflated by the idea of Software Controlled Radios (SCR), which in essence are part of the control layer for an SDR but are by no means SDRs themselves. An SCR might be a radio system that is tunable or managed by software but the physical layer remains fixed in hardware. In contrast, SDRs are radios in which all or part of the physical layers (hardware) are manipulated/configured through the use of software. 

In this blog post, I'll dive into the what is meant by a "physical layer" further on but for now this is the layer that controls the modulation/demodulation, filtering, encoding, etc. of the receieved and/or transmitted signals. For example, a car radio might be controlled by software managing the frequencies of the user's desired radio stations; this would be defined as a Software Controlled Radio.

## That's interesting but why would I need an SDR?

SDR is interesting to a number of different types of users from academic to military application and from commercial to consumer. It might surprise you to know that you likely interact with an SDR every day, your mobile/cellular phone. 

### Academic Research

This blog post hardly covers what can be done with SDR as every day new tools are frameworks are being published, offering open source implementations of current standards such as 802.11, ZigBee, LoRa and Bluetooth. Tools such as GNU Radio Companion when combined with lower cost wideband SDR hardware make it easier, faster and increasingly affordable for academics to explore with their research. My personal research interests relate to upcoming cellular standards for IoT and designing adaptive baseband layers on top of partially reconfigurable hardware (using a Xilinx Zynq SoC).

### Hobbyist Interest

Here's a run down on some of the interesting things you can do with SDR:

- Listen to Broadcast Radio (FM & AM)
- Set up your own HAM Radio
- Get involved with Radio Astronomy
- Track Aircraft with the Mode S Protocol
- Track Ships and other Vessels with AIS
- Build your own GSM Network
- Experiment with various other RF Protocols
- Many more!

Please note that this is a none exclusive list as this hardly scratches the surface as to what can be done with SDR!

## Ok, you've convinced me! Where can I start learning about SDR?

Historically, SDR has had a relatively high barrier to entry for beginners as the cost point of typical open SDRs hardware and toolkits has been in the region of £1000+. Fortunately, the open source community has assembled a fantastic set of tools that support a huge variety of radios, known as GNU Radio. GNU Radio applications can be written in C++ & Python lanugages as well as assembled in flow diagram formats using a tool called the GNU Radio Companion. This toolkit is 100% and supports from the very low end of SDRs (~£20) all the way through to industry standard devices.

To get started, I'd recommend taking a look at ![RTL-SDR](https://www.rtl-sdr.com/about-rtl-sdr/), a $20 USB TV Tuner Dongle that can be used as a computer based radio scanner. This nifty device will let you play with a whole range of interesting SDR from simple amplitude & frequency modulation/demodulation to ![reading smart meters](https://blog.kroy.io/monitoring-home-power-consumption-for-less-than-25/).

## Useful SDR Resources

- [Hack RF](https://greatscottgadgets.com/hackrf/)
- [Learn SDR with Hack RF](https://greatscottgadgets.com/sdr/)
- [Get Started with SDR - RTL-SDR](https://coderwall.com/p/roldfw/getting-started-with-sdr-with-rtl2832u)

### References
*[RS - What is SDR?](https://www.rs-online.com/designspark/10-things-you-can-do-with-software-defined-radio)*
