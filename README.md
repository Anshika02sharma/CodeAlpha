# CodeAlpha
Project 1
# Network Sniffer
A simple and customizable network packet sniffer built using Scapy in Python. This tool allows you to capture network packets and display their details, such as source and destination IP addresses, ports, and protocols, in real-time.

## Features
- Capture packets from any available network interface.
- Display packet details such as IP addresses, ports, and protocol types.
- Support for TCP, UDP, and ICMP packets.
- Easy-to-use command-line interface with real-time packet monitoring.
- Customizable packet filtering based on protocol or port.

## Prerequisites
### Python 3: 
Ensure Python 3 is installed on your system.
### Scapy: 
A powerful Python library used for network packet manipulation and analysis.

## Installation
### Install Python 3
Python 3 can be installed from the official website or using a package manager:

sudo apt-get install python3

## Usage
### Running the Script
Clone this repository to your local machine:

git clone https://github.com/Anshika02sharma/network-sniffer.git

Navigate to the project directory: cd network-sniffer

# Run the script with administrator/root privileges:
On Windows, use the Command Prompt as Administrator: python network_sniffer.py

On Linux/Mac, use sudo: sudo python3 network_sniffer.py

## Example Output
After running the script, you will see real-time captured packet details:

Capturing packets on interface: Wi-Fi | Filter: tcp

Press Ctrl+C to stop....

TCP: 192.168.1.100:5678 -> 172.217.160.46:443

TCP: 192.168.1.101:1234 -> 93.184.216.34:80

## Contributing
Feel free to fork this repository, open issues, or submit pull requests for enhancements and bug fixes.
## Acknowledgments
- This project utilizes the Scapy library for packet sniffing and manipulation.
- Special thanks to the Python community for providing excellent resources and documentation.







