# Design and Development of a Predictive Maintenance System for Large Industrial Machines using IoT

# IoT-Based Predictive Maintenance for CNC Machines

This repository contains the implementation of an IoT-based system for streaming sensor data and controlling instructions, designed to enhance decision-making processes and operational efficiency in industrial settings through Prognostics and Health Management (PHM). The project leverages the transformative power of IoT as a core component of Industry 4.0 to introduce predictive maintenance capabilities that identify anomalies proactively.

## Overview

Industry 4.0 has revolutionized industrial domains through technologies like blockchain, IoT, and AI. Among these, IoT plays a pivotal role in enabling efficient and autonomous operations across various sectors. This project focuses on the application of IoT in creating a sophisticated system for predictive maintenance of CNC machines, utilizing advanced machine learning models to predict operational anomalies based on sensor data.

## Project Components

### Hardware
- **Raspberry Pi 3 B+**: Serves as the central processing unit, handling sensor data integration and preprocessing.
- **CNC Machines**: Target machines for maintenance prediction.
- **Sensors**: Various sensors installed on CNC machines to monitor conditions like temperature and vibration.

### Software
- **Python Libraries**: Utilized for data processing and machine learning model development. Libraries include Pandas, NumPy, Scikit-Learn, TensorFlow, and Keras.
- **Machine Learning Models**: Ranging from Linear Regression to advanced models like ConvLSTM, which captures both temporal and spatial dependencies.

### System Architecture
- The system is structured hierarchically, ensuring scalability, modularity, and real-time communication capabilities.
- Integration focuses on seamless data flow from sensors through the Raspberry Pi to the predictive models.

## Predictive Models Performance

| Model             | Vib_X | Vib_Y | Vib_Z | Temp   |
| ----------------- | ----- | ----- | ----- | ------ |
| Linear Regression | 9.24  | 7.68  | 6.85  | 2.021  |
| RFG               | 13.26 | 8.97  | 7.82  | 2.25   |
| XGBoost           | 13.45 | 8.95  | 8.38  | 2.02   |
| GRU               | 13.65 | 9.13  | 7.31  | 2.018  |
| LSTM              | 13.21 | 9.71  | 6.43  | 2.023  |
| BiLSTM            | 13.18 | 9.1   | 8.51  | 2.0354 |
| StackedLSTM       | 14.55 | 9.83  | 6.7   | 2.0301 |
| ConvLSTM          | 7.44  | 7.43  | 9.67  | 2.065  |

## Key Features

- **Real-time Data Streaming**: Real-time monitoring and control for CNC machines, enhancing timely decision-making.
- **Predictive Maintenance**: Early anomaly detection to prevent costly downtimes.
- **Energy Efficiency**: Optimizing operations to reduce energy consumption and operational costs.

