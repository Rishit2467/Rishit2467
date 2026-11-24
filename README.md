# Rishit Paliwal

B.Tech Electronics and Communication Engineering, IIIT Naya Raipur (2025-2029)
Focused on embedded systems and firmware engineering.

Building real-time firmware on STM32 — bare-metal drivers,
FreeRTOS task scheduling, and closed-loop control.


## Projects

bootloader

A two-stage bare-metal/HAL firmware update system for the STM32 Nucleo-F103RB (ARM Cortex-M3, 128 KB Flash) supporting over-UART firmware flashing, IEEE 802.3 CRC32 integrity verification, vector table relocation (SCB->VTOR), and fault-tolerant boot fallback—requiring no external hardware beyond the onboard ST-LINK Virtual COM Port.


stm32-freertos-realtime-imu

FreeRTOS multi-task system on STM32F103RB with PID controller, exponential
low-pass filter on joystick ADC, ISR-to-task notifications, IWDG supervision,
and cycle-accurate WCET profiling via DWT->CYCCNT. JSON telemetry over USART2.

UART-snake-game

Fully functional Snake game on STM32F103RB using bare-metal C.
I2C LCD driver (PCF8574), 12-bit ADC joystick with software deadzone,
TIM2 hardware interrupt game loop, interrupt-driven UART commands,
4-state FSM, and I2C address auto-detection at startup.


## Skills

Languages: C, Embedded C, Python, C++ , Verilog (basic)

Microcontrollers: STM32 Nucleo-F103RB (Cortex-M3), Arduino Uno, Raspberry Pi 5

Interfaces: GPIO, UART, I2C, SPI, ADC, PWM, Timer Interrupts

RTOS: FreeRTOS (tasks, queues, mutexes, task notifications, watchdog)

Tools: PlatformIO, STM32CubeIDE, Git, Linux


## Currently

Open to research internships in embedded systems and firmware engineering
for Summer 2027. Particularly interested in real-time systems, IoT, and
low-level firmware development.


## Contact

rishit25101@iiitnr.edu.in 
https://www.linkedin.com/in/rishit-paliwal-276226334
