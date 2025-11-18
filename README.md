# Elevate-Labs04

🔥 Firewall Configuration Task

🎯 Objective

Configure and test basic firewall rules to allow or block network traffic on Windows or Linux systems.


---

🛠 Tools Used

🪟 Windows Firewall

🐧 UFW (Uncomplicated Firewall) on Linux



---

📎 Deliverables

📸 Screenshot of firewall rules

📄 Configuration file or command list



---

📘 Task Steps (Mini Guide)

1. 🏁 Open the firewall configuration tool

Windows: Windows Firewall

Linux: UFW using Terminal



2. 🔍 Check the current firewall status.


3. 🚫 Add a rule to block inbound traffic on a specific port

Example: Port 23 (Telnet)



4. 🧪 Test the rule by trying to connect to the blocked port.


5. 🔓 Add a rule to allow SSH (Port 22) on Linux.


6. ♻️ Remove the test block rule to restore original settings.


7. 📝 Document all commands or GUI steps used.


8. 📚 Write a short summary explaining how firewalls filter traffic.




---

🎓 Outcome

You will gain practical firewall management skills and understand how firewalls control network traffic.


---


🐧 Example Commands (Linux - UFW)

sudo ufw status
sudo ufw deny 23
sudo ufw allow 22
sudo ufw delete deny 23


---

🪟 Windows Firewall Steps

1. Open Windows Defender Firewall


2. Go to Advanced Settings


3. Select Inbound Rules → New Rule


4. Choose Port → Enter Port Number → Block


5. Test the rule


6. Delete the rule after testing

