## Hydrogreen Pollub
Hydros is a prototype of an innovative three-wheeled vehicle equipped with an electric drive and **hydrogen** fuel cell. The vehicle has been designed to minimize energy losses through its aerodynamic body, incredibly low mechanical resistance, and a highly efficient drive system. The construction is based on a monocoque made of modern lightweight composite materials.

The project's goal is to participate and podium in the Shell Eco Marathon competitions. The Shell Eco Marathon competitions take place annually on three continents - Europe, America, and Asia. Shell Eco-Marathon is an event that brings together the worlds of science, technology, and industry in a competition where vehicle efficiency in terms of energy consumption is paramount.

<div style="text-align:center">    
    <img src="/images/2023-10-15_16-55.png" />
</div>

## Current PCB projects
- [Energy flow unit PCB](https://github.com/HydrogreenPollub/energy-flow-pcb)
- [Fuel cell control unit PCB](https://github.com/HydrogreenPollub/fuel-cell-pcb)
- [Fuel cylinder unit PCB](https://github.com/HydrogreenPollub/fuel-cylinder-pcb)
- [Motor driver unit PCB](https://github.com/HydrogreenPollub/motor-driver-pcb)
- [Auxillary unit PCB](https://github.com/HydrogreenPollub/auxillary-pcb)
- Telemetry unit PCB
- Steering wheel unit PCB
- Hydrogen sensor PCB
- [PCB template](https://github.com/HydrogreenPollub/template-pcb)

## Current software projects
- [Master controller](https://github.com/HydrogreenPollub/master-controller-stm32) - STM32 MCU that governs all PCBs telling them what is the current situation of the vehicle
- [Telemetry](https://github.com/HydrogreenPollub/telemetry-esp32) - ESP32 MCU pushing data to our GIT stack (Grafana, InfluxDB, Telegraf)

## Legacy projects
- [Energy flow](https://github.com/HydrogreenPollub/energy-flow-stm32) - STM32 MCU taking care about energy flow from fuell cell and supercapacitor to motor controller
- [Steering wheel controller](https://github.com/HydrogreenPollub/steering-wheel-stm32) - STM32 MCU taking input from buttons and swiches on steering wheel, as well as providing data to HMI panel
- [Test vehicle controller](https://github.com/HydrogreenPollub/test-vehicle-esp32) - ESP32 MCU for a simple test vehicle control
