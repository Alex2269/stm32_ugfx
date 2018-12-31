

``` cpp

it is necessary for inclusion of illumination of the display:
display light it is connected to B0 GPIOB
palClearPad(GPIOB, GPIOB_PIN0);


base code:
stm32f407-osc.tar.xz
driver display:
STM32F407-OSC-ILI9486-drv


example:
extraxct stm32f407-osc.tar.xz
extract  STM32F407-OSC-ILI9486-drv-2.tar.xz
cd stm32f407-osc/STM32F407-OSC-ILI9486
make
make flash

```
