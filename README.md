# Selim Coşkun

**Embedded Systems Developer** · Electrical & Electronics Engineering, İzmir Kâtip Çelebi University

[![LinkedIn](https://img.shields.io/badge/LinkedIn-selimcoskun-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/selimcoskun)

I develop firmware for Arm Cortex-M microcontrollers, mostly STM32, working directly at register level from reference manuals and datasheets. My work covers peripheral drivers, communication protocols and real-time control loops, from bench prototypes to flight hardware.

---

### Focus areas

| Area | Experience |
|---|---|
| **Embedded firmware** | Bare-metal C on STM32 F1 / F4 / H7 · interrupts, timers, PWM, ADC, DMA · start-up code and linker scripts |
| **Communication** | SPI · I²C · UART · Ethernet (WIZnet W5500, TCP) · LLRP · MAVLink |
| **Control systems** | Discrete PID with anti-windup · sensor filtering · closed-loop motor control |
| **Software** | Rust · Python · Tauri desktop applications |

### Currently working on

- **Fixed-wing UAV flight controller** — STM32H7 firmware for Teknofest
- **Ground control station** — Rust + Tauri desktop application for the same UAV
- **Grand-strategy game** — written in Rust

*(Private repositories.)*

### Featured projects

| Project | Description | Key techniques |
|---|---|---|
| [W5500 LLRP RFID Reader](https://github.com/Selimc1/W5500_LLRP_RFID_Reader) | STM32F407 as an LLRP client for UHF RFID readers over Ethernet | W5500 SPI driver · TCP state machine with auto-reconnect · binary report parser · no HAL / RTOS / LwIP |
| [PID Motor Speed Control](https://github.com/Selimc1/PID_Motor_Speed_Control) | Closed-loop DC motor speed control | PI with anti-windup in a 100 ms SysTick loop · EXTI tachometer · TIM4 PWM · UART setpoint commands |
| [BMP280 Dual Sensor Driver](https://github.com/Selimc1/BMP280_Dual_Sensor_Driver) | Two BMP280 sensors read simultaneously over SPI and I²C | Register-level SPI / I²C drivers · bus timeouts · integer compensation |
| [Smart Greenhouse](https://github.com/Selimc1/Smart_Greenhouse_BareMetal) | STM32F103 greenhouse controller, simulated in Proteus | Single-wire DHT11 driver · humidity-driven fan PWM · EXTI door alarm |

Smaller bare-metal exercises: [ADC + UART monitoring](https://github.com/Selimc1/ADC_UART_Monitoring) · [1 kHz ADC step-response logger](https://github.com/Selimc1/BareMetal_Timer_ADC_UART) · [EXTI emergency stop](https://github.com/Selimc1/EXTI_EStop_Button) · [EXTI multi-sensor](https://github.com/Selimc1/EXTI_MultiSensor)

### Tools

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Arm](https://img.shields.io/badge/Arm_Cortex--M-0091BD?style=flat-square&logo=arm&logoColor=white)
![GCC](https://img.shields.io/badge/arm--none--eabi--gcc-555555?style=flat-square&logo=gnu&logoColor=white)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square)
![Proteus](https://img.shields.io/badge/Proteus-1f6feb?style=flat-square)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
