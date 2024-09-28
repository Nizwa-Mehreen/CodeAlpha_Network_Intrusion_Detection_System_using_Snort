This repository contains the necessary configuration files and instructions for setting up a basic Network Intrusion Detection System (NIDS) using Snort.
The OS used is Linux.

snort.conf: The main configuration file for Snort.

community.rules: A set of community-contributed Snort rules for detecting various network threats.

local.rules: Custom rules specifically designed to detect ICMP traffic, such as pings.

Setup Snort.txt: A guide on how to install and set up Snort on your system.

Run Snort.txt: Instructions on how to run Snort and direct its alerts to log files for analysis.

It demonstrates how to configure Snort to passively monitor network traffic and generate alerts based on custom-defined rules. Logs and alerts are saved in the /var/log/snort/ directory by default.
