# Multi-Room Communication System using Arduino
Authors - Avi Bhatnagar, Rimsha Rizvi & Shehriar Burney

## Description:
The Multi-Room Communication System is a wireless communication system designed to facilitate real-time monitoring and emergency communication between three Arduino devices in environments where temperature, light, and emergency response are crucial, such as in farming. The system utilizes various sensors, LCDs, LEDs, and RF transceivers to transmit and receive environmental data and emergency codes.

## Features:
- Real-time monitoring of temperature, light, and humidity
- Wireless communication between three Arduino devices
- Display of sender's name and emergency codes on LCD
- User-friendly interface with button control
- LED indicator for transmit/receive mode

## Subsystems:
### 1. Sensor Subsystem (handled by Shehriar Burney)
- Input: 
  - DHT11 sensor to measure temperature and humidity
  - Photoresistor to measure light levels
- Output: 
  - LCD to output sensor values on the other Arduinos

### 2. Communication Subsystem (handled by Avi Bhatnagar)
- Input: 
  - Push button to toggle between transmitting and receiving modes
- Output: 
  - LED to indicate the current mode (lit up for transmit, off for receive)

### 3. LCD Display and Button Control Subsystem (handled by Rimsha Rizvi)
- Input: 
  - Potentiometer to select pre-set emergency codes/messages
- Output: 
  - LCD to show messages from other Arduinos and the selected emergency code

## References:
- Admin. (2022, August 22). Simple phone: Call & SMS using GSM module & Arduino. How To Electronics. Retrieved March 6, 2023, from [Link](https://how2electronics.com/call-sms-using-gsm-module-arduino/)
- Lambert, Graham. (2021, November 17). Wireless Communication between Two Arduinos. Circuit Basics. Retrieved March 6, 2023, from [Link](https://www.circuitbasics.com/wireless-communication-between-two-arduinos/)

## Statement of Original Work:
Our project is unique as it combines LCDs and the concept of pre-set emergency codes with the use of a potentiometer, allowing for quick and efficient communication during emergencies. The use of an LED to indicate the mode (transmit or receive) adds a layer of user-friendliness to the system. This project stands out as a reliable, versatile, and user-friendly communication system that can be utilized in various settings, including farming, to monitor environmental factors and respond to emergencies promptly.

## Copyright and Plagiarism Notice
All content in this repository, including code, documentation, and other materials, is the property of Avi Bhatnagar, Rimsha Rizvi, and Shehriar Burney.
Plagiarism is a serious offense and is strictly prohibited. You may not use, copy, or submit this work as your own. Any plagiarism or unauthorized use will be reported to the relevant academic or professional authorities.
If you would like to use this work for educational or other non-commercial purposes, don't hesitate to get in touch with the authors for permission.


