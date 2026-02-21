# IT_360_Final_Project_Spring_2026
IT 360 Group Project Repo 


## Team Members
- Jasmine Dhamers
- Lana Caculovic

## Project Idea 

### 1. Project Overview 

Brute force attacks on Secure Shell (SSH) services are a common security concern on Linux-based systems and networks. The attacks occur when attackers attempt unauthorized access via multiple authentication requests. The main goal of this project is to gain hands-on experience in the identification, analysis, and response to Secure Shell brute force attacks using the Splunk SIEM tool. Through the analysis of Secure Shell logs, the project will be able to show how security teams use log analysis to identify security threats. 

### 2. Objectives & Deliverables 

At the end of this project, we will be able to: 

- Identify patterns for SSH brute force attacks based on the logs. 
- Ingest and normalize the SSH authentication logs into the Splunk platform. 
- Develop Splunk Processing Language (SPL) to identify failed login attempts and suspicious IP addresses. 
- Develop Splunk dashboards to visualize the attack patterns. 
- Develop basic alert rules for identifying brute force attacks.
- Utilize Illinois State Generative AI Tool to automate the explanation of complex SPL query results and provide context-aware mitigation strategies.

### 3. Project Scope 

The project will cover: 

- Establishing a Splunk infrastructure for log consumption. 
- Importing and parsing SSH authentication logs. 
- Identifying failed and successful login attempts. 
- Identifying repeated failed login attempts from individual IP addresses. 
- Visualizing patterns of attacks with Splunk dashboards.  
- Exploring possible solutions such as rate limiting, key-based authentication, and IP blocking. 
- Considering the practical applicability and potential shortcomings of log-based intrusion detection.

### 4. Project Plan 

Week 1–2: Introduction and Setup 

- Install and configure Splunk Free. 
- Review SSH authentication mechanisms and common attack patterns. 
- Import sample SSH log files into Splunk. 

Week 3–5: SSH brute force detection

- Identify failed and successful SSH login events. 
- Write SPL queries to detect multiple failed attempts from the same IP. 
- Analyze time-based patterns to identify brute force behavior. 

Week 6–8: Dashboard Development & Analysis

- Create dashboards visualizing failed login attempts, top source IP addresses, and attack activity over time to identify potential brute-force attacks.
- Refine queries for accuracy and performance.

Week 9–12: Mitigation Techniques 

- Configure Splunk alerts for excessive failed login attempts.
- Utilize Illinois State's Generative AI tool to perform contextual analysis on flagged IP addresses, correlating SSH attack patterns with known threat behaviors to generate an automated Risk Score for each incident.
- Document detection thresholds and false positives. 
- Research and discuss SSH hardening techniques.

Week 13-14: Final Touches, Reporting & Reflection 

- Compile findings into a professional SIEM analysis report. 
- Include screenshots of dashboards and SPL queries. 
- Reflect on lessons learned and real-world applicability of SIEM tools.

### 5. Tools and Resources 
- Splunk Free (SIEM) 
- SSH authentication log files (Linux) 
- Illinois State University Proxmox Virtual machine (test environment) 
- Documentation resources: Splunk SPL documentation, Linux SSH authentication documentation
- Illinois State Generatie AI Tool

### 6. Expected Outcomes 
- Gain practical experience using Splunk for security monitoring. 
- Understand the patterns of brute force attacks in SSH log data. 
- Acquire the skills needed for basic analysis and detection using a SIEM system.

### Conclusion: 

The objective of this project is to gain hands-on experience in security monitoring using a SIEM solution, and it does so by specifically focusing on the detection of SSH brute force attacks. The skills gained in this project are relevant in a cybersecurity role. 
