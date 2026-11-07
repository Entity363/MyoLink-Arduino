Implementation of the [MyoLink paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9762559) Analog Front End to work with an Arduino UNO shield. Made in EasyEDA.
<img width="2048" height="1536" alt="image" src="https://github.com/user-attachments/assets/f37263e3-59b6-49bd-8dc3-d6f796b996ec" />

Current issues:
- Arduino ADC has too low of a resolution
- Buffers on electrode heads are not needed
- Amplification of AD8295 is too low
- Poor USB Isolation

Coming Soon:
- Full amplification with 8 channels, ADS1298 24bit ADC, STM32F411 chip and ADuM4160 isolator
- Better ENIG flex pads
