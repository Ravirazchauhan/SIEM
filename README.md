# SIEM
I am working on a Tool that will collect logs from a single machine like SIEM and notify the owner if there is anything suspicions 

Now, follow these steps:

1️⃣ Set Up Dependencies
Ensure you have all required dependencies installed. Run:

pip install flask psutil pywin32

(On Linux, remove pywin32 since Windows-specific modules won’t work.)

2️⃣ Run the Script
Execute:

python your_script.py
This will start monitoring logs, detecting anomalies, and launching the Flask web server.

3️⃣ Access the Web Dashboard
Open http://localhost:5000 in your browser.

View logs at http://localhost:5000/logs.

View detected anomalies at http://localhost:5000/alerts.

Monitor running processes at http://localhost:5000/processes.

4️⃣ Next Steps
Do you want better UI/visualization (charts, graphs)?

Should we add email/SMS alerts for critical anomalies?
DM: ravirazchauhan@gmail.com

Would you like to store logs persistently (database integration)?
