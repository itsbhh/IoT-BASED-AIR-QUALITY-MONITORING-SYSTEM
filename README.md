#  IoT-Based Air Quality Monitoring System

### Virtual Simulation Using Google Colab and Python

## About the Project

This project is a virtual simulation of an IoT-Based Air Quality Monitoring System.

The main objective is to demonstrate how air pollution can be monitored using two sensors:

- **MQ-135:** Used to represent gas-related pollution readings.
- **PMS5003:** Used to represent particulate matter readings such as PM1.0, PM2.5 and PM10.

The project is developed using Python in Google Colab. It generates sample sensor readings, processes the data and displays the results through an interactive dashboard.

## Project Objectives

- To understand the working concept of an air quality monitoring system.
- To simulate MQ-135 and PMS5003 sensor readings.
- To display air quality readings through gauges.
- To visualize pollution levels using graphs.
- To classify air quality as GOOD, MODERATE or POOR.
- To allow users to enter their own sensor readings and check the results.

## Technologies Used

| Technology | Purpose |
|---|---|
| Google Colab | Online Python environment |
| Python | Programming language |
| NumPy | Generate sample sensor readings |
| Pandas | Store and manage sensor data |
| Plotly | Interactive gauges and graphs |
| ipywidgets | Interactive input controls |

## Sensors Used

### 1. MQ-135 Gas Sensor

The MQ-135 is a gas sensor that responds to various gases present in the air.

In this simulation, it is represented by a raw ADC reading between 0 and 4095.

### 2. PMS5003 Particulate Matter Sensor

The PMS5003 measures particulate matter in the air.

The simulation represents three types of particulate matter:

- PM1.0
- PM2.5
- PM10

## Working Principle

1. Python generates sample readings representing the sensors.
2. The readings are processed using Python.
3. The program classifies air quality based on PM2.5 values.
4. Sensor readings are displayed through interactive gauges.
5. Pollution history is displayed using graphs.
6. Users can enter their own sensor readings.
7. The dashboard updates according to the entered values.

## Dashboard Features

The dashboard includes:

- MQ-135 sensor gauge
- PM1.0 reading gauge
- PM2.5 reading gauge
- PM10 reading gauge
- Air quality status
- Pollution history graph
- Sensor data table
- Manual sensor data entry option

## Sensor Input Ranges

Users can enter their own readings using the following simulation ranges:

| Sensor | Input Range | Example |
|---|---|---|
| MQ-135 | 0–4095 | 2300 |
| PM1.0 | 0–100 µg/m³ | 25 |
| PM2.5 | 0–250 µg/m³ | 65 |
| PM10 | 0–400 µg/m³ | 150 |

**Note:** These are input ranges selected for this virtual simulation, not the full physical measurement specifications of the sensors.

## Air Quality Classification

The simulation uses simplified PM2.5 thresholds:

| PM2.5 Value | Air Quality Status |
|---|---|
| 0–15 µg/m³ | GOOD |
| Above 15–35 µg/m³ | MODERATE |
| Above 35 µg/m³ | POOR |

These are demonstration categories, not official AQI calculations.

## How to Run the Project

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Copy the project Python code into a code cell.
4. Run the cell.
5. View the generated sensor gauges and graphs.
6. Check the sensor readings in the data table.
7. At the end, choose whether to enter your own sensor readings.

### Manual Data Entry

The program asks:

`Do you want to add your own data and check? (yes/no)`

If the user enters `yes`, the program requests:

- MQ-135 reading
- PM1.0 reading
- PM2.5 reading
- PM10 reading

After validating the inputs, the dashboard updates with the entered readings.

## Project Scope and Limitations

This project currently represents only the **Google Colab virtual simulation**.

- No physical ESP32 is connected.
- No actual MQ-135 sensor is connected.
- No actual PMS5003 sensor is connected.
- Sensor readings are generated using Python or entered manually.
- Wi-Fi and MQTT communication are not implemented.
- The MQ-135 value is a simulated raw ADC reading, not a gas concentration in ppm.
- The dashboard demonstrates the software functionality of the proposed monitoring system.

## Future Scope

The project can be extended by:

- Connecting actual MQ-135 and PMS5003 sensors.
- Integrating an ESP32 microcontroller.
- Transmitting real-time sensor data through Wi-Fi.
- Implementing MQTT communication.
- Adding automatic pollution alerts.
- Storing historical air quality readings.

## Conclusion

This project demonstrates a virtual IoT-based air quality monitoring system using Python and Google Colab.

It provides a simple way to understand sensor data processing, pollution classification and dashboard visualization.

The simulation serves as a foundation for future implementation using physical sensors and an ESP32 microcontroller.

---

**Project Type:** Virtual Simulation  
**Platform:** Google Colab  
**Programming Language:** Python  
**Sensors Represented:** MQ-135 and PMS5003  
**Data Source:** Generated sample data and manual user input



<img width="1363" height="768" alt="image" src="https://github.com/user-attachments/assets/ec6bded9-0bc9-4709-a691-3ee6cb4d13ee" />
<img width="1350" height="768" alt="image" src="https://github.com/user-attachments/assets/8bf2b049-069e-4f84-93ea-8dd6d7fabcc1" />
<img width="1356" height="768" alt="image" src="https://github.com/user-attachments/assets/3e2ff2c5-e0f1-4533-9b28-617380dfbe2b" />
<img width="1360" height="704" alt="image" src="https://github.com/user-attachments/assets/1656b543-e9b5-4c7e-84f1-42363ae10596" />

