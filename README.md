# Learning-Basics
This is a introductory for me. Learning and covering the basics 

SOC Level 1 Learning – Beginner Cybersecurity Practice

In this project, I am completing **SOC Level 1 training rooms** to learn the basics of cybersecurity and how a Security Operations Center (SOC) works. This is my introduction to blue team security and how threats are detected and handled in real environments.

 What I’m Learning

* What a Security Operations Center (SOC) does on a daily basis
* How to read and understand security logs
* How security alerts are created and reviewed
* Basics of phishing, malware, and suspicious activity
* How security teams decide if something is a real threat or a false alarm
* Simple incident response steps (identify, investigate, respond)

 Why I Chose SOC Level 1

SOC Level 1 focuses on fundamentals, which makes it a good starting point for beginners. This training helps me:

* Understand how cyber attacks are detected
* Learn common security terms and concepts
* Build confidence working with security tools
* Develop problem-solving and analytical thinking skills

Skills I’m Building

* Basic log analysis
* Identifying unusual or suspicious behavior
* Understanding alerts and security events
* Writing simple security notes and reports
* Thinking like a security analyst

Tools & Concepts Practiced

Log review and analysis

* Alert triage (deciding what is important)

* Security terminology and common attack methods

* Writing simple investigation notes

* Social engineering is an attack tatic that mmanipulates human physcology.
Some tactics include:
Impersonation
Phising attacks
malware
ect.

* Defending agaisnt these threats involes two tasks... Mitigation and Detection.
* Mitigation ( aims to prevent or reduce the chance of attacks )

* Every piece if software can have security flaws and just because you may not be the one to attacked something called supply chain can lead to everything being compromised.

* Even having software vulnerablities and once made public a CVE (common vulnerablities and exposures) number is assigned which its then attackers vs defenders as the defenders rush to update their system known as a patch.

Mitigation	

* Patch Management-	A process of tracking and patching the vulnerable systems significantly reduces the chance of a successful attack

* Training for IT-	If your IT knows the risks of misconfigurations, they are less likely to leave the systems unprotected

* Network Protection-	The system is much harder to breach if access to it is restricted to trusted people or IP addresses

* Antivirus Protection-	Same as with attacks on humans, a good antivirus can stop or at least detect many different attacks 

* LEARNING OBJECTIVES

* Familiarise with the concept of SOC alert
* Explore alert fields, statuses, and classification
* Learn how to perform alert triage as an L1 analyst
*Practice with real alerts and SOC workflows
* Prepare for SOC Simulator and SAL1 certification

* all system logs must be shipped to a security solution like SIEM or EDR both of which are alert management platforms most soc teams use.

* SOC L1 analysts are the first line of defence, and they are the ones who work with alerts the most. Depending on various factors, L1 analysts may receive zero to a hundred alerts a day, every one of which can reveal a cyberattack. Still, everyone in the SOC team is somehow involved in the alert triage:

* SOC L1 analysts:  Review the alerts, distinguish bad from good, and notify L2 analysts in case of a real threat

* SOC L2 analysts:  Receive the alerts escalated by L1 analysts and perform deeper analysis and remediation

*  SOC engineers:  Ensure the alerts contain enough information required for efficient alert triage

* SOC manager:  Track speed and quality of alert triage to ensure that real attacks won't be missed

Picking the right alert is different for every SOC team.
* Make sure wasnt already reviewed.
* Sort it by serverity(high,medium,low)
* Sort it by time(oldest to newest)

* You normally want to understand who is under threat(whats affected hostname, cloud, network, or website
* Note the action wether it was suspicious login, malware, phishing.
* Review  the surrounding events.\
* Use threat platforms or other resoures to verify

What i found interesting right now is while in the room i was given a task to first assign myself alerts. I had to correctly triaged the alert which made me really have to anazlyze the documents either downloded how much data was sent ect.

For example- Description:

* This rule detects 5 or more gigabytes of data sent from a single device to a single destination within a day, which may indicate data exfiltration to untrusted location.

Destination:*.zoom.us

Source IP:192.168.45.66

Source Network:UK04/MEETINGROOM

Sent Data:5.8 GB

Received Data:5.2 GB

However even though I got this inccorect without knowing looking at this more it was more than 5Gb of data sent however the location wasnt unkown it was through zoom. This data sent is very common especially through such a website. Even with the severity as critcal making it seem as somehting may be wrong somehting as simple as that is very easy to overlook.

What I ended up putting- Comment:

Not an unknown location was sent through zoom
And boom Correct!


Alert reporting:
Before closing or passing the alert to L2, you might have to report it. Depending on team standards and alert severity, instead of a short alert comment, you can be required to document your investigation in detail, ensuring all relevant evidence is included. 

Alert Escalation:
If the True Positive alert requires additional actions or deeper investigation, escalate it to the L2 analyst for further review following the agreed procedures. 










After finishing SOC Level 1, I plan to:

* Continue practicing with beginner security labs
* Learn more about SIEM tools and alert investigation
* Move into more advanced SOC or blue team training

