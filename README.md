# HEART-BEAT-SENSOR
In this project we have used Heart beat sensor module to detect Heart Beat. This sensor module contains an IR pair which actually detect heart beat from blood
# Heart Rate Monitor System

This repository contains the code and documentation for a real-time heartbeat monitoring system using Arduino and Python.

## Overview

The project utilizes an Arduino-based heartbeat sensor for measuring pulse rates. The system integrates both hardware and software components to provide accurate real-time monitoring of the user's pulse rate. 

## Components

- Arduino Uno or compatible microcontroller board
- Heartbeat sensor module
- Python environment
- Arduino IDE

## Setup

1. **Hardware Setup**: Connect the heartbeat sensor module to the Arduino Uno according to the provided schematics.

2. **Software Setup**:
   - Upload the Arduino code (`heartbeat_sensor.ino`) to the Arduino Uno using the Arduino IDE.
   - Install necessary Python libraries (`serial`, `matplotlib`, etc.) by running `pip install -r requirements.txt`.

3. **Running the System**:
   - Run the Python script (`heartbeat_monitor.py`) to start monitoring the pulse rate in real-time.

## Usage

1. Ensure that the Arduino is properly connected to the heartbeat sensor and the computer.
2. Run the Python script `heartbeat_monitor.py`.
3. The script will continuously read data from the Arduino and display the pulse rate graphically using matplotlib.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The project was inspired by the need for a simple yet effective heartbeat monitoring system.
- Thanks to the Arduino and Python communities for their valuable contributions.

## Author

Rishav Raj - [rishavrajsingh545@gmail.com]

Feel free to reach out with any questions or suggestions!
