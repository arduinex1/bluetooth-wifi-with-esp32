Required Components –
 
ESP32, 2x NRF24L1 + PA + LNA, 18650 Li-Ion battery, battery holder, battery charger
 
HSPI = ESP32
SCK = 14, 
MISO = 12, 
MOSI = 13, 
CSN = 15 , 
CE = 16
 
VSPI = ESP32
SCK = 18, 
MISO =19, 
MOSI = 23 ,
CS =21 ,
CE = 22
 
 
Nrf24l ki jagah nrf24l01 + PA + LNA ka use krna hai. Isme antena hota hai, isiliye iski long range hoti hai.
 
 E01-2G4M27D aur E01-ML01DP5 dono hi long-range SPI-based modules hain, lekin range aur power output me kaafi difference hai:
🔐 ESP32-Based IR Sensor Security System with Blynk IoT Cloud
Yeh smart security system ESP32 aur IR sensor ka use karke design kiya gaya hai, jise Blynk IoT Cloud se remotely monitor kiya ja sakta hai. System motion detect karte hi Blynk app par instant alert bhejta hai, ensuring real-time surveillance.
📦 Hardware Configuration:
Power Supply: Battery ka positive terminal ESP32 ke 3V3 pin se connected hai, aur negative terminal GND pin se.
IR Sensor Trigger Pin: Sensor ka OUT pin ESP32 ke GPIO 4 se connected hai.
Sensor Type: Passive Infrared (PIR) sensor for motion detection.
📲 Cloud Integration:
Blynk IoT Cloud ke through live status monitoring aur notifications enable kiye gaye hain.
App interface se system ko remotely arm/disarm bhi kiya ja sakta hai.
⚡ Use Case: Ideal for home entrances, storerooms, ya kisi bhi jagah jahan motion detection se security enhance ki ja sakti hai.
