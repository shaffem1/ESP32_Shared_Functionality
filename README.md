# ESP32 Sensor Data Collection and Upload

This repository contains shared code and functionalities for ESP32-WROOM-32 modules equipped with weather and environmental sensors. The ESP32 devices collect sensor data and upload it to a SQL server for later analysis and display.

## Overview

The ESP32-WROOM-32 modules in this project are configured to collect data from various weather and environmental sensors, including temperature, humidity, air quality, and more. The collected data is then uploaded to a SQL server, where it can be stored, analyzed, and visualized.

## Features

- **Modular Codebase:** The code is organized into modular components, allowing for easy customization and extension.
- **Wi-Fi Connectivity:** Built-in functionality for connecting to Wi-Fi networks, ensuring seamless communication with the SQL server.
- **Sensor Integration:** Support for a variety of weather and environmental sensors, enabling comprehensive data collection.
- **SQL Server Upload:** Data collected by the ESP32 devices is uploaded to a SQL server for storage and further processing.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Configure the Wi-Fi credentials and SQL server settings in the appropriate files (e.g., `config.h`).
3. Upload the code to your ESP32-WROOM-32 modules using the Arduino IDE or your preferred development environment.
4. Verify that the devices are successfully connecting to Wi-Fi and uploading data to the SQL server.

## Contributing

Contributions to this project are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors of the ESP32 Arduino Core and related libraries for their invaluable work.
- This project was inspired by the need for reliable weather and environmental monitoring solutions.
