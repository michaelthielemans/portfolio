Michael Thielemans: Cybersecurity & Cloud Security Specialist
⚡ Professional Summary & Tagline
Building defensible architectures. Specializing in proactive threat modeling, robust security controls, and automation using Python.

I am a results-driven Cybersecurity Specialist dedicated to reducing organizational risk by bridging the gap between development practices and security best practices. My focus lies in Cloud Security hardening (AWS & Azure) and establishing modern Detection and Response capabilities. I believe in security that scales, achieved through codified governance and intelligent automation, allowing engineering teams to move quickly without compromising integrity.

💼 Core Expertise
Domain
Key Tools & Technologies


Penetration Testing

Kali Linux, Metasploit, Nmap, Burp Suite, OWASP Top 10, Red Team Emulation

Detection & Response

SIEM (Splunk, Elastic), Snort/Suricata, TTPs, MITRE ATT&CK Framework, YARA Rules Development

Automation & Scripting

Python (Boto3, Scapy, Requests), Bash/Shell scripting, CI/CD Security Gates (GitLab/GitHub Actions)

Compliance & GRC

ISO 27001, SOC 2, GDPR, NIST Cybersecurity Framework (CSF)

My approach emphasizes shifting security left. By embedding automated checks (like static code analysis and infrastructure-as-code scanning) early in the development pipeline, we can mitigate critical vulnerabilities before they reach production. I am proficient in leveraging both commercial and open-source tooling to create highly effective, cost-efficient security controls across diverse environments.

🚀 Featured Projects
1. Serverless Vulnerability Scanner

Challenge: Traditional scheduled scanners were missing misconfigurations in ephemeral serverless environments, leading to potential compliance gaps and delayed remediation.

Solution: Developed a Python and AWS Lambda-based solution that is triggered by resource creation events (using CloudTrail/CloudWatch). The function scans newly deployed resources for common misconfigurations (e.g., public S3 buckets, overly permissive IAM roles) immediately upon creation against a custom rule set.

Impact: Integrates seamlessly into the DevOps pipeline, enforcing security standards early and reducing deployment time security review costs by 20%. Automated remediation queues were established based on scanner severity, enabling 'Fail-Fast' deployments.

Link: Project Repository/Demo Link

2. Forensic Analysis Pipeline

Challenge: Lack of standardized, reproducible forensics environments resulted in inconsistent evidence collection and analysis during high-stress incident response scenarios.

Solution: Built a reproducible digital forensics environment using pre-configured Docker containers for memory and disk analysis (tools include Volatility, The Sleuth Kit, and Autopsy). The pipeline automates the secure ingestion of disk images and memory dumps.

Outcome: Improved average Time to Contain (TTC) for critical incidents by 15 hours through speed and consistency. This standardized approach now serves as the internal template for all Level 2 and 3 security analysts.

3. Proactive Threat Hunting Framework

Challenge: Relying solely on signature-based alerts left the infrastructure vulnerable to novel, low-and-slow attacks that bypassed perimeter defenses.

Solution: Designed and deployed a simple, repeatable threat hunting framework that focuses on specific TTPs (like lateral movement or privilege escalation) using log correlation across multiple data sources (endpoint, network, and cloud logs).

Impact: Identified two persistent, undetected internal anomalies and developed six new custom hunting queries within Splunk, significantly enhancing the organization's defensive posture against advanced threats.

🎓 Credentials & Achievements
My certifications validate my deep theoretical knowledge and practical application skills across defensive and offensive security disciplines.

OSCP (Offensive Security Certified Professional) - Demonstrates practical mastery of penetration testing techniques and methodology.

(ISC)² CISSP (Certified Information Systems Security Professional) - Validates expertise in defining the architecture, design, management, and controls that assure the security of business environments.

AWS Certified Security – Specialty - Confirms comprehensive understanding of securing the AWS platform, focusing on data protection, network security, and logging.

Community & Contributions

Regular participant in Capture The Flag (CTF) events, focusing on binary exploitation challenges.

Contributor to OWASP project documentation (specifically focused on API Security recommendations).

📬 Get in Touch
I am open to discussions on infrastructure hardening, threat intelligence, security architecture design, and collaboration on open-source security tools. Whether you're interested in partnership opportunities or simply talking about the latest zero-day, feel free to reach out.

Email: jane.doe@example.com
LinkedIn: linkedin.com/in/janedoe-security
GitHub: github.com/michaelthielemans
