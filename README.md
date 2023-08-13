# Incident-handler-journal

In this project, I will review the details of a security incident and document the incident using my incident handler's journal. <br>
Throughout **Sound the Alarm: Detection and Response** course, I was given the opportunity to apply my documentation skills using my incident handler's journal. With this journal, I can record information about the experiences I will have analyzing security incident scenarios through the course activities.
<img src="images/detectionimage.png" width=100 align=right>

### Scenario 1

A small U.S. health care clinic specializing in delivering primary-care services experienced a security incident on a Tuesday morning, at approximately 9:00 a.m. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.

Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key. 

The attackers were able to gain access into the company's network by using targeted phishing emails, which were sent to several employees of the company. The phishing emails contained a malicious attachment that installed malware on the employee's computer once it was downloaded.

Once the attackers gained access, they deployed their ransomware, which encrypted critical files. The company was unable to access critical patient data, causing major disruptions in their business operations. The company was forced to shut down their computer systems and contact several organizations to report the incident and receive technical assistance.


| Date<br> 08/08/2023 <br>Tuesday 09:00 | Entry 1 |
| :--- | :--- |
| Description | Documenting a cybersecurity incident     |
|   Tools Used   | none     |
| The 5 Ws     | - **Who caused the incident?:** A recognized group of unethical hackers. <br> - **What happened?:** A ransomware security Insident <br> - **When did the incident occur?:** Tuesday 09:00 <br> - **Where did the incident happen?:** At a small US health clinic <br> - **Why did the incident happen?:** The incident happened because the attackers were able to gain access into the company's network by using targeted phishing emails, which were sent to several employees of the company. The emails contained malicious attachments that once downloaded gave control to the attackers. Once the attackers had control, they encripted critical files and leaft a note demanding a large sum of money.     |               
| Additional notes | 1. How can the company prevent future phishing attacks? <br> 2. Who should the company contact to report this incident? <br> 3. Where should the company seek help?     |


### Scenario 2

You are a level one security operations center (SOC) analyst at a financial services company. You have received an alert about a suspicious file being downloaded on an employee's computer. 

You investigate this alert and discover that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

You retrieve the malicious file and create a SHA256 hash of the file. You might recall from a previous course that a hash function is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint.

| Date<br> 08/13/23 | Entry 2 |
| :--- | :--- |
| Description     | Analyzing an artifact using VirusTotal     |
| Tools Used     |  VirusTotal    |
| Details     |  An employee received an email contining a file attachment, the employee downloads the file and miltiple unauthoried executable files appear on the employee's computer. An Intrusion Detection System (IDS) detects the files and sends out an alert.<br> Upon investigation of the file hash, it is descovered that the file hash was found to be MALICIOUS by over 50 vendors on VirusTotal.    |
| Additional notes     | SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b<br> Here is a timeline of the events leading up to this alert:<br>**1:11 p.m.:** An employee receives an email containing a file attachment.<br>**1:13 p.m.:** The employee successfully downloads and opens the file.<br>**1:15 p.m.:** Multiple unauthorized executable files are created on the employee's computer.<br>**1:20 p.m.:** An intrusion detection system detects the executable files and sends out an alert to the SOC.     |



<!--

column layout

| Date<br> | Entry  |
| :--- | :--- |
|      |      |
|      |      |
|      |      |
|      |      |

-->
