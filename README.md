# network-traffic-analyzer
A Python script for capturing and analyzing network traffic to detect anomalies

## Project Overview

The **Network Traffic Analyzer** is a Python-based tool that captures and analyzes network traffic using the **Scapy** and **PyShark** libraries. It identifies and displays anomalies in network data such as unexpected IP addresses, ports, or suspicious traffic patterns. This project is useful for network monitoring, security analysis, and troubleshooting.

## Requirements

- **Python 3.x** (Make sure Python is installed on your machine)
- **Libraries**:
  - `scapy`: For packet capture and manipulation.
  - `pyshark`: For detailed packet analysis using Wireshark.
  
  Install required libraries:
  ```bash
  pip install scapy pyshark
