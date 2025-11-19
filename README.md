# Patient Health Monitoring System 🩺❤️‍🩹

### *An IoT-based solution for real-time monitoring of vital health and environmental parameters using ESP32.*

This project developed an **IoT-based Patient Health Monitoring System** using an **ESP32 microcontroller** to track and display real-time health parameters and surrounding environmental conditions via a web interface.

***

## 🚀 Key Features

This system integrates multiple sensors and web technologies to provide comprehensive and accessible health data monitoring.

* **Real-Time Monitoring** ⏱️: Tracks and reports health data with periodic updates (optimized for 1-second intervals).
* **Vital Signs Tracking** ❤️: Monitors key patient health parameters, including **Heart Rate (BPM)** and **Blood Oxygen Levels (SpO2)**, using the MAX30100 sensor.
* **Body Temperature Measurement** 🌡️: Measures patient body temperature using the DS18B20 sensor.
* **Environmental Monitoring** 🏠: Measures ambient room temperature and humidity using the DHT11 sensor.
* **Web Interface Access** 🌐: Data is displayed on a user-friendly HTML web interface.
* **Remote Access** 📶: Enables live data monitoring on any device via Wi-Fi networking protocols.
* **Modular Design** 🧩: Built for scalability and potential integration with additional sensors or cloud services.

***

## 📥 Installation

Since this is an embedded project, installation involves setting up the **Arduino IDE** and configuring the **ESP32** board.

### Prerequisites

* **Arduino IDE** 💻
* **ESP32 Board Support** installed in the Arduino IDE.
* **Required Libraries** 📚: Libraries for MAX30100, DHT11, DS18B20, and ESP32 WebServer must be installed via the Arduino Library Manager.
* **Git** (for cloning the repository).

### Setup Guide

1.  **Clone the Repository** ⬇️
    Open your terminal and clone the project using Git:

    ```bash
    git clone [https://github.com/farooq-hassain/Patient-Health-Monitoring-System.git](https://github.com/farooq-hassain/Patient-Health-Monitoring-System.git)
    ```

2.  **Navigate to the Directory** 📂
    Change into the project folder:

    ```bash
    cd Patient-Health-Monitoring-System
    ```

3.  **Open the Sketch** ✍️
    Open the main project file (`HealthMonitoring.ino`) in the Arduino IDE.

4.  **Configure Wi-Fi Credentials** 🔑
    Edit the main sketch file to replace placeholder values with your local Wi-Fi network's SSID and Password.

5.  **Compile and Upload** ⚡
    Select the correct ESP32 board model and COM port in the Arduino IDE and click the Upload button to flash the code to the microcontroller.

***

## ▶️ Usage

After successfully uploading the code to the ESP32:

1.  **Open Serial Monitor:** Open the Serial Monitor in the Arduino IDE to view connection status.
2.  **Find IP Address:** The system will attempt to connect to Wi-Fi and print the assigned **IP Address** to the Serial Monitor.
3.  **Access Web Interface:** Open any web browser on the same Wi-Fi network and navigate to the displayed IP address (e.g., `http://192.168.1.100`).
4.  **Monitor Data:** The web page will display the real-time readings for BPM, SpO2, Body Temperature, Room Temperature, and Humidity.

***

## 🛠️ Technology Stack

This system is built using embedded programming principles for IoT applications:

| Technology | Percentage | Icon | Description |
| :--- | :--- | :--- | :--- |
| **Language** | 100.0% | ⚙️ | C++ (Arduino Sketch/ESP32 Framework) |
| **Microcontroller** | N/A | 🧠 | ESP32 (Used for processing and hosting the web server) |
| **Key Sensors** | N/A | 📡 | MAX30100, DHT11, DS18B20 |
| **Web Server** | N/A | 📶 | ESP32 WebServer libraries (for remote monitoring) |

***

## 🤝 Contributing

Contributions are always welcome! If you have suggestions for new sensors, UI improvements, or backend integration, please feel free to:

1.  **Fork** the repository. 🍴
2.  **Create** a new feature branch (`git checkout -b feature/CloudIntegration`). 🌿
3.  **Commit** your changes (`git commit -m 'Implement AWS IOT core integration'`). 📝
4.  **Push** to the branch (`git push origin feature/CloudIntegration`). 📤
5.  **Open** a Pull Request. ✨

***

## 📄 License

This project is open-source. Please check the repository for an explicit license file (like `LICENSE.md`) if available. In the absence of one, standard open-source conventions usually apply. ©️

***

## 👤 Author

**Farooq Hassain**
* [GitHub Profile](https://github.com/farooq-hassain) 🌐
