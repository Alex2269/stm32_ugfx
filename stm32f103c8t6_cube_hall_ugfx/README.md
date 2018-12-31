 
``` cpp

stm32f103C8T6 minimal board + ILI9488 8 bit + ugfx

for remaping pins see: ILI9488.c 
func ILI9488WriteData8
func ILI9488ReadData

connect display:
display data port:
GPIOA first 8 pins for data
A0 A1 A2 A3 A4 A5 A6 A7 STM32 GPIOA
D0 D1 D2 D3 D4 D5 D6 D7 display pins

for remaping pins see: ILI9488.c func ILI9488WriteData8
shift for accurate distribution, pins tft shield
A0 A1 A2 A3 A4 A5 A6 A7 GPIO stm32
D2 D3 D4 D5 D6 D7 D0 D1 display pins

display control port:
B4 B5 B6 B7 B8  GPIOB
RD WR RS CS RST display port

run stm32cubeMx and generate  project
upload ugfx:
sh ugfx_build_sh
make
make flash
```
