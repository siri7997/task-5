# task-5
Packet Capture and Protocol Identification
Objective
Capture live network packets and identify basic protocols and traffic types.

Tools Used
Wireshark – Free, open-source network protocol analyzer

Steps Performed
Installed Wireshark on the system.

Selected the active network interface (Wi-Fi/Ethernet).

Started live packet capture.

Generated network traffic by:

Browsing a website (HTTP/HTTPS)

Pinging a public server (ping google.com)

Stopped the capture after ~1 minute.

Applied protocol filters in Wireshark (http, dns, tcp, icmp).

Identified at least three different protocols.

Exported the capture file as network_capture.pcap.

Summarized findings and packet details.

Protocols Identified
DNS (Domain Name System) – Resolves domain names to IP addresses.

HTTP/HTTPS (Hypertext Transfer Protocol/Secure) – Web browsing traffic.

ICMP (Internet Control Message Protocol) – Ping request/reply for connectivity testing.

Findings
DNS packets: Contain queries for website domains and corresponding IP resolutions.

HTTP packets: Show web requests (GET/POST) to servers; HTTPS packets are encrypted.

ICMP packets: Show echo requests and replies, confirming host reachability.

Deliverables
network_capture.pcap – Captured packet data.

This report – Summary of identified protocols and their function.

Outcome
Gained hands-on experience in packet analysis and protocol identification using Wireshark, strengthening network traffic analysis skills.
