Basic Network Scan with Nmap
Description

This project contains details about how to perform a basic network scan using Nmap. It is intended as a learning resource for those getting started in the field of cybersecurity, particularly focusing on network scanning and security.
Purpose

The purpose of this project is to demonstrate the use of Nmap, a versatile tool for network scanning and security auditing. This can be helpful for identifying open ports, live hosts, and various attributes of network devices.
How To Use

You can use the commands listed in this repository to run similar network scans on your system. Always remember to have proper authorization before scanning any network other than your own.
Step 1: Installing Nmap

For Kali Linux, you can install Nmap by running:

sudo apt install nmap

Step 2: Running the Scan

To run a basic scan, use:

css

nmap [IP_ADDRESS]

Replace [IP_ADDRESS] with the target IP address.
Step 3: Interpreting the Output

    Host is up: Indicates that the target is active.
    All 1000 scanned ports on [target] are in ignored states: Indicates that no open ports were found in the scanned range.

Results

In my own test, I scanned my local machine. I found that all 1000 ports (from 1-1000) were closed, indicating good initial security posture.
