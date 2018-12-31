

``` cpp

it is necessary for inclusion of illumination of the display:
display light it is connected to B0 GPIOB
palClearPad(GPIOB, GPIOB_PIN0);


base code:
stm32f407-base.tar.xz
driver display:
STM32F407-OSC-ILI9486-drv


example:
extract stm32f407-base.tar.xz
extract  STM32F407-ILI9486-driver-vers2.tar.xz
cd stm32f407-base/STM32F407-OSC-ILI9486

make
make flash

```
