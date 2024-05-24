# AoA-Embedded-Systems

AoA-Embedded-Systems is an open-source project focused on developing a low-cost and energy-efficient embedded system to determine the Angle of Arrival (AoA) of sound using a multidirectional microphone array. This project uses the TM4C123GH6PM microcontroller, integrating advanced digital signal processing techniques to analyze audio signals in real-time.

## Project Overview

This system is designed to solve the AoA problem efficiently in environments where resources are limited. By utilizing a set of precisely calibrated microphones and sophisticated cross-correlation algorithms, the project aims to accurately calculate the source direction of incoming sounds.

## Features

- **Multidirectional Microphone Array**: Utilizes multiple microphones to capture sound from various directions.
- **Real-time Processing**: Employs the TM4C123GH6PM microcontroller for high-performance audio signal processing.
- **Cross-correlation Algorithms**: Analyzes time differences in sound wave arrivals to determine the AoA.
- **Low Power Consumption**: Optimized for environments with limited power resources.

## Hardware Components

- **TM4C123GH6PM Microcontroller**: Manages digital signal processing and I/O operations.
- **Microphones and Conditioning Circuits**: Captures and amplifies sound signals.
- **Amplifiers and Filters**: Enhances signal quality and reduces noise.

## Software Components

- **Embedded C Code**: Contains all the logic for signal processing and system operation.
- **Command-line Interface**: Allows users to configure and control the system in real-time.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/AoA-Embedded-Systems.git
   ```
2. Navigate to the project directory:
   ```
   cd AoA-Embedded-Systems
   ```
3. Follow the hardware setup instructions provided in the `docs` folder.

## Usage

Start the system by running the embedded software uploaded to the microcontroller, and use the command-line interface to adjust settings and monitor outputs.

## Contributing

Contributions are welcome! Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to all contributors who have invested their time in improving this project.
- Project inspired by challenges in real-time audio processing in resource-constrained environments.
