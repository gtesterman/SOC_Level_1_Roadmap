<h1>SOC Level 1 Roadmap</h1>
<h2>Description</h2>
Project consists of completing the SOC Level 1 Roadmap by TryHackMe. This roadmap prepares cybersecurity professionals for a level 1 security analyst position through practical walkthroughs and interactive rooms that simulate an enterprise SOC environment.
<br />
<h2>Applications Used</h2>

- <b>Vmware Workstation Pro (for Kali Linux VM)</b><br/>
- <b>PowerShell</b><br/>
- <b>Active Directory</b><br/>
- <b>Splunk Enterprise</b><br/>
- <b>Elastic Stack (ELK)</b><br/>
- <b>CyberChef<b><br/>
- <b>Wireshark</b><br/>


<h2>Environments Used </h2>

- <b>Windows 11</b><br/>
- <b>Ubuntu</b><br/>
- <b>Kali Linux</b><br/>

<h2>Modules</h2>


<h3>Blue Team Introduction</h3>


- <b>Junior Security Analyst Intro:</b> Read about the primary roles of a Security Operations Center (SOC), how each role of the SOC team operates, and discovered what a day in the life of a security analyst looks like. <br/><br/>


- <b>SOC Role in Blue Team:</b> Explored the purpose of the Blue Team and the career of a SOC Level 1 analyst. Reviewed the place of an internal SOC vs MSSP.<br/><br/>


- <b>Humans as Attack Vectors:</b> Learned the role of the human element in cybersecurity; why humans are targeted and common social engineering attacks such as phishing, malware downloads, and deepfakes. Reviewed sample cases of social engineering attacks from an IT Support perspective.<br/><br/>


- <b>Systems as Attack Vectors:</b> Explored roles, attacks, misconfigurations, and vulnerabilities of systems. Practiced mitigation techniques such as Patch Management, IT Training, and Antivirus Protection. Selected policies for a sample remediation plan.<br/><br/>
<br/>
<br/>


<h3>SOC Team Internals</h3>


- <b>SOC L1 Alert Triage:</b> Analyzed security events and alerts in a SIEM, learned the role of a level 1 SOC analyst in alert triage and investigated sample alerts in a SIEM simulator.<br/><br/>


- <b>SOC L1 Alert Reporting:</b> Learned how to properly report, escalate, and communicate about alerts that should be passed to level 2 analysts. Reviewed the report format to include the "who", "what", "where", "when", and "why" in alert reports.<br/><br/>


- <b>SOC Workbooks and Lookups:</b> Learned the purpose of an identity inventory and asset inventory such as Active Directory. Reviewed a network diagram of identity and asset inventory topics. Practiced building a SOC workbook/playbook in an interactive TryHackMe site.<br/><br/>


- <b>SOC Metrics and Objectives:</b> Reviewed concepts such as SLA, MTTD, MTTA, and MTTR. Learned about the importance of improving metrics such as a false positive rate. Practiced finding problematic metrics in TryHackMe's interactive lab and recommended improvement tasks for each scenario.<br/><br/>


- <b>Introduction to Phishing</b><br/>
<br/>
<br/>


<h3>Core SOC Solutions</h3>


- <b>Indroduction to EDR:</b> Learned the fundamentals of Endpoint Detection and Response (EDR). Reviewed capabilities of EDR solutions and what happens after detection. Investigated a sample EDR Dashboard on TryHackMe's interactive site.<br/><br/>


- <b>Introduction to SIEM:</b> Reviewed the core functions of a Security Information and Event Management system (SIEM), including the centralization of log sources and how alerting and dashboards help with correlating data about security events. Discovered log sources in Windows Event Viewer and Linux Cron Logs. Investigated events and alerts in TryHackMe's interactive SIEM site, categorizing them as true positive or false positive.<br/><br/>


- <b>Splunk: The Basics:</b> Learned the components of Splunk, such as Splunk Forwarder, Splunk Indexer, Search Head, Splunk Bar, and Apps Panel. Created an index of VPN logs in a Splunk Enterprise instance. Correlated the data based on username, IP address, and country.<br/><br/>


