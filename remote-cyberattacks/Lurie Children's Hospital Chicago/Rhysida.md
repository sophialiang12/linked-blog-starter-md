[CISA](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-319a) Rhysida is a Ransomware as a Service (RaaS) group, using ransomware tools for profit and splitting the ransom between the group itself and any collaborators. Rhysida attacks no specific group, but rather **"targets of opportunity,"**  including sectors such as
- Education
- Healthcare
- Manufacturing
- Information technology
- Government

# Gaining Access
Rhysida typically gains access to a network via **remote services such as VPNs or remote desktops**, connecting to the target network from outside locations. The group typically targets victims that lack MFA, allowing them to log in with valid credentials without additional protections. This is typically gained through **phishing**. Additionally, they exploit known security vulnerabilities such as **Zerologon** and escalate privileges through there.

# Privilege Escalation
Rhysida uses "**Living of the Land"** techniques to hide in plain sight. The group uses built-in Windows tools such as PowerShell to avoid detection.

Privilege escalation is achieved by creating **Remote Desktop** or **SSH** (remote login from one computer into another) for horizontal privilege escalation, gaining access to users of the same privileges. The group also **extracts passwords from memory** using specialized tools.

# Ransomware
Rhysida maps the network, and the ransomware encrypts data via **4096-bit RSA encryption with a ChaCha20 algorithm**. The victim is unable to access the encrypted files.

The group engages in **double extortion** after the files are encrypted, demanding ransom to
- Decrypt encrypted files
- Prevent publishing of sensitive files

The group demands payment in cryptocurrency, typically **Bitcoin**.