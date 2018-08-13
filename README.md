# LabViewPrograms

## Probe Station

### Keithley2400_SR830_4Probe_Resistance_Measurement

A program do a series 4 probe resistance measurement of a device, with gate dependence.
It measures a loop of data, traversing from INITIAL to HIGH to LOW to INITIAL, and the relevant STEP_SIZE.
The Keithley SourceMeter provide the gate voltage, and measure current flow between the gate and sample.
The Standford Research Lock In Amplifier provides an AC current through the sample and measures the relevant changes between probes.