# Design Decisions

This document records major engineering decisions and the evidence supporting each selection.

## Confirmed Decisions

### Bilateral Measurement

The system will measure the left and right feet independently to support load comparison and asymmetry analysis.

### Four Sensing Regions per Foot

The proposed regions are:

1. Posterior heel
2. Lateral midfoot
3. First metatarsal head
4. Fifth metatarsal head

### External Electronics Enclosure

The microcontroller, battery, and supporting circuitry will be placed in an enclosure secured near the ankle rather than directly underneath the foot.

### Wireless Communication

Bluetooth Low Energy will be used to communicate with a browser-based clinical dashboard.

### Patient Feedback

The system will include both visual and auditory threshold alerts.

## Decisions Still Under Evaluation

### Final Force Sensor

Candidate sensors include:

- Interlink FSR 402
- Tekscan FlexiForce A201
- Tekscan FlexiForce A301

The final selection will be based on:

- Force range
- Accuracy
- Repeatability
- Hysteresis
- Drift
- Cost
- Mechanical durability
- Ease of integration
- Calibration results

### Final Signal-Conditioning Architecture

Candidate approaches include:

- Voltage-divider circuits
- Operational-amplifier conditioning
- External analog-to-digital conversion
- Analog multiplexing

### Final Mechanical Construction

The final insole material, sensor encapsulation, attachment system, and electronics enclosure remain subject to prototype testing.
