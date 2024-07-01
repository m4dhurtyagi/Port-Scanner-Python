# Port Scanner

This script is a basic TCP port scanner implemented in Python. It scans ports on a specified target host (either provided as a hostname or IP address). It reports which ports are open by attempting to establish a TCP connection to each port. The script handles various scenarios such as incorrect command-line arguments, network errors, and user interruptions gracefully. It uses socket programming to create TCP connections and perform port scanning operations efficiently.

## Installation

> git clone https://github.com/m4dhurtyagi/Port-Scanner-Python.git

> cd Port-Scanner-Python

> python PortScanner.py Hostname

### Example
> python PortScanner.py google.com

> python PortScanner.py 142.250.77.206
