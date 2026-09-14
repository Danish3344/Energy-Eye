# How Energy Eye Works

Energy Eye is organized as a transmitter-receiver energy monitoring system.

1. The sensing hardware measures electrical parameters from the monitored load.
2. The transmitter microcontroller reads and processes the measurements.
3. The processed data is sent over the wireless communication link.
4. The receiver obtains the transmitted data.
5. The receiver exposes the received information through the serial interface for monitoring and debugging.

## Data Path

`Load → Sensor → TX Microcontroller → Wireless Link → RX Microcontroller → Serial Monitor`

The exact measurement calculations and packet format will be documented with the final TX/RX firmware.
