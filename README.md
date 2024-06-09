# Temperature and Humidity Monitoring with DHT Sensor Module

#### Project Overview

This project demonstrates how to measure temperature and humidity using a DHT (Digital Humidity and Temperature) sensor module with an Arduino Uno. The DHT sensor provides accurate readings of temperature and humidity, which are then displayed on the serial monitor.

#### Components Needed

1. **Arduino Uno**
2. **DHT Sensor Module (DHT11 or DHT22)**
3. **Jumper Wires**

### Block Diagram


#### Pin Connections

- **DHT Sensor Module:**
  - Signal: Connect to Arduino digital pin 2
  - VCC: Connect to Arduino 5V
  - GND: Connect to Arduino GND

#### Instructions

1. **Set Up the Circuit:**
   - Connect the signal pin of the DHT sensor module to Arduino digital pin 2.
   - Connect the VCC pin of the sensor module to Arduino 5V.
   - Connect the GND pin of the sensor module to Arduino GND.

2. **Initialize the System:**
   - Begin serial communication at a baud rate of 9600 in the setup function.
   - Initialize the DHT sensor with the appropriate pin and type (DHT11 or DHT22).

3. **Read Sensor Values:**
   - Read temperature and humidity values from the sensor using the `readTemperature()` and `readHumidity()` functions, respectively.
   - The readings are returned as floats representing temperature in Celsius and humidity in percentage.

4. **Display Readings:**
   - Check if the readings are valid using `isnan()` function to avoid displaying incorrect values.
   - Print the temperature and humidity readings to the serial monitor with appropriate units.

5. **Repeat Measurement:**
   - Add a delay of 2 seconds between measurements to avoid rapid readings.

#### Applications

- **Indoor Climate Monitoring:** Monitor temperature and humidity levels indoors for comfort and health.
- **Greenhouse Control:** Use the sensor for monitoring and controlling temperature and humidity in a greenhouse environment.
- **Weather Stations:** Integrate the sensor into weather station projects for local weather monitoring.

#### Notes

- Ensure proper wiring and placement of the sensor for accurate readings.
- Calibrate the sensor if necessary for accurate measurements in your environment.

---

🌐 [projectslearner.com](https://projectslearner.com)  
📧 [projectslearner@gmail.com](mailto:projectslearner@gmail.com)  
📸 [Instagram](https://www.instagram.com/projectslearner/)  
📘 [Facebook](https://www.facebook.com/projectslearner)  
▶️ [YouTube](https://www.youtube.com/@ProjectsLearner)  
📘 [LinkedIn](https://www.linkedin.com/in/projectslearner)  

Made for you with ❣️ from ProjectsLearner