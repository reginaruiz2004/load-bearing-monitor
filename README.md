# Wearable Load-Bearing Monitor

A wearable bilateral plantar-load monitoring system designed to support lower-limb rehabilitation by measuring foot loading, providing real-time biofeedback, and displaying clinically meaningful data through a wireless web dashboard.

> **Project status:** Active development  
> **Institution:** Lehigh University  
> **Clinical sponsor:** Good Shepherd Rehabilitation  
> **Development period:** Spring–Fall 2026

---

## Project Overview

Patients recovering from lower-limb injuries and orthopedic procedures are often prescribed partial weight-bearing restrictions. Following these restrictions is clinically important because excessive loading can interfere with healing, while insufficient loading may slow rehabilitation.

Current weight-bearing assessments frequently rely on verbal instructions, patient self-reporting, and periodic observation by physical therapists. These methods provide limited objective information and do not continuously alert patients when they exceed a prescribed load.

The Wearable Load-Bearing Monitor is intended to provide a lower-cost, wearable system that:

- Measures plantar loading beneath both feet
- Estimates force applied at important anatomical regions
- Streams sensor measurements wirelessly
- Compares left and right foot loading
- Provides visual and auditory biofeedback
- Helps clinicians evaluate compliance with weight-bearing restrictions

---

## Clinical Need

The project is intended for rehabilitation patients recovering from conditions such as:

- Lower-limb fractures
- Tibial plateau fractures
- Calcaneal fractures
- Total knee arthroplasty
- Total hip arthroplasty
- Lower-limb surgery
- Other conditions requiring partial weight-bearing restrictions

The prototype is being designed for use by physical therapists, rehabilitation clinicians, and patients during supervised mobility training.

---

## System Concept

The proposed system consists of bilateral sensor-equipped insoles connected to an external electronics enclosure secured near the ankle.

```text
Plantar Force Sensors
        ↓
Analog Signal-Conditioning Circuit
        ↓
Microcontroller and ADC
        ↓
Calibration and Force Conversion
        ↓
Bluetooth Low Energy
        ↓
Clinical Web Dashboard
        ↓
Visual and Auditory Feedback