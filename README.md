# network-monitoring-tool
Python tool for scanning network devices and detecting open ports with automated logging.

Features
Scan multiple IP addresses
Detect active (UP/DOWN) hosts using ping
Scan common ports (22, 80, 443)
Save results to a file for analysis
How to Run
Clone the repository or download the files
Open a terminal in the project folder
Run the script:
python network_scanner.py
Enter IP addresses when prompted (comma-separated)
Example

Input:
127.0.0.1, 8.8.8.8

Output:

Displays host status (UP/DOWN)
Shows open/closed ports
Saves results to scan_results.txt
Technologies Used
Python
Socket programming
OS command execution
Future Improvements
Add a graphical user interface (GUI)
Expand port scanning range
Improve performance with multithreading
