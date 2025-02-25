[HIPAA Journal](https://www.hipaajournal.com/january-2024-cyberattack-on-lurie-childrens-hospital-affects-792k-individuals/) On January 31, 2024, Lurie Children's Hospital in Chicago, IL experienced a cyberattack that took IT systems offline, including
- Epic Electronic Health Record (EHR) Systems
- MyChart Patient Portal

Hospital staff had to work by hand to record patient information while EHR was down. On May 20, 2024, access was restored, and manually recorded information had to be put back into the EHR system.

# Personal Reactions
[Reddit](https://www.reddit.com/r/chicago/comments/1at2wno/anyone_have_inside_info_on_the_lurie_childrensnwm/) According to Reddit user [[cashleydashley]], who was a nurse at Lurie Children's Hospital, the staff at Lurie Children's typically know as much about the attack as the rest of the general public. 

[Reddit](https://www.reddit.com/r/Residency/comments/1fn3u7i/about_lurie_childrens_layoffs/) More recently, there have been some layoffs at the hospital. According to Reddit user [[The_Forgotten_King]], the outage caused the hospital to lose around 2 months worth of revenue.

# Attribution
[The Record](https://therecord.media/ransomware-gang-claims-payment-luries) [Fierce Healthcare](https://www.fiercehealthcare.com/providers/cybersecurity-matter-forces-lurie-childrens-hospitals-communications-mychart-offline) Attribution points to [[Rhysida]], which listed patient data on its website, selling the stolen information also for around $3.4 million, or **60 bitcoins**. In the week of March 7th, 2024, the listing on Rhysida's website was updated to say "All data was sold."
# Attack Vector
[Security Magazine](https://www.securitymagazine.com/articles/100828-nearly-800-000-affected-by-childrens-hospital-ransomware-attack) The attack vector was a ransomeware attack. While the nature of the attack is not reported to the public, the Tactics, Techniques, and Procedures (TTPs) of Rhysida provide a look into what might've happened. Most likely, the threat actors gained access to Lurie Children's system through email phishing, then used **Cobalt Strike**, a pen-testing tool, for privilege escalation.

# Scope
[HIPAA Journal](https://www.hipaajournal.com/january-2024-cyberattack-on-lurie-childrens-hospital-affects-792k-individuals/) Hackers had access to Lurie Children's systems from January 26 to January 31, giving them 5 days to access patient information. According to the Maine Attorney General, **791,784** individuals were affected. The exposed information varies from each patient, but it includes
- Name
- Address
- Telephone number
- Email address
- Date of birth
- Dates of service (when the treatment occured)
- Driver’s license number
- Health claims information
- Health plan
- Health plan beneficiary number
- Medical condition or diagnosis
- Medical record number
- Medical treatment
- Prescription information
- Social Security number