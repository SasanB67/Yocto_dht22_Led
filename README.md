Description: Reads temperature from a DHT22 sensor through the Linux kernel. The LED turns ON when the temperature exceeds 20°C and OFF otherwise. 

Required HW: Raspberrypi3-64

Pin connections and wiring:
- 3.3V (physical pin 1): Connect to DHT22 VCC.
- GPIO4 (physical pin 7): Example DATA connection, provided the kernel device-tree configuration assigns the DHT22 driver to GPIO4.
- GND (physical pin 6): Connect to DHT22 GND.
- GPIO17 (physical pin 11): Connect to a 220–330 Ω resistor, then to the LED's positive leg.
- GND (physical pin 6): Connect to the LED's negative leg.
