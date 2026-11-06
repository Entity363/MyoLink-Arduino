Implementation of the MyoLink paper(2022) Analog Front End to work with an Arduino UNO shield.

Current issues:
- Arduino ADC has too low of a resolution
- Buffers on electrode heads are not needed
- Amplification of AD8295 is too low
- Poor USB Isolation

Coming Soon:
- Full amplification with 8 channels, ADS1298 24bit ADC, STM32F411 chip and ADuM4160 isolator
- Better ENIG flex pads
