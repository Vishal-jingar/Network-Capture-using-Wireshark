# Network-Capture-using-Wireshark
Wireshark Protocol Capture Project
This project demonstrates the process of capturing and analyzing different network protocols using Wireshark. The captured protocols include TCP, HTTP, and DNS, with corresponding .pcap files and screenshots for each.

 Tools Used
Wireshark – Network protocol analyzer

Command Prompt / Terminal – To generate DNS queries

Web Browser – To generate HTTP and TCP traffic

Operating System: Windows/Linux/Mac (specify if needed)

 Protocols Captured
🔹 TCP
Captured general TCP handshake and communication.

Filter used: tcp

File: tcp_capture.pcap

Screenshot: tcp_screenshot.png

🔹 HTTP
Captured HTTP requests by visiting an HTTP website.

Filter used: http

File: http_capture.pcap

Screenshot: http_screenshot.png

Note: Use a site like http://example.com to ensure HTTP (not HTTPS) is used.

🔹 DNS
Captured DNS queries using nslookup or browsing a website.

Filter used: dns

File: dns_capture.pcap

Screenshot: dns_screenshot.png

 How to Use

git clone https://github.com/yourusername/wireshark-protocol-capture.git
Open the .pcap files using Wireshark:

Navigate to File > Open

Select the .pcap file for the protocol you want to view.

Use the filters mentioned above in Wireshark to analyze the traffic.
 Report
The full procedural report can be found in:
 Wireshark_Protocol_Capture_Report.docx

rep structure

/tcp_capture.pcap
/http_capture.pcap
/dns_capture.pcap
/tcp_screenshot.png
/http_screenshot.png
/dns_screenshot.png
/Wireshark_Protocol_Capture_Report.docx
/README.md
