A professional Python-based automation tool to monitor the availability of network devices and servers.
*Ein professionelles Python-basiertes Automatisierungstool zur Überprüfung der Erreichbarkeit von Netzwerkgeräten und Servern.*

# Project Overview / Projektübersicht
This project demonstrates the integration of **System Administration** and **Python Programming**. It automates the routine task of checking server status, reducing manual effort for system administrators.

*Dieses Projekt zeigt die Integration von Systemadministration und Python-Programmierung. Es automatisiert die Routineaufgabe der Serverprüfung.*

# Key Features / Hauptmerkmale
* **Cross-Platform:** Automatically detects if the OS is Windows or Linux and adjusts commands. (Funktioniert auf Windows und Linux).
* **Real-time Logging:** Displays results with precise timestamps for troubleshooting. (Echtzeit-Logging mit Zeitstempeln).
* **Bilingual Code:** Documented in both English and German for professional environments. (Zweisprachige Dokumentation).

# Technical Details / Technische Details
* **Language:** Python 3
* **Modules used:** * `os`: To execute system-level ping commands.
    * `platform`: To ensure compatibility across different operating systems.
    * `datetime`: To provide accurate logs.

# How to Use / Anwendung
1. Add your target IP addresses to the `targets` list in `monitor.py`.
2. Run the script using:
   ```bash
   python monitor.py
