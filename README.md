<h1 align="center">Hi, I'm Selim Coşkun 👋</h1>
<p align="center">
  <b>Embedded systems developer · Electrical &amp; Electronics Engineering, İzmir Kâtip Çelebi University</b><br/>
  Bare-metal STM32 firmware · UAV flight control · Rust
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/selimcoskun"><img src="https://img.shields.io/badge/LinkedIn-selimcoskun-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

### About me

- 🔧 I write **register-level firmware for STM32** (F1 / F4 / H7): drivers for SPI, I²C, UART, timers, ADC, EXTI and Ethernet, written from the reference manual and datasheets.
- ✈️ For **Teknofest** I work on a fixed-wing **flight controller** (STM32H7) and a **ground control station** (Rust + Tauri).
- 🎮 In my spare time I'm building a **grand-strategy game in Rust**.

### Tech stack

<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black" alt="C"/>
  <img src="https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white" alt="Rust"/>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/STM32-03234B?logo=stmicroelectronics&logoColor=white" alt="STM32"/>
  <img src="https://img.shields.io/badge/Arm%20Cortex--M-0091BD?logo=arm&logoColor=white" alt="Arm Cortex-M"/>
  <img src="https://img.shields.io/badge/Tauri-24C8DB?logo=tauri&logoColor=white" alt="Tauri"/>
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git"/>
</p>

### Featured projects

| Project | What it does | Highlights |
|---|---|---|
| [**W5500 LLRP RFID Reader**](https://github.com/Selimc1/W5500_LLRP_RFID_Reader) | STM32F407 as an LLRP client for UHF RFID readers over Ethernet | Own W5500 SPI driver, TCP state machine with reconnect, binary report parser — no HAL / RTOS / LwIP |
| [**PID Motor Speed Control**](https://github.com/Selimc1/PID_Motor_Speed_Control) | Closed-loop DC motor speed control | PI with anti-windup in SysTick ISR, EXTI tachometer, TIM4 PWM, live setpoint over UART |
| [**BMP280 Dual Sensor Driver**](https://github.com/Selimc1/BMP280_Dual_Sensor_Driver) | Two BMP280 sensors read at once, one on SPI and one on I²C | Register-level SPI and I²C drivers with timeouts, integer compensation |
| [**Smart Greenhouse**](https://github.com/Selimc1/Smart_Greenhouse_BareMetal) | STM32F103 greenhouse controller (Proteus) | Hand-written DHT11 driver, humidity-based fan PWM, EXTI door alarm |

More bare-metal STM32 exercises: [ADC + UART monitoring](https://github.com/Selimc1/ADC_UART_Monitoring) · [Timer + ADC + UART](https://github.com/Selimc1/BareMetal_Timer_ADC_UART) · [EXTI emergency stop](https://github.com/Selimc1/EXTI_EStop_Button) · [EXTI multi-sensor](https://github.com/Selimc1/EXTI_MultiSensor)
