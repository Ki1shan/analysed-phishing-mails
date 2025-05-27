# analysed-phishing-mails
 Phishing Email Analysis Report
 
Windows Error Report Phishing Analysis
"When 'Microsoft Support' is anything but supportive".

The Scam at a Glance
You get an email titled “Windows Error Report” claiming:
“We detected suspicious activity on your PC from Nigeria! Click here to secure your license key.”

Spoiler: It’s fake. Here’s how I proved it.

How I Unmasked It
Red Flags
📧 Sender: no-reply.msteamz@outlook.com
Microsoft Teams never uses @outlook.com.
Fake IP: 293.09.101.9
IP addresses can’t exceed 255 (this was like a phone number with a “9” in the area code!).
Urgency: Threats like “Your license will be corrupted!”
Real companies don’t panic you into acting.
Grammar: “malicious user might trying to access”
Microsoft has editors. Scammers don’t.

Files in This Repo
Microsoft-phishing.txt: The email’s raw headers (the “receipt” showing its origin).
windows-phishing.png: Screenshot of my Google Messageheader results.

Tools I Used
MessageHeader: To trace the email’s path (like tracking a package).
IPVoid: To check if the sender’s IP was blacklisted (it was).

