By Lucian Constantin
CSO Senior Writer, CSO
DEC 8, 2022 12:26 PM PT
Security researchers have developed a generic technique for SQL injection that bypasses multiple web application firewalls (WAFs). At the core of the issue was WAF vendors failing to add support for JSON inside SQL statements, allowing potential attackers to easily hide their malicious payloads.

The bypass technique, discovered by researchers from Claroty’s Team82, was confirmed to work against WAFs from Palo Alto Networks, Amazon Web Services (AWS), Cloudflare, F5, and Imperva. These vendors have released patches, so customers should update their WAF deployments. However, the technique might work against WAF solutions from other vendors as well, so users should ask their providers if they can detect and block such attacks.
