# Honeypot Assignment

**Time spent:** **3** hours spent in total, around 50 with the wait for attacks

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** I used Google Cloud Services to deploy my virtual isntances

<img src="GCInstance.png">

### Dionaea Honeypot Deployment (Required)

**Summary:** It detects shell code attacks

<img src="dionaea-honeypot.gif">

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

*Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.*

### Deploying Additional Honeypot(s) (Optional)

#### Amun Honeypot

**Summary:** According to the description, it is roughly the same as Dionaea

<img src="amun-honeypot.gif">

#### Cowrie Honeypot

**Summary:** This logs brute force attacks and records the username and password used

<img src="cowrie-honeypot.gif">

### Malware Capture and Identification (Optional)

#### X Malware

**Summary:** How did you find it? Which honeypot captured it? What does each malware do?

MD5 Hash: *Run `md5sum` on the file and record the hash here.*

SHA1 Hash: *Run `sha1sum` on the file and record the hash here.*

<img src="x-malware.gif">

## Notes

Describe any challenges encountered while doing the assignment.
