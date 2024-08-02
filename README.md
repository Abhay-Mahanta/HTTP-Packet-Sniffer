# HTTP Packet Sniffing Tool

This Python script captures HTTP traffic on a specified network interface to monitor and extract visited URLs and potential usernames and passwords from HTTP requests. It uses the Scapy library to sniff and process network packets in real-time.

## Features

- **URL Monitoring**: Captures and displays URLs visited by users on the network.
- **Credential Extraction**: Searches for and highlights potential usernames and passwords in HTTP requests.

## Usage

The script accepts one argument:
- `-i` or `--iface`: The name of the network interface to sniff on.

## Requirements

- Python 3.x
- Scapy library

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Abhay-Mahanta/HTTP-Packet-Sniffer
   cd http-sniffer
2. Install the required Python library:
   ```sh
   pip install scapy
## Installation

- To run the HTTP sniffing tool, use the following command:
   ```sh
   sudo python http_sniffer.py -i <interface>

## Important Note
This tool is intended for educational and ethical purposes only. Unauthorized use of this tool on networks where you do not have permission is illegal and unethical. Use it responsibly and only on networks you own or have explicit permission to test.
