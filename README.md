# portscanner
Basic TCP/UDP Port Scanner in Linux C
Network Port Scanner (Linux C)

# Overview
A simple network port scanner built in C as part of the Sasken Summer Internship 2025.
It scans TCP/UDP ports for a given IP and logs results to a file.
# Features
TCP/UDP port scanning
Multi-threaded with pthreads
Command-line arguments for IP & port range
Logs with timestamps in scan_results.txt
# Usage
Compile:
gcc scanner_combined.c -o scanner_combined -lpthread
Run:
./scanner_combined -i <IP_ADDRESS> -s <START_PORT> -e <END_PORT> -t
# Example:
./scanner_combined -i 8.8.8.8 -s 20 -e 25 -t
Output Example
[TCP] Port 53: OPEN [Wed Jul 16 06:11:49 2025]

Skillset: Linux C
Project: Network Port Scanner
Team No: 16 | Members: <names> : Anvitha C N, Athmashree U, Ranjitha T, Sathvika G Naik, Shrikanth
