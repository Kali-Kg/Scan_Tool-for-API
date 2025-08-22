Server_sleep

Server_sleep is a versatile Red Team tool designed for server security testing and vulnerability assessment. It automates scans of open ports, HTTP/HTTPS services, SSL/TLS certificates, and web endpoints to detect potential weaknesses, while remaining stealthy and adaptable.


---

Key Features

Open Source: Fully accessible codebase, allowing customization and enhancements.

Cross-Platform Support: Works on Linux, macOS, Windows, and Android (via Python environments like Pydroid or Termux).

License Protection: Each installation is bound to a specific device MAC address. Licenses are issued manually by the developer to ensure security.

Automated Scanning:

Port scanning for common services

Banner grabbing

HTTP/HTTPS endpoint checks

SSL/TLS certificate audit

Directory fuzzing from user-provided wordlists


Threaded Execution: Uses multithreading for faster scanning of multiple targets.

Configurable: All parameters can be easily customized in config.json.



---

Usage

1. Setup

1. Open config.json in a text editor and fill in your configuration parameters.


2. Install required dependencies:



python3 install_Libs.py

2. License Registration

1. Run:



python3 get_MAC.py

2. Send your MAC address to the developer via Telegram: Nsioroot to receive a license.



> Note: The previous Telegram bot is no longer active. All licenses are now issued manually.



3. Run the Tool

On Linux/macOS:


./Server_sleep-CR.bin

On Windows: run the .exe version.

On Android: run via Python environment (Pydroid/Termux).



---

Important Notes

Ethical Use Only: Server_sleep is intended strictly for authorized penetration testing. Do not use on servers without permission.

Updates: The tool is continuously updated with new features, stealth improvements, and bug fixes.
