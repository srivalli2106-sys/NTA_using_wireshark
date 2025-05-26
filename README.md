# NTA_using_wireshark
Abstract
This project is focused on capturing, analyzing, and interpreting network traffic using Wireshark and PyShark (a Python wrapper for TShark). By analyzing packet-level network traffic either in real time or from previously captured files, the project provides valuable insights into the types of protocols in use, the volume of traffic exchanged, and possible signs of malicious or abnormal activity. It aims to assist network administrators, security analysts, and learners in better understanding network behavior and detecting potential threats through automated analysis.
Objectives
To capture and analyze network packets using Wireshark or Python.


To identify and summarize protocol usage (TCP, UDP, DNS, HTTP, etc.).


To detect basic anomalies such as high-frequency packet sending or unusual IP activity.


To provide exportable summaries for reporting and visualization.


To build a foundational framework that can be extended to include more advanced threat detection features.


Technologies Used
Wireshark – Used for packet capture and initial inspection.


TShark – The command-line utility of Wireshark used for backend processing.


PyShark – A Python library used to interface with TShark for automated analysis.


Python 3 – Used to write analysis scripts and automate parsing.


Linux – The environment used for developing and running the analysis.


CSV – Format used to export traffic summaries for further analysis or visualization.





Key Features
Packet filtering by protocol, IP, or port.


Real-time or offline packet analysis (from .pcap files).


Protocol distribution and IP-based traffic summaries.


Identification of suspicious activity, such as IPs with unusually high connection counts.


Export of results to CSV format for integration with reports or visualization tools.


Modular and easy-to-extend Python codebase.
