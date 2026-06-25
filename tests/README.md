# Firmware Tests

## Dependencies
- [arm-none-eabi-gcc](https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads)
- [CMake](https://cmake.org/download/)

## GPIO Test
### Procedure
1. Connect channel 1 of the logic analyzer to TP22 and GND of the logic
analyzer to TP1.
2. Begin reading with Saleae Logic 2.
3. Observe a square wave with period of 1 seconds

## PWM Test
### Procedure
1. Connect channel 1 of the logic analyzer to TP10 and GND of the logic
analyzer to TP1.
2. Begin reading with Saleae Logic 2.
3. Observe a continuously decreasing duty cycle starting at 100% and going 
down the 0%. Once at 0% it'll loop back to 100% duty cycle and repeat.

## I2C Test
### Procedure
1. Connect

## ADC (BEMF)

## USB-C
Send and receive message.