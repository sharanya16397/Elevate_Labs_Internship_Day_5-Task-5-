# Elevate_Labs_Internship_Day_5-Task-5

🛰️ Network Traffic Capture & Protocol Analysis with Wireshark

This project is part of a hands-on lab to capture, filter, and analyze live network traffic using Wireshark. It helps develop foundational packet analysis skills and protocol awareness by inspecting real-world data packets.

📌 Objective

Capture live network traffic using Wireshark, identify at least three common internet protocols (e.g., DNS, HTTP, ICMP), and analyze packet behavior.

🛠️ Tools Used

Wireshark (open-source network protocol analyzer)

Web browser (for traffic generation)

Command-line ping (for ICMP traffic)

OS: Windows / macOS / Linux

🚀 Steps Performed

Installed and launched Wireshark.

Selected the active network interface (e.g., Wi-Fi).

Began live packet capture.

Generated traffic by browsing websites and pinging servers.

Stopped the capture after 1 minute.

Applied filters for protocols: DNS, HTTP, ICMP, TCP.

Analyzed and documented sample packet details.

Exported the capture to a .pcapng file.

Compiled a short report of findings.

🔍 Protocols Identified
Protocol	Purpose	Notes
DNS	Resolves domain names to IP addresses	Observed DNS query to 8.8.8.8
TCP	Connection protocol for web traffic	TCP 3-way handshake observed
ICMP	Ping test (echo requests/replies)	Successful ping to google.com
HTTP/HTTPS	Web content delivery	TLS handshake and GET requests found
📂 Project Files

task5_capture.pcapng — Raw packet capture file

Task5_Report.pdf (optional) — Summary of protocol analysis and key packet details

README.md — Project documentation (this file)

📈 Sample Packet Observations

Packet #12: DNS query from 192.168.1.4 to 8.8.8.8 for www.google.com

Packet #25: TCP SYN to 142.250.182.206 (HTTPS)

Packet #30: ICMP Echo request from local host to Google

📚 Outcome

By completing this task, I gained practical experience in:

Using Wireshark filters

Understanding common internet protocols

Capturing and interpreting live network traffic

Exporting packet data for reporting

📎 References

Wireshark Documentation: https://www.wireshark.org/docs/

Protocol Hierarchy: Statistics → Protocol Hierarchy in Wireshark