- <b>Elastic Stack: The Basics:</b> Learned how SOC analysts use Elastic Stack (ELK) for log investigations. Created an index in ELK to display logs for vpn connections and filtered logs to show data such as IP addresses, usernames, and locations. Reviewed the basiscs of KQL to perform more advanced searches in the index. Created visualizations and custom dashboards to display visualized data in ELK.<br/><br/>


- <b>Introduction to SOAR:</b> Explored how SOC teams use Security Orchestration, Automation, and Response (SOAR) to unify security tools and operate within a single interface. Used the TryHackMe interactive site to create playbooks for a sample workflow.<br/><br/>
<br/>
<br/>


<h3>Core SOC Solutions</h3>


- <b>Pyramid of Pain:</b> Learned the Pyramid of Pain concept from the perspectives of a threat hunter, incident responder, and SOC analyst. Used VirusTotal and any.run to review hashing algorithms, IP addresses, domain names, host artifacts, network artifacts, and TTPs. Used the TryHackMe interactive website to complete an activity to reinforce concepts.<br/><br/>


- <b>Cyber Kill Chain:</b> Explored the attack phases of the Cyber Kill Chain including reconnaissance, weaponization, delivery, exploitation, installation, command & control, and actions on objectives. Completed a lab on the TryHackMe website for proof of concept.<br/><br/>


- <b>Unified Kill Chain:</b> Learned critical cybersecurity concepts including threat modeling and kill chain frameworks such as Unified Kill Chain (UKC), Lockheed Martin, and MITRE ATT&CK. Completed a scenario in the TryHackMe website for proof of concept.<br/><br/>


- <b>MITRE:</b> Reviewed MITRE's cybersecurity frameworks and resources such as the MITRE ATT&CK Framework, Cyber Analytics Repository (CAR), and MITRE D3FEND. Learned about the various projects the MITRE organization designed for cyber security professionals.<br/><br/>


- <b>Summit:</b> Used the concepts of the Pyramid of Pain and MITRE to analyze sample malware files in a simulated internal lab environment. Followed each level of the Pyramid of Pain to prevent the malware from executing in the environment.<br/><br/>

- <b>Eviction:</b> Analyzed TTPs of the APT group APT28. Used the MITRE ATT&CK Navigator to identify TTPs in an internal environment and stop the simulated threat actor from intruding into the netowrk.<br/><br/>
<br/>
<br/>


<h3>Phishing Analysis</h3>


- <b>Phishing Analysis Fundamentals:</b>  Analyzed the basic components of phishing emails. Reviewed email message protocols such as SMTP, POP3, and IMAP. Used phishing emails in a controlled lab environment to review email headers, email addresses, and source code. Determined the different types of malicious emails such as spam, phishing, spear phishing, whaling, smishing, and vishing.<br/><br/>


- <b>Phishing Emails in Action:</b> Reviewed actual phishing emails in a lab enviornment to find malicious URLs, TTPs, and attachments sent by threat actors.<br/><br/>


- <b>Phishing Analysis Tools:</b> Analyzed more samples of real phishing emails using a controlled lab environment. Used tools such as message headers, VirusTotal, CyberChef, and AnyRun to report on three different phishing cases.<br/><br/>


- <b>Phishing Prevention:</b> Reviewed core email security controls such as SPF, DKIM, DMARC, and S/MIME. Used Wireshark filters to search through SMTP response codes and find email attachments.<br/><br/>


- <b>The Greenholt Phish:</b> Used an Ubuntu lab enviornment to analyze and report on a phishing email sample. Documented the originating email address, IP, and IP owner. Analyzed the email attachment to reveal file size, extention, and hash value (SHA256).<br/><br/>


- <b>Snapped Phish-ing Line:</b> Completed a challenge scenario based off a real-world phishing campaign. Connected to an isolated VM environemnt and analyzed the emails for key indicators such as IP addresses, malicious URLs, files of the phishing kit, and email addresses used by the adversary.<br/><br/>


</b><br/>
