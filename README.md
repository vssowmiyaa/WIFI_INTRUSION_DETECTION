# WIFI_INTRUSION_DETECTION
A simple Wi-Fi intrusion detection project in Kali Linux
📌 Abstract

The Wi-Fi Intrusion Detection and Monitoring System is a security-focused project designed to identify unauthorized devices attempting to connect to or scan a wireless network. With the rapid increase in cyber threats targeting Wi-Fi networks, real-time monitoring and intrusion detection have become essential to protect sensitive information and maintain network integrity.

This system combines network scanning, alert generation, and a visual dashboard to provide a comprehensive monitoring solution. Using Bash or Python scripts, the system continuously scans nearby Wi-Fi networks and compares them against a list of known/trusted networks.

When an unknown or unauthorized Wi-Fi network is detected, the system:

Logs the event with a timestamp

Triggers desktop notifications

Updates a live dashboard built using Flask + HTML/CSS

The dashboard provides a clear and interactive interface, showing all detected unauthorized Wi-Fi networks along with the detection time and date. Color-coded alerts enhance readability, making it easy for users to quickly identify suspicious activity.

The solution is lightweight, cost-effective, and can run on a standard laptop — suitable for both home users and small office environments. By providing early warnings of potential intrusions, this system empowers users to take immediate action to secure their network.

🎯 Features

✅ Real-time Wi-Fi network scanning

✅ Unauthorized device detection

✅ Automatic event logging with timestamps

✅ Desktop notifications for alerts

✅ Interactive dashboard with Flask + HTML/CSS

✅ Lightweight and cost-effective solution

🛠️ Tech Stack

Programming: Python / Bash

Backend: Flask

Frontend: HTML, CSS

Tools: Wireshark / Aircrack-ng (optional for advanced monitoring)

⚙️ How It Works

System scans nearby Wi-Fi networks at regular intervals

Compares detected networks with a list of known/trusted devices

If an unknown/unauthorized network is found →

Logs event with timestamp

Sends desktop notification

Updates live dashboard with details

Dashboard displays all detected unauthorized Wi-Fi networks in real-time

📊 Output (Screenshots)
https://drive.google.com/drive/folders/1vP7y8IbGPRfSZdTnui2J7yRSxnsKAPzw


Alert notification

🚀 Future Enhancements

🔹 Add SMS/email alerts for critical intrusions

🔹 Integration with cloud storage for logs

🔹 AI-based anomaly detection for smarter intrusion prevention

👨‍💻 Author

SOWMIYAA V.S

🎓 B.E CSE | Cybersecurity Enthusiast

🌐 LinkedIn Profile:https://www.linkedin.com/in/sowmiyaa-vs-820a91373?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
 | GitHub
