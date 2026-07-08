# 8S Li-ion Battery Active Balancing System Based on Flyback Converter

This repository contains our undergraduate graduation thesis on the design of a flyback converter based bidirectional active balancing system for 8-cell Li-ion battery packs.

## Project Title

**Design of a Flyback Converter Based Active Balancing System for Bidirectional Energy Transfer in 8-Cell Li-ion Battery Packs**

**Türkçe Başlık:**  
**8 Hücreli Li-ion Batarya Paketlerinde Çift Yönlü Enerji Aktarımı için Flyback Dönüştürücü Tabanlı Aktif Dengeleme Sistemi Tasarımı**

## Authors

- Faruk Küçüktatıl  
- Berkant Akıncı  

## Advisor

- Assoc. Prof. Dr. Davut Ertekin

## University

Bursa Technical University  
Faculty of Engineering and Natural Sciences  
Department of Electrical and Electronics Engineering  

## Project Overview

In this graduation project, a flyback converter based bidirectional active balancing system was designed for an 8-series Li-ion battery pack.

The main purpose of the project is to reduce voltage imbalance between cells in multi-cell Li-ion battery packs. Instead of dissipating excess energy as heat, the proposed active balancing structure aims to transfer energy between the selected cell and the battery pack.

The system is designed to support two operating modes:

- **Cell-to-Pack (CTP):** Energy transfer from a high-voltage cell to the battery pack  
- **Pack-to-Cell (PTC):** Energy transfer from the battery pack to a low-voltage cell  

## Main Project Topics

- Battery Management System (BMS)
- Active cell balancing
- Flyback converter design
- Bidirectional energy transfer
- MOSFET-based cell selection matrix
- STM32-based control approach
- MATLAB/Simulink simulations
- 4-layer PCB design

## Hardware and Design

The project includes the design of a 4-layer PCB for the active balancing system. The hardware structure includes:

- Flyback converter power stage
- MOSFET switching matrix
- Current and voltage sensing points
- Gate driver circuits
- Snubber and protection structures
- STM32 Nucleo based control interface

## Simulation

The system was modeled and analyzed in MATLAB/Simulink. Both Cell-to-Pack and Pack-to-Cell operating modes were evaluated using current and voltage waveforms.

## Thesis Document

The full thesis document can be accessed from the repository files.

[View Thesis PDF](./8S-Liion-Active-Balancing-Flyback-Converter-Thesis.pdf)

## Project Images

Project photos, PCB layout images and 3D PCB render views are included in this repository.

## Keywords

Battery Management System, BMS, Active Balancing, Flyback Converter, Power Electronics, Embedded Systems, STM32, PCB Design, MATLAB, Simulink
