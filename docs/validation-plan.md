# Validation Plan

## 1. Sensor Characterization

Each force sensor will be evaluated independently.

Measurements will include:

- Raw ADC output
- Voltage
- Estimated force
- Sensitivity
- Linearity
- Hysteresis
- Drift
- Repeatability
- Sensor-to-sensor variation

## 2. Calibration

Each sensor will be calibrated using known reference loads.

For each load:

- Apply the load consistently.
- Record the sensor output.
- Repeat the measurement at least three times.
- Calculate the mean and standard deviation.
- Fit an appropriate calibration equation.
- Record the regression equation and R² value.

Target:

- R² ≥ 0.95
- Coefficient of variation ≤10%

## 3. Multi-Sensor Testing

The complete system will be tested to confirm:

- All eight channels can be read.
- Channels remain distinguishable.
- Simultaneous loading does not create unacceptable interference.
- The sampling rate remains at or above 20 Hz.

## 4. Bluetooth Testing

Three independent 30-minute trials will be conducted.

Record:

- Expected packet count
- Received packet count
- Dropped packet count
- Packet-loss percentage
- Average sampling frequency
- Connection interruptions

Target:

- Packet loss below 5%

## 5. Force Accuracy Testing

The calibrated prototype will be compared against known reference loads.

Calculate:

- Absolute error
- Percentage error
- Mean absolute error
- Mean absolute percentage error

Target:

- MAPE ≤15%

## 6. Mechanical Testing

Evaluate:

- Sensor movement
- Wiring strain
- Enclosure integrity
- Attachment stability
- Comfort
- Visible wear
- Performance after repeated use

## 7. Clinical Usability Evaluation

Evaluate:

- Ease of application
- Ease of removal
- Comfort
- Dashboard clarity
- Visibility of visual alerts
- Audibility of alarm
- Clinical usefulness
- Overall user satisfaction
