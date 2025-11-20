Network Traffic Analysis Project 
---
Project Overview

This project focuses on the analysis of live network traffic captured from a local device interface.

The primary objective was to identify various communication protocols, inspect packet structures, and understand network behavior using Wireshark.

The analysis covers the successful identification of IPv4/IPv6 traffic, encrypted transport protocols (QUIC, TLS 1.3), and local network discovery mechanisms.


---


Repository Contents
---
This repository contains the following two key files:

1. PCAP FILE
   ---
   
   Description: This is the raw packet capture file generated using Wireshark.

   Contents: It contains approximately 88 seconds of recorded network traffic, including over 1,200 packets. Usage: You can open this file in Wireshark to inspect the individual packets, apply filters, and verify the findings.

   
3. REPORT
   ---
   
   Description: A comprehensive project report detailing the findings from the packet capture.
   
   Contents: Step-by-step methodology used for the capture. Technical analysis of protocols (DNS, TCP, TLS, QUIC).Specific observations regarding traffic sources (e.g., Spotify, Google Services).



  
Tools Used
---
Wireshark: For packet capturing and filtering.

---





How to Review
---


Read the Report: 

Start with the network_analysis_report.pdf to understand the context and summary of the analysis.


Analyze the Data: 

Open network_traffic_capture.pcap in Wireshark to see the raw data referenced in the report.
