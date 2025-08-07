# Lightweight AUTOSAR-Inspired BSW for Small MCUs (Work in Progress)

## Overview
This is a **work-in-progress** embedded software framework inspired by AUTOSAR, designed for small, resource-constrained microcontrollers.  
It provides a lightweight Basic Software (BSW) with modular layers for easy portability and maintainability.

## Goals
- Modular and structured embedded software design  
- Portable MCAL drivers for GPIO, ADC, UART, etc.  
- Reusable sensor and actuator service modules  
- Optimized for low-end MCUs with limited resources  

## Target Platforms
- Texas Instruments TMS570 (32-bit)  
- Renesas RL78 (16-bit)  
- TI MSP430 (16-bit)  

## Architecture
Application Layer
↓
Service Layer
↓
Microcontroller Abstraction Layer (MCAL)
↓
Hardware


## Current Status
- Initial architecture and coding guidelines defined  
- MCAL GPIO driver under development  
- LED control service planned  
- Demo application upcoming  

## Project Structure (planned)
- `/core` — Application code and main entry point  
- `/common` — Platform-independent interfaces and services  
- `/platform` — Platform-specific MCAL drivers  
- `/docs` — Documentation and diagrams  

---

*This repository will be continuously updated as development progresses.*
