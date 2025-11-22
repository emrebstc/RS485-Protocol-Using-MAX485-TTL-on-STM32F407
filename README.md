STM32 ------ MAX485 #1
______________________

PA2 (USART2_TX)  >    DI

PB0    >     DE & RE Combined (Short Circuit)

5V      >       VCC

GND     >      GND

__________________________
MAX485 #1 ------ MAX485 #2
__________________________
A     >     A

B     >     B

GND   >     GND

______________________
MAX485 #2 ------ STM32
______________________
RO     >    PA3 (USART2_RX)

DE & RE   >   GND

VCC    >   5V

GND    >   GND
