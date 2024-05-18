Hello,

here you can find the Printer.cfg for an Kobra 2 Plus in combination with an Manta M8P v2.0

At the moment there is only a untested Version without errors!
Test at your own risk!!!
Updates follows.

Also you can get Print files to Print your own New Housing for the Hardware. Please lookup with your connections and configuration. This is an early Version that is not 100% correct!

| Part | Pinout Label | Manta M8P v2.0 | Pin / Pin Assignment |
|----|----|----|----|
| Probe / ABL Sensor | E-CON: LEVEL | Probe PD13 | If you use BlTouch: (PD13/Sensor) \[PD12/Servo) |
| Acceleration Sensor Printhead = X E-CON | E-CON: MOSI E-CON: MISO E-CON: SCLK E-CON: CS E-CON: 5V | SPI: SPI_MOSI SPI: SPI_MISO SPI: SPI_SCK SPI: SPI_CS SPI: 5V SPI_GND| PA7 PA6 PA5 PE10 (SPI: 5V) (SPI: GND)|
| Acceleration Sensor Bed = Y ACC-SENSOR | ACC-SENSOR: MOSI ACC-SENSOR: MISO ACC-SENSOR: SCLK ACC-SENSOR: CS ACC-SENSOR: 5V ACC-SENSOR: GND | EXP2: SPI1_MOSI EXP2: SPI1_MISO EXP2: SPI1_SCK EXP2: BTN_EN2 Motor: 5V Motor → Motor - | PA7 PA6 PA5 PE11 (Motor: 5V) (Motor → GND -) |
| Printhead's 24V main | E-CON: 24V | Motor Fan → 24V + | (Motor Fan → 24V +) |
| Printhead's GND main | E-CON: GND | Motor Fan → 24V - | (Motor Fan → 24V -) |
| Part Cooling Fan | E-CON: F0 | FAN1 | FAN0 PF7 |
| Heatsink Cooling Fan | E-CON: F1 | FAN2 | FAN1 PF9 |
| Thermistor Hotend | E-CON: T0 | TH1 | PC1 |
| Cartridge Heater | E-CON: H+ / H- (3x) | HE0+ / HE0- | HE0 PA0 |
| Thermistor Bed | T1/GND | TB1 | PC0 |
| Heater Bed | HOTBED + / - | H-BED + / - | BED OUT PF5 |
| PE / Chassis GND | E-/X-CON: CHASSIS GND | PE-Wire PSU | (PE-Wire PSU) |
| Filament Runout Sensor | X-CON: FILAMENT/GND | MT_DET1 !PF2/GND | !PF2 M3-Stop |
| X Limit Switch | X-CON: X LIMIT/GND | X !PF4/GND | !PF4 M1-Stop |
| Y Limit Switch | Y-CON: LIMIT/GND | Y !PF3/GND | !PF3 M2-Stop |
| Mainboard Cooling Fan | MB-FAN + / - | FAN2 → 24V + / - | (FAN2 PF6 → 24V + / -) |
| Z-Offset Sensor | CALIBRATION S/GND | Z+ PD13/14/GND | ^PD13/14 |
| Extruder Motor | E-CON: A1/A2/B1/B2 | E0-MOTOR: 1A/1B/2A/2B | step: PB5 / dir: PB3 / enable: !PB6 / uart: PD5 |
| X-Axis Motor | X-CON: A1/A2/B1/B2 | X-MOTOR: 1A/1B/2A/2B | step: PE6 / dir: PE5 / enable: !PC14 / uart: PC13 |
