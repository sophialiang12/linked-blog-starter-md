[HIPPA Journal](https://www.hipaajournal.com/ascension-cyberattack-2024/) On May 8th, 2024, Ascension Health, a healthcare company with 142 hospitals, 40 senior living facilities, and more than 26,000 care sites across 19 states and Washington, D.C., experienced a cyberattack that infiltrated IT systems and impacted
- charting
- scheduling
- prescription writing

as well as stealing patient data. While EHR was down, staff had to use an analog system to record patient information. On June 14, 2024, Ascension Health EHR access was fully restored.
# Personal Reactions
[NPR](https://www.npr.org/2024/06/19/nx-s1-5010219/ascension-hospital-ransomware-attack-care-lapses) The outage led to hospitals having to use analog systems to administer care for patients. This led to many close calls:
- Marvin Ruckle (Nurse) "He nearly gave a baby 'the wrong dose of narcotic' because of confusing paperwork."
- Lisa Watson (ICU Nurse) "She said she nearly administered the wrong medication to a critically ill patient because she couldn’t scan it as she normally would. 'My patient probably would have passed away had I not caught it'"
- Melissa LaRue (ICU Nurse) "...described a close call with 'administering the wrong dosage' of a patient’s blood pressure medication"

[Reddit](https://www.reddit.com/r/nursing/comments/1cnox74/ascension_cyber_attack/) This Reddit thread has the reaction of many staff members at Ascension healthcare facilities across the country. The outage caused a frantic shift to convert to paper charting, which overwhelmed many staff members, such as [[Taj525]] at Ascension healthcare facilities. 

[Reddit](https://www.reddit.com/r/nursing/comments/1cof30p/ascension_systems_down/) Furthermore, much of the staff was not trained for paper charting. For example, Reddit user [[Wineinmyyetti]] had to document and order 100 folders of patient records, and [[SirHarryAzcrack]] was never trained either. No plan B worries many staff members, such as [[soggydave2113]].

[Reddit](https://www.reddit.com/r/nursing/comments/1cn7evo/ascension_outage/) Paying is also an issue: [[Money_Potato2609]], causing some people to question whether or not to quit.

[CBS4 Indy](https://www.youtube.com/watch?v=NofGfUnptfs) Justin Niesr was a travel nurse working at Ascension St. Vincent.
- "Delays in X-Rays, CTs, MRIs, ..."

He caught many errors because of the switch from online to paper record keeping. He was asked by his boss to move to another unit that he had no training for, causing him and another nurse to resign.
- "Not worth patient risk..."
- "good luck going to an Ascension hospital, you might die"

## Potential Build up of Cyberattack
[The Stack](https://www.thestack.technology/ascension-cyber-attack/) [Reddit Post](https://www.reddit.com/r/cybersecurity/comments/1cqzr0u/comment/l3uzdrm/) "Ascension fired hundreds of IT staff and outsourced the roles to India. On Reddit after that decision, one purported former staffer commented “it needs to be publicly understood that trying to pull some lowest common denominator shit with your ENTIRE IT department is going to go up in flames.”"
# Attribution
[Bleeping Computer](https://www.bleepingcomputer.com/news/security/ascension-health-data-of-56-million-stolen-in-ransomware-attack/) CNN attributed the cyber attack to [[Black Basta]], and Health-ISAC warned of "recently accelerated attacks against the healthcare sector" from Black Basta.

[HIPAA Journal](https://www.hipaajournal.com/ascension-cyberattack-2024/?utm_source=chatgpt.com) While the total ransom that Black Basta demanded is not known currently, Ascension has lost $1.1 billion for the fiscal year ending June 30, 2024, most directly linked to the Black Basta outage.

[The Register](https://www.theregister.com/2024/05/13/cisa_ascension_ransomware) Typically, Black Basta has ransom demands into 6-figures.
# Attack Vector
[SC Media](https://www.scworld.com/news/patient-data-stolen-in-ascension-ransomware-attack-but-ehr-restored) The threat actor most likely gained access to the Ascension network through spear phishing, when an employee accidentally downloaded malware thinking it was legitimate.
- “The Ascension announcement is not a surprise, the Health Sector Coordinating Council identified social engineering as the first attack vector to be concerned about when prioritizing risk remediation.” - Toby Gouker

After gaining access to Ascension systems, the threat actors most likely escalated privileges via their TTPs and encrypted important hospital information to prevent staff from accessing it.
# Scope
[HIPPA Journal](https://www.hipaajournal.com/ascension-cyberattack-2024/) The threat actor breached 5,599,699 patient records, making it the third largest healthcare data breach of 2024. Breached data includes
- Personal information
- Medical information
- Payment information
- Insurance information
- Government identification

Threat actors did not have access to EHR, so full medical histories were not touched. However, many victims are worried about potential identity theft and fraud.

[Fierce Healthcare](https://www.fiercehealthcare.com/providers/systems-clinical-operations-interrupted-ascension-amid-apparent-cybersecurity-event) Some victims of the outage have sued Ascension for negligence in implementing industry-standard cybersecurity practices, arguing that the attack could've been preventable.