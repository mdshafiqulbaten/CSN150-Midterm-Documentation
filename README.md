# Cybersecurity 150 midterm Spring 2024

## Sending a massage by whatsApp
ESP32 Massage sending Program

## Purpose
Create an ESP32 project using the ESP32CAM.

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Link to Documentation Followed
- [Messaging with WhatsApp](https://randomnerdtutorials.com/esp32-send-messages-whatsapp/)

## Steps I followed
1. I have added the given phone number in my whatsApp.
2. then I have written massage in the  massage option
3. then I have  written the phone number and the API key that I have received from the whatsApp bot
4. connected the ESP-32 Cam with the computer by the cable
5. upload that
6. reset the button in the ESP32
7. check in the monitor
8. and I got massage in whatsApp describing "Hello from ESP 32!"

## Problems
When I was connecting the ESP32 with the cable , it was not finding the device. We checked and later on found that the cable was normal charging cable not the data cable. We changed the cable to the data cable and It started working.
