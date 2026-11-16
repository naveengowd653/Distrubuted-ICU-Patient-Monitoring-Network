### Distributed ICU Patient Monitoring Network

The Distributed ICU Patient Monitoring Network is an embedded system designed to collect and monitor patient-related sensor information using LPC2129 microcontrollers.

The system uses three sensors: a temperature sensor to measure temperature, an LDR sensor to measure light intensity, and an oxygen sensor to monitor oxygen-related parameters.

The system consists of two microcontroller nodes. Node A collects sensor data through the ADC and transmits the information to Node B using CAN (Controller Area Network) communication. Node B receives the sensor data and transfers it to a computer or local server using UART (Universal Asynchronous Receiver Transmitter) communication.

The computer displays the collected sensor information for monitoring purposes. A local server helps provide fast data access, local data control, and operation without depending entirely on an external internet connection.

The main objective of this project is to demonstrate distributed sensor monitoring and reliable communication between embedded systems using CAN and UART protocols.
