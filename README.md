🔐 ChatGuardian – Real-Time Message Security Monitor
📌 Overview

ChatGuardian is a cybersecurity-based project designed to monitor and analyze messages in real time to detect potential security threats such as phishing links, malicious keywords, and suspicious patterns.

The system works locally and ensures user privacy while providing instant alerts for unsafe content. It can later be integrated with chat applications like WhatsApp Web, Slack, or custom messaging systems.

🚀 Features
🔍 Real-time message monitoring
⚠️ Detection of phishing links
🧠 Keyword-based threat analysis
🚫 Suspicious content flagging
📝 Log generation for detected threats
🔒 Works locally (privacy-friendly)
🎯 Objectives
To identify malicious or suspicious messages
To prevent phishing and social engineering attacks
To provide real-time alerts for unsafe content
To build a lightweight cybersecurity tool
❗ Problem Statement

With the rise of online communication, users are increasingly exposed to phishing links, spam, and malicious messages. Most users fail to identify such threats, leading to data breaches and cyber attacks.

ChatGuardian aims to solve this problem by automatically scanning messages and alerting users before harm occurs.

🛠️ Technologies Used
Programming Language: Python
Libraries:
re (Regular Expressions)
nltk (Natural Language Processing)
sklearn (Optional ML model)
Platform: VS Code (Jupyter Notebook)
📂 Project Structure
ChatGuardian/
│── data/
│   └── keywords.txt
│
│── src/
│   ├── detector.py
│   ├── analyzer.py
│   └── main.py
│
│── logs/
│   └── alerts.log
│
│── README.md
│── requirements.txt
⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/chatguardian.git
cd chatguardian
2. Install Dependencies
pip install -r requirements.txt
3. Run the Project
python src/main.py
🧪 How It Works
User inputs a message
System scans for:
Suspicious keywords
Malicious URLs
Message is analyzed
If threat detected:
Alert is generated
Log is saved
📊 Example

Input:

Click this link to win money: http://fake-site.com

Output:

⚠️ Warning: Suspicious link detected!
📈 Future Enhancements
🤖 Machine Learning-based threat detection
🌐 Browser extension integration
📱 Mobile app support
☁️ Cloud-based monitoring
🔐 Security Considerations
Runs locally (no data sharing)
No storage of sensitive personal data
Logs only suspicious activity
👨‍💻 Author

Arshad Kabir
IT Support Executive | M.Sc. AI & ML Student

📚 References
Python Documentation
Cybersecurity Basics (OWASP)
NLP with NLTK
