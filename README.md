# port-scanner
## Python Port Scanner

A fast, multithreaded TCP port scanner built in Python. This tool allows you to scan a range of ports on a target host, and identify open ports.

## Basic Features

-Multithreaded scanning for speed
-Retry logic for handling timeouts
-Identifies common services on known ports
- Real-time progress tracking in terminal

## Project Structure

-main.py, which is the main port scanner script
-results.txt, which is Output file with open ports 
- results.json, which is Structured JSON results 
-README.md, which is the main project documentation
 
## Requirements

- Python 3.7+
- `colorama` library for colored output

Install dependencies:

```bash
pip install colorama

## How to Use
-Clone this repo or download main.py
-Open main.py and configure:
-target_host 
-Port range (port_start to port_end)
-Run the script:
python main.py
-View results in:
1)results.txt
2)results.json

## Sample Output
-Port 22 (SSH): SSH-2.0-Go
##Acknowledgements
-It is built on the basis of basic network tools and learning in Python.

