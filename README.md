# PCB_Design_Portfolio
This portfolio showcases my previouus work in PCB design and fabrication. it includes pictures of various PCBs  that i have designed and fabricated using Altium Designer.
my PCBs includes :
  1) RF circuit for LoRaWan wireless and Bluetooth Low Energie (BLE) Wireless data communication.
  2) designing highly constraint Power supply circuit to comply with the ATEX explosive zone safety requirement
  3) designing  dual band RF communication circuit for BLE 2.4Ghz and LoRaWa 868Mhz, using RF switch to switch between each wireless communication
  4) RF matching circuit  making sure that all RF line impedance match the antenna impedance (50 Ohm)
  5) Usage of blind via, buried via, Through-hole via
  6) multi-layer
     


# Overview
  I am a embedded systems engineer with big experience in PCBs design and fabricating  using ALTIUM DESIGNER. i have designed and fabricated numerous PCBs for various application, including Gas quality dectection sensor , pipeline Vanne positionning sensor, pipeline pressure detection sensor, pipeline leak detection sensor, pipeline Teemperature sensor.All these sensors use the same main board; only the sensor boards are interchangeable. Sensor data is transmitted wirelessly to the cloud via LoRaWAN. BLE is used for sensor configuration through a mobile app. I also have a very big experience in developing firmware for MCU using embedded C language.
  

# Projects

1) The design and the  fabrication of the sensaIO Main board (Mother board)  : This board will be use to power, process the data, and handle the wireless data tranfer for various sensor board (pressure sensor board, temperature sensorbaord, leak detection sensorboard, vanne positionning sensor board). The main board is a 6 layers PCB board that  includes a Flex layer. the Flex layer connect the ATEX certified power part of the circuit (where the pogo pin for sensorboard are located) to the MCU and RF part of the baord.

2) Design of the sensor board PCBs : vanne positionning sensor board, Temperature sensor board, pressure sensor board, leak sensor board. this sensor board will be connected to the main board discrib above.

3) Design of a Motion sensor using a dual core MCU from infineon (PSOC6 CORTEX M4 & M0) with an IMU (Inertial measurement unit) 

4) Design of a fine particule detection sensor :  The fine particle sensor operates by utilizing a laser and a DC motor. The motor draws particles into the sensor, and as these particles pass through the laser beam, they cause a deflection. This deflection is detected by a photodiode. A signal conditioning circuit processes the photodiode signal, which is then measured by the ADC (Analog-to-Digital Converter).The sensor's firmware processing is handled by an STM32 microcontroller integrated into the circuit board. This microcontroller enables efficient data handling and communication, ensuring accurate readings and processing of the sensor's outputs.

   
# PCBs images

  1) SensaIO Mainboard (mother board):
     
     Design on altium:
![sensorIO mainboard](https://github.com/user-attachments/assets/c96539c7-ef64-4480-998f-68014e5f7f76)

![mainboard_back](https://github.com/user-attachments/assets/0b107b20-1027-4987-be64-a30068d7b73c)

![mainboard_fab png](https://github.com/user-attachments/assets/4a841e9f-5400-49b0-8fd5-a912c3d0147c)

  Fabrication :

![maiboard_fab2](https://github.com/user-attachments/assets/11310026-bafb-44d3-bb64-b6eacbeb0735)
![integration](https://github.com/user-attachments/assets/1e975412-de37-4be0-8aaf-511f6675593d)

  Main board dual band (LoRaWa ,BLE) PCB antenna:
  
![antenna](https://github.com/user-attachments/assets/ee7ffafe-bf96-4d8d-86f4-a0ebd3281f10)

2) Sensor board PCB design:

   this board will be connected to the mainboard presented above.
   ![pcb_sesorboard](https://github.com/user-attachments/assets/fa47d935-0221-4ae1-ad5e-e744ee527b4e)
![sensorboard](https://github.com/user-attachments/assets/5e8d62bc-2fcf-4fdb-9534-56f2592cb5a7)
![sensorboard1](https://github.com/user-attachments/assets/ecc0d731-c4e6-4d23-9331-8984ae9457fb)

3) Vanne Positionnig PCB design

![Capture d’écran 2025-05-21 070355](https://github.com/user-attachments/assets/b0614702-c5d5-440a-b4aa-d6ae46267a60)

![sensaLite](https://github.com/user-attachments/assets/0ab60a65-057f-40d8-aa7b-aa8d3dc95e1a)
![sensaLite1](https://github.com/user-attachments/assets/45ca1883-35e0-4467-a11e-5f56c74f5ec1)
![sensaLite2](https://github.com/user-attachments/assets/a7b3b324-89a0-4a8c-8dc7-57f97e5cc46a)
![many_sensaLIte](https://github.com/user-attachments/assets/ca930b6f-516d-4d95-89c4-129624757779)

 usage of a super-capacitor for more current boost needed for LoRaWa transmission
 ![sensaLite0](https://github.com/user-attachments/assets/4ceee6ce-47e3-4c83-ad0f-bd0261f615e5)

4) Gas quality monitoring sensor:
   ![Gas](https://github.com/user-attachments/assets/1ad40198-d9ad-49ee-b6ab-0f20f9528bdd)
![gas_meca](https://github.com/user-attachments/assets/66c9c0ea-fa4a-4031-9ed3-f36f1251fdb2)

![gas1](https://github.com/user-attachments/assets/3f9319fc-4e0f-4d67-a121-ab9f457d9a62)
![gas_meca2](https://github.com/user-attachments/assets/d17932da-f556-467e-b2c1-a95d607bf178)


