# Building-Firewall-for-IoT-devices
Advanced firewall solution for securing IoT devices against cyber threats.

ABSTRACT

The rapid adoption of IoT devices has introduced major cyber security risks due to weak  security measures. Notable incidents like the Mirai botnet attack (2016) and the water treatment facility hack (2021) highlight these vulnerabilities. This project aims to develop an advanced firewall for IoT devices to enhance security and mitigate cyber threats effectively. The firewall will incorporate real-time traffic monitoring and anomaly detection to identify suspicious activities. Additionally, it will feature adaptive access control mechanisms to prevent unauthorized access and ensure secure device communication.

PROBLEM  IDENTIFICATION & DEFINITION

"Design and implement a lightweight, secure, and decentralized communication framework for IoT devices using ESP-NOW, addressing the challenges of resource constraints, protocol heterogeneity, and data security, while ensuring scalability, energy efficiency, and ease of deployment.”
The main problem this project seeks to address is the inadequate security in IoT communication systems. Specifically, it focuses on mitigating the risks arising from the lack of encryption, vulnerable communication protocols (like unencrypted MQTT and HTTP), and unauthorized device access.

Problem Statement:Despite their potential to revolutionize industries and daily life, IoT devices are inherently vulnerable to security threats. One of the fundamental reasons for this vulnerability is the lack of comprehensive security measures implemented at the device level. 

OBJECTIVES

Developing a Secure Communication Protocol.
Minimizing Latency and Bandwidth Usage.
Ensuring Scalability and Flexibility.
Enhancing Energy Efficiency.
Providing Offline Functionality.

IMPLEMENTATION

Hardware & Setup – Configure ESP8266/ESP32 with ESP-NOW for peer-to-peer communication.
Security Measures – Implement MAC filtering, AES-128 encryption, and real-time intrusion detection.
Data Handling – Enable segmentation, checksums, SPIFFS storage, and backup mechanisms.
Firewall Mechanism – Block unauthorized devices & log access attempts.
Front-End Development – Build a responsive UI with Web Serial API for real-time control.
OSI Layer Security – Apply encryption, authentication, and secure coding across layers.
Testing & Deployment – Perform unit, functional, security, and UAT testing before deployment.
