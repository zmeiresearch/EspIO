# EspIO

This is a simple carrier board for ESP32-DevKitC (30-pin version) that implements a number of I/O channels:
- 8 Digital Inputs with protection and solder-time input range selection. Default values in schematic are for 12V input
  but this can easily be extended up to ~200V by proper resistor selection.
- 8 Digital Outputs, either buffered push-pull or Open Collector with on-board pull-ups.
- RS-485 serial interface


