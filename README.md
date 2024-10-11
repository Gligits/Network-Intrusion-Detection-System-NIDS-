# Network-Intrusion-Detection-System-NIDS
This project involves developing a simple Network Intrusion Detection System (NIDS) using Python. 
The NIDS monitors network traffic in real time, detects anomalies or attacks (port scanning, flooding, etc.), and logs suspicious events into a database for further analysis.

## Main Features
- Real-time network packet capture and analysis
- Attack detection based on simple signatures (port scanning, flooding, etc.)
- Logging events into an SQLite database
- Using pipes for communication between processes (capture and analysis)
- Simulating network attacks to test detection

## Prerequisites
Before starting make sure you have installed the following:

Python 3.x: Check if Python is installed using python --version.
Python Libraries: Install the necessary libraries with the following command

`pip install scapy SQLAlchemy`

## Project Steps
###  Network Traffic Capture
Use scapy to capture network packets and extract key information such as IP addresses, ports, and protocols.

### Intrusion Detection
Implement rules to detect attacks such as port scanning and flooding... These rules can be based on signatures or anomalies in network traffic.

### Logging to a Database
Store detected events in an SQLite database for analysis. Each event should contain information such as the source IP, type of attack, and timestamp.

### Using Pipes
Separate the packet capture and analysis into different processes for better code organization by using pipes for communication between them.

### Simulating Network Attacks
To test the NIDS we are gonna simulate network attacks such as flooding or port scanning using sockets. This will allow us to verify that the detection mechanisms are functioning correctly.

# License
This project is licensed under the MIT License.






