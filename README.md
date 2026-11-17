# ESP32 DHT11 Temperature and Humidity Sensor

A simple electronics project using an ESP32 development board and a DHT11 sensor to measure temperature and relative humidity.

## 🛠️ Components

- ESP32 Development Board
- DHT11 Temperature and Humidity Sensor
- Breadboard
- Jumper Wires (Male-to-Male)
- USB Cable

## 🔌 Wiring

| DHT11 Sensor | ESP32 |
|---|---|
| S (DATA) | GPIO 4 (D4) |
| + (VCC) | 3V3 |
| - (GND) | GND |

## 📚 Libraries

This project uses the following Arduino library:

- [DHT Sensor Library by Adafruit](https://github.com/adafruit/DHT-sensor-library)

You may also need:

- [Adafruit Unified Sensor](https://github.com/adafruit/Adafruit_Sensor)

## 💻 How It Works

The ESP32 reads data from the DHT11 sensor every 3 seconds.

The program measures:
- Temperature in Celsius (°C).
- Relative humidity in percent (%).

The results are printed to the Serial Monitor at a baud rate of 115200.

## 🚀 Getting Started

1. Connect the DHT11 sensor to the ESP32 according to the wiring table.
2. Install the required Arduino libraries.
3. Open the project in Arduino IDE.
4. Select your ESP32 board and the correct COM port.
5. Upload the code.
6. Open the Serial Monitor and set the baud rate to **115200**.

## 📟 Example Output

```text
Temp: 24.00 C Humidity: 45.00 %
Temp: 24.00 C Humidity: 46.00 %
Temp: 24.00 C Humidity: 45.00 %
```

*The values above are examples. Actual readings depend on the environment.*

## 🎯 Project Goals

- Learn the basics of ESP32 programming.
- Understand how digital sensors work.
- Read temperature and humidity data.
- Practice working with Arduino IDE and electronic components.

## 📝 Future Improvements

- Display sensor readings on an OLED screen.
- Add a web interface using ESP32 Wi-Fi.
- Send sensor data to a server.
- Build a simple temperature and humidity monitoring system.

---

**Platform:** ESP32  
**Sensor:** DHT11  
**Programming Language:** C++  
**IDE:** Arduino IDE
