# Hybrid Smart Energy Control and Redistribution System

This project aims to develop a **cost-effective energy management solution** that optimizes the distribution of energy from multiple sources (solar panels, grid power, and battery storage) while ensuring efficient load management and sustainability. The system is enhanced with **AI-driven capabilities** to prioritize energy usage, reduce costs, and minimize carbon emissions, making it ideal for urban households and small businesses in outage-prone regions like Bangladesh.

---

## Key Features

1. **Load Prioritization**:
   - Classifies loads into **High**, **Normal**, and **Low** priority to ensure critical needs (e.g., medical equipment) are met during power shortages.

2. **Automatic Source Switching**:
   - Seamlessly transitions between **solar**, **battery**, and **grid power** based on availability and demand.

<!-- 3. **AI-Driven Optimization**:
   - Uses **predictive analytics** to forecast energy availability and consumption patterns, maximizing renewable energy utilization.
   - Implements machine learning algorithms to adapt to user behavior and environmental conditions (e.g., sunlight intensity, grid availability). -->

3. **Cost Efficiency**:
   - Prioritizes solar energy over grid power to lower energy costs for users.

4. **Sustainability and Reliability**:
   - Reduces carbon emissions by maximizing renewable energy usage.
   - Ensures a stable power supply in regions with frequent outages.

---

## Hardware Components

- **Power Sources**:
  - Solar Panel (40W, 12V)
  - Rechargeable Battery (12V, 7Ah)
  - Grid Power (External Supply)
- **Control Unit**:
  - Arduino Uno (ATmega328P, 5V, 16 MHz)
- **Sensors and Actuators**:
  - Voltage Sensor (0-25V)
  - Current Sensor (ACS712, 5A)
  - Light-Dependent Resistor (LDR)
  - 4-Channel Relay Module (5V, 10A/channel)
- **User Interface**:
  - 16x2 LCD Display
  - Push Buttons (4 units)

---

## Software Integration

- **Arduino IDE**:
  - Programs the Arduino Uno in **C/C++** to handle real-time control logic, sensor data processing, and relay activation.
<!-- - **AI-Driven Algorithms**:
  - Implements predictive analytics to forecast energy availability and consumption.
  - Uses machine learning models to optimize energy distribution and adapt to user behavior. -->
- **Embedded Control Logic**:
  - Manages load prioritization and automatic source switching based on real-time data.

---

## Repository Structure
<!-- /hybrid-smart-energy-system
│
├── /hardware
│ ├── circuit_diagram.pdf # Circuit schematic
│ ├── component_list.md # List of hardware components
│ └── wiring_guide.md # Step-by-step wiring instructions
│
├── /software
│ ├── arduino_code.ino # Main Arduino sketch
│ ├── ai_algorithms.md # Explanation of AI-driven logic
│ ├── control_algorithms.md # Explanation of control logic
│ └── sensor_calibration.md # Calibration guide for sensors
│
├── /docs
│ ├── project_overview.md # Detailed project description
│ ├── user_manual.md # User guide for operating the system
│ └── future_enhancements.md # Ideas for future improvements
│
├── LICENSE # License file
└── README.md # Overview of the project (this file)-->

---

## How to Use

1. **Hardware Setup**:
   -  <!-- Follow the wiring guide in `/hardware/wiring_guide.md` to connect all components.-->
2. **Software Setup**:
   - <!-- Upload the Arduino sketch (`/software/arduino_code.ino`) to the Arduino Uno. -->
   -  <!-- Calibrate the sensors using the guide in `/software/sensor_calibration.md`. -->
3. **Operation**:
   - <!-- Use the **LCD Display** and **Push Buttons** to monitor and control the system. -->
   - <!-- Refer to `/docs/user_manual.md` for detailed instructions. -->

---

## Future Enhancements

- Integrate IoT capabilities for remote monitoring and control.
- Expand machine learning models for more accurate energy forecasting.
- Scale the system to support larger applications, such as community microgrids.

---

## Contributing

Contributions are welcome! Please contact us for guidelines on how to contribute to this project.

---

## Contact

For questions or feedback, feel free to reach out:
- **Email**: [shanjida.alam2020@gmail.com, haiderirtifa@gamil.com, jucse29.402@gmail.com]

