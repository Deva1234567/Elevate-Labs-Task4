1. Opened Windows Defender Firewall with Advanced Security via search.
2. Viewed Inbound Rules list and took screenshot.
3. Created new inbound rule: TCP, port 23, block connection, applied to all profiles, named "Block Telnet Port 23".
4. Tested using `telnet <IP_Address> 23` in cmd; connection failed as expected.
5. Deleted the rule via right-click > Delete in Inbound Rules.# Elevate-Labs-Task4
