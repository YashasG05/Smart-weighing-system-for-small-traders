# Smart-weighing-system-for-small-traders
Say goodbye to manual stock tracking. This smart weighing scale automatically logs inventory additions and deductions for small retailers.

## Overview
The system uses a load cell and HX711 amplifier to measure the weight placed on a weighing platform. An ESP32 reads the measurement, handles button inputs, updates the stock calculations, and displays key values on a 0.96 Inch OLED SPI Display Module. A microSD card is intended to store transaction records.
The target use case is small-scale produce handling, where a user needs to weigh items and track stock without maintaining a separate handwritten ledger.

## Features
- Measure platform load using a 20kg load cell and an HX711 amplifier.
- Use physical Add, Subtract, and Reset buttons to update the stock record.
- Display the measured weight and relevant stock values on a 0.96 Inch OLED SPI Display.
- Append transaction records to a microSD card.
- Keep the hardware compact and powered from a regulated 5 V supply.
  
## Workflow
- Workflow: workflow/
  
## Firmware and Wiring
- Firmware: firmware/
- Circuit and pin map: hardware/
  
## Calibration
- Calibrate using one or more known reference weights across the intended measurement range.
- Remove and replace the same reference load and compare readings.
