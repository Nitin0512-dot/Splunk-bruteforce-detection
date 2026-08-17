# Splunk-bruteforce-detection

## Objective
The objective of this SOC analyst project for detecting and investigating SSH brute-force attacks using Splunk and Linux authentication logs.

## Detection
- Extracted source IP and username from authentication logs
- Counted failed SSH login attempts
- Analyzed failed attempts within a defined time windows
- Identified top attacking source IPs

## Investigation
- Investigated suspicious source IPs generating repeated failed logins
- Analyzed targeted username and source IPs
- Correlated successful logins following multiple failed attempts but no successful login activity happened
  
