[HHS](https://www.hhs.gov/sites/default/files/black-basta-threat-profile.pdf) Black Basta shares similar TTPs with Conti and perhaps evolved from the group. Conti is a Kremlin associated hacker group. Black pasta is known for its double extortion attack, both executing ransomware and threatening to sell the data.

[CISA](https://www.cisa.gov/sites/default/files/2024-11/aa24-131a-joint-csa-stopransomware-black-basta_3.pdf) Black Basta operates as a RaaS model, conducting ransomware attacks on many high-value targets.
# Targets
[HHS](https://www.hhs.gov/sites/default/files/black-basta-threat-profile.pdf) In its first year, Black Basta targeted US organizations, impacting many healthcare institutions. However, the group has also targetted manufacturing, construction, and finance companies located in australia, Canada, the UK, and Europe.
# TTPs
[HHS](https://www.hhs.gov/sites/default/files/black-basta-threat-profile.pdf)
![[Screenshot 2025-03-23 at 12.48.16 AM.png]]
# Gaining Access
[CISA](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-131a) Black Basta gains access to networks through spearphishing and Qakbot, a malware loader and Trojan that is typically used as a delivery mechanism for ransomware by email thread hijacking.

They may also take advantage of unpatched vulnerabilities in public-facing applications, or use stolen credentials to gain access to remote services.

# Escalation and Lateral Movement
[CISA](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-131a) Black Basta uses Mimikatz for credential scraping to escalate privileges in the network. They have also exploited CVEs for local and Windows Active Directory privilege escalation.

For lateral movement, Black Basta uses tools such as BITSAdmin, PsExec, and Remote Desktop Protocol.
# Double Extortion
[CISA](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-131a) Black Basta uses RClone for data syncing used for exfiltration and PowerShell to disable antivirus protections in the network.

Files are encrypted using a ChaCha20 algorithm with RSA-4096 public key encryption, with a .basta file extension added to file names and a readme.txt file as a ransom note.