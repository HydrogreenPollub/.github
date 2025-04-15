# Hydrogreen Team
*Hydros* is a prototype of an innovative three-wheeled vehicle equipped with an electric drive and **hydrogen** fuel cell. The vehicle has been designed to minimize energy losses through its aerodynamic body, incredibly low mechanical resistance, and a highly efficient drive system. The construction is based on a monocoque made of modern lightweight composite materials.

The project's goal is to participate and podium in the Shell Eco Marathon competitions. The Shell Eco Marathon competitions take place annually on three continents - Europe, America, and Asia. Shell Eco-Marathon is an event that brings together the worlds of science, technology, and industry in a competition where vehicle efficiency in terms of energy consumption is paramount.

<div style="text-align:center">    
    <img src="/images/2023-10-15_16-55.png" />
</div>

## Current PCB projects
- [Master](https://github.com/HydrogreenPollub/master-pcb) - Master - measurment and safety unit PCB
- [FCCUv2](https://github.com/HydrogreenPollub/fccu_v2-pcb) - Fuel cell control unit v2 PCB
- [DCU](In progress) - Dual converter unit with fuel cell control PCB
- [FCM](In progress) - Fuel cell module - Current control and FC short PCB
- Telemetry unit PCB (*in future*)

## 2024 PCB projects
- [EFU](https://github.com/HydrogreenPollub/energy-flow-pcb) - Energy flow unit PCB
- [FCCU](https://github.com/HydrogreenPollub/fuel-cell-pcb) - Fuel cell control unit PCB
- [HCU](https://github.com/HydrogreenPollub/hydrogen-cylinder-pcb) - Hydrogen cylinder unit PCB
- [MCU](https://github.com/HydrogreenPollub/motor-driver-pcb) - Motor control unit PCB
- Telemetry unit PCB (*in future*)
- Steering wheel unit PCB (*in future*)
- Auxillary unit PCB (*in future*)
- [KiCAD symbol library](https://github.com/HydrogreenPollub/symbol-library-kicad)
- [PCB template](https://github.com/HydrogreenPollub/template-pcb)

## 2024 software projects
- [Energy flow unit_test](https://github.com/HydrogreenPollub/EFU_test_code)
- [Energy flow](https://github.com/HydrogreenPollub/energy-flow-esp32)
- [Fuel cell](https://github.com/HydrogreenPollub/fuel-cell-esp32)
- [Hydrogen cylinder](https://github.com/HydrogreenPollub/hydrogen-cylinder-esp32)
- [Motor control](https://github.com/HydrogreenPollub/motor-control-esp32)
- [Telemetry](https://github.com/HydrogreenPollub/telemetry-esp32) - ESP32 MCU sending data to our GIT stack (Grafana, InfluxDB, Telegraf)

#### ESP32 shared components
- [Connectivity](https://github.com/HydrogreenPollub/connectivity-component-esp32) - WiFi + MQTT
- [UART](https://github.com/HydrogreenPollub/uart-component-esp32) - UART over RS422 for steering wheel MCU
- [FOTA](https://github.com/HydrogreenPollub/ota-component-esp32) - Firmware over the air
- [IMU](https://github.com/HydrogreenPollub/connectivity-component-esp32) - Inertial measurement unit (9 axis)
- [GPS](https://github.com/HydrogreenPollub/gps-component-esp32)
- [SD card](https://github.com/HydrogreenPollub/sdcard-component-esp32)


## 2020-2022 Legacy software projects
- [Master](https://github.com/HydrogreenPollub/master-controller-stm32) - STM32 MCU that governs all PCBs telling them what is the current situation of the vehicle
- [Energy flow](https://github.com/HydrogreenPollub/energy-flow-stm32) - STM32 MCU taking care of energy flow from fuell cell and supercapacitor to motor controller
- [Steering wheel](https://github.com/HydrogreenPollub/steering-wheel-stm32) - STM32 MCU taking input from buttons and swiches on steering wheel, as well as providing data to HMI panel
- [Test vehicle](https://github.com/HydrogreenPollub/test-vehicle-esp32) - ESP32 MCU for a simple test vehicle control
