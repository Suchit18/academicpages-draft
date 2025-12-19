---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Here are some selected projects.

Rapid Diagnosis of ACL Injuries                                                                                                                                                           May 2024
Aim: To build a Point of Care device to assess the Anterior Cruciate Ligament injuries using a portable 7.5MHz linear ultrasound probe as an alternative to Magnetic Resonance Imaging (MRI)
•	Engineered and simulated circuits based on push-pull MOSFET topology in LTSpice Circuit Simulator to generate the excitation pulses for the ultrasound transducer crystals
•	Built an image processing pipeline using Python to reconstruct ultrasound images and improve their quality, using histogram equalization and contrast stretching
•	Implemented segmentation functionality to divide image into multiple regions for further diagnosis

5-Stage Pipelined Arithmetic Logical Unit (ALU) Design                                                                                                                    May 2025
Aim: To design and verify a 5-stage pipelined ALU in Verilog with correct multi-cycle timing and instruction flow
•	Designed a pipelined ALU in Verilog with multi-cycle instruction flow and validity-based control 
•	Implemented a combinational ALU for arithmetic, logical, and shift operations 
•	Managed instruction propagation and result timing using pipeline registers and valid signals to ensure correct execution alignment
•	Verified functionality using a Verilog testbench in Vivado and analyzed latency and timing behavior through waveform simulation

Fixed Point FFT Core                                                                                                                                                                                 July 2025
Aim: To implement and verify a 16-point radix-2 FFT using fixed-point arithmetic in Verilog 
•	Implemented a 16-point FFT in Verilog to convert input signals from the time domain to the frequency domain
•	Designed the datapath with fixed-point arithmetic and stage-wise scaling to manage dynamic range during computation
•	Verified the functionality by developing testbenches that applied impulse signals and analyzing the resulting waveforms in Vivado
