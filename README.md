Python PID Simulator:
A two-wheel differential-drive robot was simulated with a virtual five-sensor IR bar.
The reference track contains a straight section, an S-curve, another straight section,
a smooth 90-degree turn, and a final straight section. P-only and PID controllers
were compared using the same initial conditions and robot model.

Simulation settings:
- Time step: 0.02 s
- Simulation duration: 32.0 s
- Wheel separation: 150 mm
- Base speed: 0.16 m/s
- Maximum wheel speed: 0.30 m/s
- Sensor spacing: 15 mm
- Sensor offsets: -30, -15, 0, +15, +30 mm
- Line width: 20 mm

Measured RMS distance from reference track:
- P-only: 0.0398 m
- PID: 0.0129 m
