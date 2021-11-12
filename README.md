# Floating Water Quality Station

This project proposes the hardware design and the firmware of a floating station for measuring the water quality of lakes.

Water quality measurements are transmitted over a LoRaWAN network (TTN or Chirpstack).

The main MCU board is the [Seeedstudio LoRa E5 Dev](https://wiki.seeedstudio.com/LoRa_E5_Dev_Board/) with the STM32 WL55JC.

The firmware is based on [RIOT OS](https://riot-os.org/).

The water sensors are listed [here](./sensors.md)

[Github repositories](https://github.com/waterqualitystation)

## Version 2022
Coming soon
* MCU: STM32WL55 ([Nucleo](https://www.st.com/en/evaluation-tools/nucleo-wl55jc.html), [Seeedstudio](https://wiki.seeedstudio.com/LoRa_E5_Dev_Board/))
* Sensors:
  * Air: Temperature, Humidity, Pressure
  * Water: Temperature
  * [Water quality sensors](./sensors.md)
  * Acceleration, Gyroscope
  * GPS
* Firmware : C or MicroPython on RIOT OS
