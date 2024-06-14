# Blue Team Level 1 Write-Up 

Last year, I took the course BTL1 and passed the exam. Since there aren't many write-ups without marketing talk on the internet I decided to write a quick review on this certification.

The BTL1 course consists of the following topics ("Domains"), which I will cover in-depth:

1. Introduction
2. Security Fundamentals
3. Phishing Analysis
4. Threat Intelligence
5. Digital Forensics
6. Security Information and Event Monitoring
7. Incident Response
8. BTL1 Exam Preparation

In total, there are 24 labs, 32 quizzes, and 309 topics. When you've purchased the course, you get 4 months of training access and 12 months of exam access. You also get 100 hours of lab access, of which I have used about 10. For context, a lab is a kind of HTB environment in which you have to answer questions. Quizzes are at the end of a section (multiple topics) within a domain.
The Introduction and exam preparation topics will not be highlighted separately since they do not contain much content.

---

## Security Fundamentals

Not very interesting to me; maybe if you're completely new to Information Security, this topic is interesting to you. It covers topics such as Networking 101, Security Controls (What is an EDR/AV, Vulnerability scanning.) This topic contains 0 labs.

---

## Phishing Analysis

Phishing is explained here in detail. The intents behind the mails and how to spot them are also covered. Technical tricks used by attackers, such as typosquatting, attachments, and email headers (how to get the sender's IP, for instance), are highlighted here. The lab is an exercise in which you have to categorize phishing emails and gather artifacts such as sender IP, hostname, etc.

---

## Threat Intelligence

Starts with the most basic part of TI. What is an IOC, APT, MITRE ATT&CK, Cyber Kill Chain, OSINT, Traffic Light Protocol? The lab was a starting guide to MISP and how to use it.

---

## Digital Forensics

Most time-intensive domain in my opinion. It starts with how Forensics works and Forensics techniques such as file carving, metadata, hashing, and integrity. Labs are for learning to use the tools: FTK imager, KAPE.
We also get an introduction to Windows and Linux Forensics, such as LNK files, Recycle Bin, Windows Event Logs, Passwd, and Shadow files. Included is also a Volatility 3 guide; however, this tool is not included in the exam. In the end, we get to know Autopsy, a tool you need to use in the exam.

---

## Security Information and Event Monitoring

Starts with what a SIEM is, platforms, log aggregation, and more event log analysis. Introduction to Sigma rules. Followed by a Splunk crash course (queries, dashboards, etc.) The 4 labs are borrowed from the Boss of the SOC exercise, which I had already completed a while back, so that was that. The course does take you by the hand, which is a plus for beginners.

---

## Incident Response

Starts with what a CERT and CSIRT are. Gives prevention and detection best practices, such as DMZ, EDR, Firewalls. Here we also get a Wireshark lab and an introduction to DeepBlueCLI, a script we need to use in the exam. After that, a starting guide to TheHive, and how to handle an incident (taking forensics images). In the end, more Mitre ATT&CK.

---

## The exam

*Disclaimer: I cannot go into too much detail since I'm under an NDA and don't want to lose my certification.*

After skimming through the course as quickly as possible, I started the exam, for which you get 24 hours. In the end, I used 6 hours but did not manage to get the gold coin (90%+ correct), unfortunately :(. I have to say I was pleasantly surprised; the exam guides you through a very realistic incident response scenario in which you have to combine mostly your Splunk/Wireshark/Autopsy knowledge and really have to dive deep into Splunk to get the correct answer. You really need to understand the logs and have to create good queries to pass the exam and you need good knowledge on how for instance C2 frameworks operate.

---

## Final Thoughts

The exam was comparable to a very thorough SOC investigation and definitely on par with the level which can be encountered in a SOC. I do, however, think that I could've passed the exam without doing the course at all, which was a bit of a disappointment. The course is very broad but as a result, a bit basic in my opinion. Every mid-level/senior SOC analyst should be able to pass this easily, so I can recommend this course to junior Analysts, as it is a good foundation to build upon. For mid-level/senior analysts, I do not think that this certification is challenging enough.