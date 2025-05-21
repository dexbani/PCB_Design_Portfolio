# PCB_Design_Portfolio
This portfolio showcases my previouus work in PCB design and fabrication. it includes pictures of various PCBs  that i have designed and fabricated using Altium Designer.
my PCBs includes skills:
  1) RF circuit for LoRaWan wireless and Bluetooth Low Energie (BLE) Wireless data communication.
  2) designing highly constraint Power supply circuit to comply with the ATEX explosive zone safety requirement
  3) designing  dual band RF communication circuit for BLE 2.4Ghz and LoRaWa 868Mhz, using RF switch to switch between each wireless communication
  4) RF matching circuit  making sure that all RF line impedance match the antenna impedance (50Ohm)
  5) Usage of highly sophisticated IMU sensor (MEMS technology) : Accelorematers (BHI160), Magnetometers,...


# Overview
  I am a embedded systems engineer with big experience in PCBs design and fabricating  using ALTIUM DESIGNER. i have designed and fabricated numerous PCBs for various application, including Gas quality dectection sensor , pipeline Vanne positionning sensor, pipeline pressure detection sensor, pipeline leak detection sensor, pipeline Teemperature sensor.All these sensors use the same main board; only the sensor boards are interchangeable. Sensor data is transmitted wirelessly to the cloud via LoRaWAN. BLE is used for sensor configuration through a mobile app.
  

# Projects

1) The design and the  fabrication of the sensaIO Main board (Mother board)  : This board will be use to power, process the data, and handle the wireless data tranfer for various sensor board (pressure sensor board, temperature sensorbaord, leak detection sensorboard, vanne positionning sensor board). The main board is a 6 layers PCB board that  includes a Flex layer. the Flex layer connect the ATEX certified power part of the circuit (where the pogo pin for sensorboard are located) to the MCU and RF part of the baord.

2) Design of the sensor board PCBs : vanne positionning sensor board, Temperature sensor board, pressure sensor board, leak sensor board. this sensor board will be connected to the main board discrib above.

3) Design of a Motion sensor using a dual core MCU from infineon (PSOC6 CORTEX M4 & M0) with an IMU (Inertial measurement unit) 

4) Design of a fine particule detection sensor :  The fine particle sensor operates by utilizing a laser and a DC motor. The motor draws particles into the sensor, and as these particles pass through the laser beam, they cause a deflection. This deflection is detected by a photodiode. A signal conditioning circuit processes the photodiode signal, which is then measured by the ADC (Analog-to-Digital Converter).The sensor's firmware processing is handled by an STM32 microcontroller integrated into the circuit board. This microcontroller enables efficient data handling and communication, ensuring accurate readings and processing of the sensor's outputs.

   
# PCBs images

  1) SensaIO Mainboard (mother board): 
![sensorIO mainboard](https://github.com/user-attachments/assets/c96539c7-ef64-4480-998f-68014e5f7f76)

![mainboard_back](https://github.com/user-attachments/assets/0b107b20-1027-4987-be64-a30068d7b73c)

![mainboard_fab png](https://github.com/user-attachments/assets/4a841e9f-5400-49b0-8fd5-a912c3d0147c)




![Capture d’écran 2025-05-21 070355](https://github.com/user-attachments/assets/1bb101b2-8062-4bce-b65a-f0384674bdc9)
