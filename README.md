# 45 MW Grid-Connected Solar Power Plant Design (Fatikchory, Chattogram)

## Project Overview

This repository contains the electrical system design and plant layout of a 45 MW AC Grid-Connected Solar Power Plant located in Fatikchory, Chattogram, Bangladesh.

The project includes:

    * Complete Single Line Diagram (SLD)
    * Protection and Control Philosophy
    * 132 kV Grid Interconnection Design
    * 33 kV Collection System
    * Inverter Distribution Network
    * Internal Plant Layout
    * Switchyard Arrangement
    * Control Building Layout

The design was developed as part of engineering work carried out at Abtahi Power and Automation

## Project Capacity

| Item                       | Value                 |
| -------------------------- | --------------------- |
| Plant Capacity             | 45 MW AC              |
| Grid Voltage               | 132 kV                |
| Collection Voltage         | 33 kV                 |
| Inverter Output Voltage    | 800 V AC              |
| DC System Voltage          | 1500 V DC             |
| Power Transformers         | 2 × 20/25 MVA         |
| Inverter Duty Transformers | 7 × 7.5 MVA           |
| Solar Inverters            | Multiple 460 kW Units |


## System Architecture

The generated DC power from solar PV strings is converted into AC power through string inverters.

Power flow:

        Solar PV Arrays
                ↓
        1500 V DC
                ↓
        String Inverters
        (800 V AC)
                ↓
        0.8/33 kV IDT
                ↓
        33 kV Collection Bus
                ↓
        33/132 kV Power Transformers
                ↓
        132 kV Switchyard
                ↓
        National Grid


## Single Line Diagram Features

### Grid Interconnection

    * 132 kV Outdoor Switchyard
    * Double Transformer Configuration
    * Transmission Line Interface
    * Lightning Protection System

### Protection Scheme

The protection design includes:

    * Differential Protection (87/87N)
    * Overcurrent Protection (50/51)
    * Earth Fault Protection (50N/51N)
    * Directional Overcurrent Protection (67)
    * Directional Earth Fault Protection (67N)
    * Breaker Failure Protection (50BF)
    * Busbar Protection
    * Transformer Protection

### Metering and Instrumentation

    * Current Transformers (CT)
    * Capacitive Voltage Transformers (CVT)
    * Multifunction Meters
    * Revenue Metering
    * Power Quality Monitoring

---

## Layout Design Features

The plant layout includes:

### Main Substation Building

    * Protection & Control Room
    * PPC Room
    * SCADA Workstations
    * Server Room
    * Communication Room
    * Conference Room
    * Fire Control Room

### Electrical Equipment

    * 132 kV Switchyard
    * 33 kV Switchgear
    * Power Transformer Bays
    * Auxiliary Transformer Bays
    * Earthing Transformers
    * Battery Rooms
    * UPS Systems
    * Rectifier Systems

### Auxiliary Systems

    * Diesel Generator System
    * Fire Protection System
    * Station Service Power System
    * DC Supply System
    * Communication Infrastructure


## Engineering Standards

The design follows internationally accepted standards including:

    * IEC 60076 (Power Transformers)
    * IEC 62109 (Inverters)
    * IEC Protection Standards
    * Utility Grid Interconnection Requirements
    * Solar Power Plant Design Practices

## Software & Tools Used

* AutoCAD
* Electrical Design Calculations
* Protection Coordination Principles
* Power System Engineering Standards


## Author

**Fahim Faisal**

B.Sc. in Electrical & Electronic Engineering (CUET)

Graduate Trainee Engineer

Abtahi Power and Automation

Specialization:

    * Power System Design
    * Solar Power Plants
    * Substation Engineering
    * Protection & Control Systems
