
IPS BY ML (INTRUSION PREVENTION SYSTEM USING MACHINE LEARNING)
==============================================================

Project Overview
----------------
IPS BY ML is an advanced hybrid Intrusion Prevention System designed to provide real-time protection against modern cyber threats.
The project combines Network Security Monitoring, Browser-Level Attack Prevention, and Behavior-Based Analysis to detect,
analyze, and mitigate malicious activities before they impact the system.

Unlike traditional IPS solutions that rely solely on static signatures, IPS BY ML introduces an intelligent scoring engine
that evaluates behavior patterns, assigns risk scores, and triggers automated defensive actions.

Key Features
------------
[✓] Real-Time Network Monitoring
[✓] Browser Intrusion Prevention System (Browser IPS)
[✓] SQL Injection Detection & Prevention
[✓] Cross-Site Scripting (XSS) Detection & Prevention
[✓] Command Injection Detection
[✓] Path Traversal Detection
[✓] ARP Spoofing Detection
[✓] Automatic IP Blocking
[✓] Automatic Wi-Fi Isolation During Critical Threats
[✓] Security Alerts Logging
[✓] Interactive Dashboards
[✓] Chrome Extension Integration
[✓] Behavior-Based Security Scoring
[✓] Live Charts & Analytics
[✓] SQLite Security Event Database

Machine Learning Inspired Engine
--------------------------------
The project applies Machine Learning concepts through intelligent behavioral analysis rather than heavy pretrained models.

Behavioral Factors:
• Network Traffic Changes
• Connection Frequency
• Interface Activity
• MAC Address Changes
• ARP Behavior Patterns
• Browser Navigation Activity
• Suspicious URL Detection

Risk Score Levels:
0.0 - 0.4  → Safe
0.4 - 0.6  → Suspicious
0.6 - 1.0  → High Risk

Automatic Response Engine
-------------------------
When malicious behavior exceeds configured thresholds, the system can:

• Generate Security Alerts
• Log Attack Information
• Block Suspicious IP Addresses
• Disable Network Interfaces
• Terminate Malicious Browser Sessions
• Notify Security Operators

Browser IPS Module
------------------
The Browser IPS is implemented as a Chrome Extension (Manifest V3).

Capabilities:
• Real-Time URL Inspection
• SQL Injection Detection
• XSS Detection
• Domain Blocking
• Malicious Request Prevention
• Browser Tab Monitoring
• Dashboard Synchronization

Network Security Module
-----------------------
Features:
• Interface Monitoring
• Active Connection Analysis
• ARP Spoofing Detection
• MAC Change Tracking
• Whitelist Protection
• Rate Limiting Protection
• Automatic Mitigation Actions

Technology Stack
----------------
Backend:
• Python
• FastAPI

Frontend:
• HTML5
• CSS3
• JavaScript

Visualization:
• Chart.js

Database:
• SQLite

Configuration:
• YAML

Browser Security:
• Chrome Extension (Manifest V3)

Core Libraries:
• FastAPI
• Uvicorn
• Pydantic
• PyYAML
• psutil
• netifaces

System Architecture
-------------------
+---------------------+
| Browser Extension   |
+----------+----------+
           |
           v
+---------------------+
| FastAPI Backend     |
| IPS Engine          |
+----------+----------+
           |
           v
+---------------------+
| Detection Engine    |
| ML Scoring Engine   |
+----------+----------+
           |
           v
+---------------------+
| SQLite Database     |
+----------+----------+
           |
           v
+---------------------+
| Security Dashboard  |
+---------------------+


Installation
------------
1. Install Python 3.9+

2. Install Dependencies
   pip install -r requirements.txt

3. Run Backend
   python main.py

4. Open Browser
   http://127.0.0.1:8000

5. Load Browser Extension
   Chrome → Extensions
   Enable Developer Mode
   Load Unpacked
   Select browser-extension folder

Project Structure
-----------------
backend/
frontend/
browser-extension/
database/
config.yaml

Developed By
------------
Net Defenders Team

Ahmed Mohamed Abo Rashed
Seif Adel Eltanaihey
Mohamed Ahmed Elshanawy
Gamal Osama Areda
Basmala Mahmoud Radwan
Shahd Ehab Mohamed

University
----------
Delta University for Science and Technology

Disclaimer
----------
This project was developed for educational, academic, and cybersecurity research purposes.
Unauthorized use against systems without permission is strictly prohibited.

© 2026 Net Defenders Team
