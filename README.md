# Network Traffic Analysis Lab

## About

This project documents my hands-on learning experience in network traffic analysis using Kali Linux and Wireshark.

The objective of this laboratory was to understand how network communication works at the packet level by capturing, analyzing, and interpreting real network traffic instead of relying only on theoretical concepts.

Throughout the project, I generated different types of network traffic and analyzed them using Wireshark. Each analysis is supported by real packet captures, screenshots, and technical observations collected during the experiments.

The project focuses on three fundamental protocols commonly encountered in enterprise networks:

- ICMP for network connectivity testing.
- DNS for domain name resolution.
- TCP for reliable communication and connection establishment over HTTPS.

For every protocol, I documented the objective of the capture, the commands executed, the packets observed, the security interpretation, and the conclusions drawn from the analysis.

This repository demonstrates practical skills in packet capture, protocol analysis, network troubleshooting, and basic security monitoring. It also serves as a foundation for more advanced Blue Team and SOC investigations involving suspicious traffic, reconnaissance detection, and incident response.

## Conclusion

This project significantly improved my understanding of network communications and packet analysis.

Before completing this laboratory, protocols such as ICMP, DNS, and TCP were mostly theoretical concepts. Capturing and analyzing real traffic allowed me to observe how these protocols operate in practice and how devices communicate across a network.

Through the ICMP analysis, I learned how hosts verify connectivity and how Echo Requests and Echo Replies can be used for diagnostics. I also understood why abnormal ICMP activity may indicate reconnaissance attempts during a security investigation.

The DNS analysis demonstrated the complete process of translating a domain name into one or more IP addresses. By inspecting DNS queries and responses in Wireshark, I gained a better understanding of how applications locate remote servers before establishing a connection.

The TCP analysis helped me understand the importance of the three-way handshake and how reliable communication begins between a client and a server. Observing SYN and SYN/ACK packets in Wireshark provided practical insight into one of the most fundamental mechanisms of network communication.

Beyond learning individual protocols, this project strengthened my ability to capture traffic, apply Wireshark filters, interpret packet contents, and distinguish normal network activity from behavior that could require further investigation.

This laboratory also improved my documentation skills by transforming raw packet captures into structured technical reports supported by evidence and security interpretations.

Overall, this project represents an important step in my journey toward becoming a cybersecurity professional. It establishes a strong foundation for future work involving network monitoring, Security Operations Center (SOC) activities, digital forensics, threat detection, and incident response.
