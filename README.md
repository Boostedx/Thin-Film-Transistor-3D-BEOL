<img width="1209" height="853" alt="Screenshot 2025-02-03 233751" src="https://github.com/user-attachments/assets/2c7de9b5-b4b7-43b9-bfad-1421f76b9a61" />


# Thin-Film-Transistor-3D-BEOL
Sentaurus TCAD simulations of a Pd/IWO/HfO₂ thin-film transistor for 3D BEOL integration. Includes device structures, input decks, and results analyzing threshold voltage, leakage, and scaling behavior for low-power, high-density applications.

Thin-Film-Transistor-3D-BEOL

Sentaurus TCAD simulations of Pd/IWO/HfO₂ thin-film transistors for 3D BEOL integration

Overview

This repository contains my work on thin-film transistor (TFT) simulations for 3D Back-End-of-Line (BEOL) integration using Synopsys Sentaurus TCAD. The project focuses on analyzing device behavior, scaling limits, and material properties of a Pd/IWO/HfO₂ transistor structure, designed to enable low-power, high-density circuits in advanced 3D integration.

Device Stack:

Upper Gate: 100 nm Pd

Second Gate: 20 nm Pd

Drain/Source Contacts: 50 nm Pd

Channel: 7 nm Indium Tungsten Oxide (IWO)

Insulator: 5 nm HfO₂

Substrate: 90 nm SiO₂ on p-type Si

Features

Complete Sentaurus input deck files (.cmd, .tdr, .plt)

Device structures and doping profiles

Bias sweeps (ID–VG, ID–VD curves)

Parameter studies: oxide thickness, gate work function, channel scaling

Post-processing scripts (MATLAB/Python) for IV extraction and plotting

Results Snapshot

Extracted threshold voltage (Vth), subthreshold slope, and leakage currents

Studied scaling behavior for channel and dielectric thickness

Validated potential of oxide TFTs in BEOL-compatible 3D integration

Future Work

Explore ferroelectric HfO₂ as a gate dielectric

Benchmark against FinFET and GAAFET structures

Investigate reliability and variability in BEOL environments
