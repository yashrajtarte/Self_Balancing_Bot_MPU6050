# Self_Balancing_Bot_MPU6050
Build a self-balancing robot using an MPU6050 accelerometer and PID control. Code and docs by ElectroElite Squad. Use and modify freely.
This repository contains the code and documentation for building a self-balancing robot using an MPU6050 accelerometer and PID control. The project aims to create a robot that can maintain balance and controlled movement using sensor data.

## Features

- Self-balancing functionality using MPU6050 accelerometer
- PID control algorithm for precise motor output adjustment
- Integration with IR functionality for communication with other devices (work in progress)

## Getting Started

### Prerequisites

- Arduino IDE installed
- MPU6050 library
- PID library

### Hardware Setup

1. Connect the MPU6050 accelerometer to the Arduino board following the pinout specified in the code.
2. Connect the motors and motor driver according to your specific hardware configuration.

### Software Setup

1. Clone this repository or download the code files.
2. Open the `SelfBalancing.ino` file in the Arduino IDE.
3. Install the required libraries (`MPU6050` and `PID`) if not already installed.
4. Select the correct board and port from the Arduino IDE's "Tools" menu.
5. Upload the code to the Arduino board.

### Usage

1. Power on the self-balancing bot.
2. The bot will initialize and calibrate the accelerometer.
3. Once calibrated, the bot will enter the self-balancing mode.
4. Monitor the serial monitor for debugging information and adjust the PID coefficients (`Kp`, `Ki`, `Kd`) for optimal performance.
5. Experiment with different setpoints and observe how the bot maintains balance.

## Contributing

Contributions to this project are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to acknowledge the following resources and libraries used in this project:

- MPU6050 library by jrowberg: https://github.com/jrowberg/i2cdevlib/tree/master/Arduino/MPU6050
- PID library by Brett Beauregard: https://github.com/br3ttb/Arduino-PID-Library

