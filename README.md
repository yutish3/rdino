# rdino
rp-2040 development board in the shape of arduino uno r3 so it supports its hats and also has esp32 for wifi and bluetooth and 5x5 grid of neo pixel leds

it has dual microcontroller so all the less important repetative tasks can be off loaded to esp32 and main work can be done by the rp 2040 chip with extra 16M bit memory
and it can be used foor any project like lfr robot , micromouse , rc car etc

<img src="Screenshot (1535).png" alt="PCB Layout 1" width="600">

<img src="Screenshot (1530).png" alt="PCB Layout 1" width="600">

<img src="Screenshot (1531).png" alt="PCB Layout 2" width="600">

<img src="Screenshot (1532).png" alt="DRC Errors" width="600">

<img src="Screenshot (1533).png" alt="Silkscreen Design" width="600">

<img src="Screenshot (1534).png" alt="3D View" width="600">


| Component | Purpose | Qty | Cost (USD) | Distributor |
| --- | --- | --- | --- | --- |
| RP2040 (QFN-56) | Main Microcontroller | 1 | ₹81.00 | ROBU / MOUSER / offline |
| ESP32-C3-WROOM-02 | Wi-Fi / BLE Module | 1 | ₹175 | ROBU / MOUSER / offline |
| W25Q128JVS (SOIC-8) | 128Mbit Flash Memory | 1 | ₹70 | ROBU / MOUSER / offline |
| AP2112K-3.3 (SOT-23-5) | 3.3V LDO Voltage Regulator | 1 | ₹24 | ROBU / MOUSER / offline |
| WS2812B-2020 (PLCC4) | Addressable RGB LEDs (D1-D24, D27, D29, D31) | 25 | ₹200 | ROBU / MOUSER / offline |
| Standard LED (0603) | Status Indicator (D26) | 1 | ₹13 | ROBU / MOUSER / offline |
| USB-C Receptacle 14-Pin | Power and Data Interface (J1) | 1 | ₹45 | ROBU / MOUSER / offline |
| 1x04 Pin Header/Socket | I/O Expansion / Programming (J6) | 1 | ₹15 | ROBU / MOUSER / offline |
| 1x06 Pin Header/Socket | I/O Expansion (J2) | 1 | ₹15 | ROBU / MOUSER / offline |
| 1x08 Pin Header/Socket | I/O Expansion (J4, J5) | 2 | ₹30 | ROBU / MOUSER / offline |
| 1x10 Pin Header/Socket | I/O Expansion (J3) | 1 | ₹15 | ROBU / MOUSER / offline |
| Push Button (KMR2) | Reset / User Input (SW1, SW2) | 2 | ₹10 | ROBU / MOUSER / offline |
| 1.1kΩ Resistor (0603) | Current Limiting / Pull-up | 1 | ₹1 | ROBU / MOUSER / offline |
| 4.7kΩ Resistor (0603) | I2C / General Pull-up | 2 | ₹2 | ROBU / MOUSER / offline |
| 10kΩ Resistor (0603) | Pull-up / Pull-down | 3 | ₹3 | ROBU / MOUSER / offline |
| 5.1kΩ Resistor (0603) | USB-C CC line Pull-down | 2 | ₹2 | ROBU / MOUSER / offline |
| 1μF Capacitor (0603) | Decoupling / Bypass | 6 | ₹6 | ROBU / MOUSER / offline |
| 27pF Capacitor (0603) | Crystal Load Capacitors | 2 | ₹2 | ROBU / MOUSER / offline |
| Crystal 3225 (4-Pin) | Clock Source for RP2040 (Y1) | 1 | ₹30 | ROBU / MOUSER / offline |
| PCB | Component Mounting | 1 | ₹180 | JLCPCB / PCBWay |

Total Estimated Cost: ₹919
