# Cyber-Frameworks

## MITRE
MITRE is a non-profit organisation that does research and development including in the cybersecurity field. MITRE has built several frameworks, most well know the MITRE ATT&CK framework which is highly useful and used in the industry.  
  
### MITRE ATT&CK
This framework is a reposatory of knowledge  on "Adversarial Tactics Techniques & Common Knowledge" which documents and sorts into different categories the malicious tactics, techniques and procedures (TTPs) used by advanced persisitent threat (APT) groups.
- Tactic: An adversary's goal or objective. The "why" of an attack
- Technique:How an adversary achieves their goal or objective
- Procedure: The implementation or how the technique is executed  

The [MITRE ATT&CK Matrix](https://attack.mitre.org/matrices/enterprise/) shows off all the tactics and techniques within the framework. Under CTI > Groups, there is also a section dedicated to known APT groups and attacks credited to them with the TTPs they used. ATT&CK Navigator layer can also be used to look at specific APT Group's preferred or previously used TTPs.
  
**Image 1: The header of each coloumn is a Tactic, under which all the Techniques are listing which are related to that specific tactic. The numbers in brackets next to the techniques show how many sub-techniques there are under each technique**
<img width="1216" height="756" alt="Képernyőkép 2025-12-06 185010" src="https://github.com/user-attachments/assets/dcebe446-ec96-477e-9715-6a794d30cd96" />

By clicking on any of the techniques a new page comes up, where all the information related to that specific technique can be accessed in detail. The information includes things such as, description of how the technique works, an ID number given to that specific technique, what tactic it falls under, examples, mitigations and detection strategies.  

**Video 1: Technique page for Active scanning**

https://github.com/user-attachments/assets/533efc54-b8b2-49f5-99b0-269a9a31f9ce

By having documented all of these adversarial activities in a uniform and easily accessible format it greatly helps security professional and organisations to use shared standard terms and reference the same unique IDs. Allowing efficient communication and allows incidents and data to be comparable between organisations. It also fuses together threat intelligence and defence and gives a good tool for defenders to understand new threats by having the TTPs mapped out and be able to translate them into detection rules.  
**Usage cases & users**
- *Cyber Threat Intelligence:* Collect and analyse threat data. Document discovered threat behaviours according to the ATT&CK framework
- *SOC:* Investigate and triage security alerts. Linking activity to TTPs to alerts and help prioratise incidents
- *Detection Engineers:* Develop and improve detection according to TTPs in the framework
- *Incident Responders:* Use the framework to more efficiently respond to incidents, using it to better visialise and follow the attack
- *Red & Purple Teams:* Copy the TTPs and behaviours documented to test defences and improve them
  
### MITRE D3FEND
It stands for "Detection, Denial, and Distruption Framework Empowering Network Defence". It is a structured framework that maps out defensive techniques and as with ATT&CK it is used to estblish a universal standard when it comes to describing security controls. It has its own [D3FEND Matrix](https://d3fend.mitre.org/) where in the same structure defensive techniques and tactics are documented. It provides a guide for defenders on controls and how to implement them and what attacks and threats each tactic and technique can tackle. 
  
**Image 2: The MITRE D3FEND Matrix**
<img width="1653" height="826" alt="Képernyőkép 2025-12-06 224256" src="https://github.com/user-attachments/assets/ae9349f4-59df-4f8c-87f8-0e2b128f29d7" />

## Cyber Kill Chain


## Unified Kill Chain

## Pyramid of Pain
