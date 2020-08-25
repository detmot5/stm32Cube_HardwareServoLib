# stm32Cube_HardwareServoLib
Simple lib for controlling servo with hardware PWM using stmCubeMX

## Timer Parameters
* Prescaler(PSC) = SystemCoreClock / (SystemCoreClock / 1000000) - 1 (to get 1MHz)
* Period(ARR) = 19999 (to get 50Hz)



