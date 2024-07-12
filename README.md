# IoT-Based Weather Monitoring System

## Overview
The IoT-Based Weather Monitoring System is designed to collect real-time weather data using various sensors. The system measures light intensity, temperature, humidity, atmospheric pressure, and rainfall, displaying the data locally on an LCD screen and remotely via the internet. This system is useful for applications in agriculture, urban planning, and disaster management.

## Features
- Real-time data collection
- Remote data access via the internet
- Local display on an LCD screen
- Utilizes multiple sensors (LDR, BMP180, DHT11, Rain Sensor)
- User-friendly web-based dashboard for remote monitoring

## Components
- **LDR Sensor**: Measures light intensity
- **BMP180 Sensor**: Measures atmospheric pressure
- **DHT11 Sensor**: Measures temperature and humidity
- **Rain Sensor**: Measures rainfall
- **Nodemcu (ESP8266)**: Microcontroller for data processing and transmission
- **LCD Display**: For local data display

## Setup Instructions
1. **Hardware Setup**:
   - Connect the sensors to the Nodemcu (ESP8266) as per the pin configuration tables provided.
   - Ensure the sensors are properly calibrated and connected.

2. **Software Setup**:
   - Install the necessary libraries for Nodemcu (ESP8266) in your Arduino IDE.
   - Upload the provided code to the Nodemcu (ESP8266).
   - Set up the Blynk platform for remote data access and create a dashboard.

3. **Data Transmission**:
   - Connect the Nodemcu (ESP8266) to your Wi-Fi network.
   - Ensure data is being transmitted to the Blynk platform and displayed on the web-based dashboard.

## Pin Configuration
- **DHT11 Sensor**:
  - VCC to VIN
  - OUT to D3
  - GND to GND
- **BMP180 Sensor**:
  - SDA to D2
  - SCL to D1
  - GND to GND
  - VCC to VIN
- **Rain Sensor**:
  - A0 to A0
  - GND to GND
  - VCC to VIN
- **LDR Sensor**:
  - VCC to VIN
  - GND to GND
  - D0 to D0
- **LCD Display**:
  - VCC to VIN
  - GND to GND
  - SDA to D2
  - SCL to D1

## Usage
1. Power the system using a USB cable.
2. Monitor the local weather conditions on the LCD display.
3. Access real-time weather data remotely via the Blynk web-based dashboard.
4. Use the data for various applications such as agriculture monitoring, urban planning, and disaster management.

## Future Improvements
- Integration with additional sensors for more comprehensive weather data.
- Enhanced data analytics for better prediction and insights.
- Mobile app development for improved user access.

## Contributors
- Avik Halder
- Hrithik Das
- Tasnim Mahmud Fahim
- Maliha Rahman Mitu
- Jakaria Saikat Dhrobo

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to modify this template to better suit the specifics of your project.
