# QualityTool

## Overview

The "QualityTool" project is a comprehensive solution for data quality management and control in Internet of Things (IoT) environments. Specifically designed for applications like aquaculture, this repository introduces an event-driven software architecture, leveraging the Python programming language.

## Key Features

1. **Event-Driven Architecture:** The repository implements an event-driven architecture to handle real-time data collection, processing, and analysis generated by IoT sensors.

2. **Modular Layers:** Organized into distinct modules, the project includes components for event generation (producers), event processing (processors), and event consumption (consumers).

3. **Efficient Persistence:** The persistence layer uses a dedicated database to store events and quality metrics, ensuring durability and query capability.

4. **Flexible Integration:** Integration modules allow seamless connection with other systems and services, featuring adapters for external APIs and connectors for databases.

5. **Robust Security:** It includes authentication and authorization features to ensure system security, controlling access to data and events.

6. **Monitoring and Logs:** A monitoring layer provides tools to trace event flow, analyze system performance, and log information for auditing.

7. **Centralized Configuration:** A configuration module enables easy adjustment of project settings to meet specific environment needs.

## Usage Instructions

1. Clone the repository.
2. Configure and start the different modules according to your specific requirements.
3. Personalize settings and adapt adapters as needed.
4. Monitor and review logs to ensure system integrity.

### Prerequisites
- Python 3.x
- Kafka broker running (localhost:9092)

## Dataset
The dataset used in this project was obtained from Kaggle: [Sensor-Based Aquaponics Fish Pond Datasets](https://www.kaggle.com/datasets/ogbuokiriblessing/sensor-based-aquaponics-fish-pond-datasets).

### Dataset Structure
The dataset includes sensor readings for parameters such as temperature, turbidity, ammonia, nitrate, pH, dissolved oxygen (DO), and geographic coordinates. The data is stored in a CSV file located at `QualityTool/data/sensor_readings.csv`.

## Academic Origin

This project was created during the Master's program in Information Engineering at the Federal University of ABC (UFABC). It represents a culmination of academic research and practical implementation, addressing challenges in data quality management within IoT environments.

## Contributions

Feel free to contribute to this open-source project. Your contributions are valuable for further research, collaboration, and learning.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

