BreatheLogic
--
Overview
-
BreatheLogic is an indoor air quality monitoring project focused on collecting accurate measurements of carbon dioxide (CO₂), temperature, and relative humidity in indoor environments. The project emphasizes reliable sensor integration, repeatable data collection, and clear documentation to support academic analysis and data sharing.

The final objective of BreatheLogic is to prepare a well-documented dataset suitable for publication in the Data in Brief journal, enabling reuse by other researchers studying indoor environmental conditions.

Project Goals
-
Collect accurate indoor CO₂, temperature, and humidity data

Validate sensor performance through controlled testing

Establish a reproducible data collection methodology

Produce clean, well-documented datasets for academic use

Hardware Stack
-
Arduino – Used during early development and testing for simplicity and rapid validation of sensor readings.

SCD41 Sensor – Measures CO₂ concentration (ppm), temperature (°C), and relative humidity (%). Chosen for its accuracy and suitability for indoor air quality research.

ESP32 – Provides processing power and wireless capabilities, enabling future scalability and extended deployments.

System Design
-
The SCD41 sensor collects environmental measurements at defined intervals. During development, data is output locally to verify accuracy and system stability. The ESP32 is used as the primary controller, laying the groundwork for future wireless data transmission while keeping the current focus on data quality rather than real-time visualization.

Data Collection
-
Data is collected in indoor environments under consistent conditions to ensure reliability. Measurements are stored locally in a structured format for later analysis. At this stage of the project:

No backend, database, or dashboard is implemented

Data collection prioritizes accuracy, consistency, and documentation

Metadata is recorded to support transparency and reproducibility

Planned Outcome
-
The finalized dataset, along with detailed documentation of the hardware setup and data collection methodology, will be prepared for submission to the Data in Brief journal. The published data is intended to support future research in indoor air quality and environmental monitoring.
