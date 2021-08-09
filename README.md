# X-IIoTID- connectivity- and device-agnostic intrusion dataset for industrial internet of things 

The X-IIoTID dataset represents a carefully formulated simulacrum of recent attackers' tactics, techniques and procedures and the realistic IIoT systems' activities, including industrial control loops' devices (i.e., sensors, actuators and controllers), edge, mobile and cloud traffic and activities, the behaviours of their new connectivity protocols (e.g., MQTT, CoAP, WebSocket) and services, the diverse communication patterns (Machine-to-Machine, Human-to-Machine, and Machine-to-Human), and large volume network traffic and systems' events. It has connectivity- and device-agnostic features, making it suitable for the heterogeneous nature and interoperability demand of IIoT systems. These features were extracted from network traffic, system logs, application logs, device's resources (CPU, input/Output, Memory, and others), and commercial Intrusion detection systems' logs (OSSEC and Zeek/Bro).

The X-IIoTID dataset in its final version has 820,834 instances (421,417 observations/instances for normal and 399,417 for attacks) with 68 features (including three label levels, i.e., normal and attack, normal and sub-category attack, normal and sub-sub-category attack).

Attacks:
Reconnaissance: Generic scanning, scanning vulnerabilities, fuzzing, discovering resources.
Weaponisation: Brute force attack, dictionary attack, and the malicious insider.
Exploitation: reverse shell and Man-in-the-Middle.
Lateral Movement: MQTT cloud broker-subscription, Modbus-register reading, and TCP Relay attack.
Command and Control
Data Exfiltration
Tampering: poisoning of cloud data (i.e., false data injections), fake notification
Crypto-ransomware
Ransom Denial of Service attack
