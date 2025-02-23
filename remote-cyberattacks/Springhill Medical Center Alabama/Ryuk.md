Wizard Spider is a Russian-based cybercriminal group that has targeted hospitals, businesses, and government institutions [source](https://www.trendmicro.com/en_us/what-is/ransomware/ryuk-ransomware.html)
- Ryuk: a family of ransomware that first shuts down 180 services and 40 processes, then encrypts files using AES-256 encryption. The symmetric encryption keys are then encrypted using asymmetric RSA-4096.
- focuses on Microsoft Windows-based systems
- Often starts with a phishing email and once clicked, Ryuk downloads additional malware elements called droppers. The additional malware includes Trickbot, Zloader, BazarBackdoor, and others. These droppers install Ryuk directly onto the computer 

### Trickbot
A malware run by Wizard Spider. It's a "banking trojan to steal user credentials, personally identifiable information, and bitcoins" and can search for files in an infected system.
Main purpose is to deploy Ryuk ransomware
