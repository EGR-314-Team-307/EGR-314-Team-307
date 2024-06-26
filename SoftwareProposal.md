# [Back to Main Page](./index.md)
---
# Software Implementation
---
### Process and Flow
The flow through the software code needed to be developed once the components were selected. To do this, the team identified the different coding requirements for the sensors and the microcontroller. The sensors require I2C for communicating with the microcontroller, and the motor driver requires SPI. When the system powers on, the system needs to initialize with the appropriate setup for the two different types of serial communication. Once the communication methods have been initialized, the sensors will be enabled, then the motor, and then the ESP32 module. At this point, the system will start reading the output of the sensors while comparing those outputs to baseline values to determine if the prototype is facing a fire or not. If the sensor values are determined to indicate a fire, the system state will be changed, and the motor will be told to move whilst still reading the sensor outputs. Once the greatest value output by the sensors has been reached, the motor will be told to stop. If the sensors continue to indicate a fire, the motor will stay at that position; if the sensors indicate the fire has been extinguished, the motor will move back to its original position and the state of the system will be changed back to monitoring for a fire. Each time there is a system state change, the system will output an update via the ESP32 module. The following figures represent the logic flow of the system:
## Main Control Loop
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/e8977080-a0ea-4625-8662-15950e93150b)
## Initialize System Loop
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/3c740c02-d770-4db7-ab2a-244abe82b3cd)
## Refresh Display Loop
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/33398161-3451-4edb-936a-da8b52467630)
## Temperature Sensor
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/044100e1-f5a2-42b4-85fa-c809a926ba0c)
## Light Sensor
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/2b5f275a-1eef-4787-a6f6-808dd52d7363)
## Motor System
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/14ac5112-8339-4841-be09-6d4fa16d9104)
# System Verification Table
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/a5b6ba05-7569-430c-86ef-e3e6c060e5ed)
# Project Code
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/147283789/5b128129-450a-44db-8d67-d008b4f0bae8)
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/147283789/0fcf3438-9703-4b06-9b18-b589faea62fd)
This code defines specific addresses for pressure and temperature sensors. It initializes the UART, I2C, and SPI communication interfaces. Within the main loop, it continuously reads data from a temperature sensor via I2C sends it over UART, and then enables the motor driver based on the received values. Additionally, it exchanges data with an SPI device, specifically sending and receiving bytes in a loop and printing the results. The main loop runs indefinitely, continuously reading sensor data and sending it over UART while exchanging SPI data.
