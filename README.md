# **WebLock: AI-Powered Cybersecurity and Digital Forensics Tool**

Welcome to **WebLock**, an advanced cybersecurity tool designed to safeguard your web applications from various threats using machine learning, behavioral analysis, and real-time forensic capabilities. WebLock’s core mission is to protect databases from attacks, automate digital forensic investigations, and provide a dynamic and detailed threat intelligence system. Whether you're an individual or an organization, WebLock is your shield against evolving cybercriminal techniques.

---

## **Introduction:**

In today's digital world, cybercriminals have become increasingly sophisticated, using advanced techniques like SQL Injection, XSS, Brute Force, and keylogging to breach systems. **WebLock** leverages **AI-powered detection models** and real-time forensic data collection to safeguard your applications and provide actionable insights for digital forensics.

### **Problem Statement:**
As cybercriminals evolve their attack strategies, traditional defense mechanisms struggle to keep up. The need for an intelligent and adaptive system that can detect threats in real time, capture evidence, and protect databases is paramount.

### **Solution:**
**WebLock** provides a comprehensive solution by:
- Detecting attacks in real-time.
- Collecting forensic data automatically upon threat detection.
- Offering a powerful admin dashboard for analysis and monitoring.
- Using machine learning to recognize attack patterns and improve security.

---

## **Key Features:**

### **1. Real-Time Attack Detection:**
WebLock identifies various cyberattack vectors such as:
- **Brute Force**
- **Credential Stuffing**
- **SQL Injection**
- **XSS (Cross-Site Scripting)**
- **Session Hijacking**
- **Keylogging**

The system’s **machine learning models** continuously evolve to detect new and unknown attack patterns.

### **2. Intruder Identification and Logging:**
When an attack is detected, WebLock does more than just block it:
- **Logs the intruder’s IP and MAC address.**
- **Tracks their physical location, ISP, and device details**.
- **Captures screenshots** and webcam images.
- **Records keystrokes** for further analysis.

### **3. Forensic Data Collection:**
- **Intruder Logs**: Includes detailed metadata like IP, MAC address, location, attack type, and ISP.
- **Captured Images**: Screenshots and webcam photos of the intruder are stored for evidence.
- **Keylogger**: Logs every keystroke and records suspicious activity like clipboard usage or fast typing.

### **4. Real-Time Forensic Reports:**
- **Automated Report Generation**: As soon as an attack is detected, WebLock generates a **forensic PDF report**, which includes:
  - **Intruder images and screenshots**.
  - **Detailed attack data** and timestamps.
  - **Location information**.

These reports are stored both on your server and uploaded to a **central database** for future reference.

### **5. Machine Learning-Powered Anomaly Detection:**
WebLock uses **machine learning algorithms** to analyze login patterns, detect unusual behavior, and predict future attack attempts. It helps in:
- **Identifying abnormal traffic patterns**.
- **Flagging suspicious logins**.
- **Blocking high-risk IP addresses** based on historical data.

### **6. Admin Dashboard:**
- **Dashboard for Monitoring**: An intuitive admin dashboard provides real-time monitoring of all system activities.
- **Network Analysis**: Visualize and analyze network traffic in real-time with interactive graphs.
- **IP and MAC Address Tracking**: Compare current login attempts with approved devices and IP addresses to ensure only authorized users have access.

### **7. Threat Intelligence Integration:**
WebLock goes beyond the basics, integrating **threat intelligence** to:
- Automatically **block malicious IPs**.
- Provide **detailed threat reports**.
- Offer insights on potential vulnerabilities in your system.

---

## **Tech Stack:**

- **Backend**: Python (Flask)
- **Machine Learning**: Scikit-learn, TensorFlow
- **Database**: MongoDB (for real-time data storage)
- **Frontend**: HTML, CSS, JavaScript
- **Real-Time Logging**: CSV (login logs), JSON (attack logs)
- **Data Analysis**: Custom-built algorithms for anomaly detection

---

## **How WebLock Works:**

1. **Login Verification**: When a user attempts to log in, WebLock verifies their credentials and IP address.
2. **Behavioral Analysis**: The system continuously monitors the user’s behavior (e.g., typing speed, login times, etc.) and flags any abnormalities.
3. **Attack Detection**: If an attack is detected (SQL Injection, XSS, etc.), the system:
   - Logs the attack.
   - Activates the **trap mechanism** (keylogger, webcam capture, screenshots).
4. **Forensic Report Generation**: A comprehensive **forensic report** is generated immediately upon attack detection and stored securely for further analysis.
5. **Continuous Learning**: The machine learning models are trained on collected data, improving their ability to identify new attack vectors.

---

## **Installation and Setup:**

### **1. Clone the Repository:**
```bash
git clone https://github.com/hitksh18/weblock-p.git

cd WebLock
```

### **2. Install Dependencies:**
```bash
pip install -r requirements.txt
```

### **3. Run the Application:**
```bash
python app.py
```

Visit `http://localhost:5000` to access the WebLock interface.

---

## **Future Plans:**
- **VPN Detection**: Adding mechanisms to detect and block VPN-based attacks.
- **Cloud Integration**: Store forensic reports in the cloud for better scalability.
- **Advanced AI Models**: Implementing advanced deep learning models for better attack prediction and anomaly detection.

---

## **Contributing:**

We welcome contributions! If you want to help improve **WebLock**, feel free to:
1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request with a detailed description of the improvements.

---

## **Contact:**
- **Developer**: Hitesh Ksheersagar
- **Email**: sentinels1825@gmail.com
- **GitHub**: hitksh18

---

## **Acknowledgments:**

- **AI Model Credits**: [Machine Learning Framework Credits]
- **Libraries Used**: Scikit-learn, Flask, TensorFlow, etc.
- **Open Source Contributions**: [List contributors if applicable]

---

**WebLock** is designed to evolve continuously as cyber threats grow more sophisticated. By leveraging the power of AI and real-time data collection, it provides an advanced layer of protection and evidence collection to ensure that your web applications remain secure in an ever-changing digital landscape.
