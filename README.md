# Pranshu Verman

### Cybersecurity Analyst | IAM | SOC Operations | VAPT | AI Security

Cybersecurity professional with experience in Identity and Access Management (IAM), vulnerability assessment, web application security, Linux administration, and security-focused projects. I enjoy investigating security risks, improving access governance, analyzing network behavior, and building practical security tools.

- **Primary Domains:** IAM, SOC Operations, VAPT, Network Security, Linux Security
- **Research Interest:** AI/LLM Security and Model Forensics
- **Location:** Madhya Pradesh, India
- **Portfolio:** [zerocyb3r.netlify.app](https://zerocyb3r.netlify.app/)
- **GitHub:** [PranshuCyb3r](https://github.com/PranshuCyb3r)
- **LinkedIn:** [Pranshu Verman](https://www.linkedin.com/in/pranshu-verman-2b39b9241/)

---

## About Me

My cybersecurity experience combines identity governance, vulnerability assessment, network analysis, and Linux system administration.

As an IAM Analyst, I worked on identity lifecycle processes, access provisioning and de-provisioning, role management, and access reviews. My cybersecurity internships gave me hands-on experience with security assessment workflows and web application testing. I also have experience with Linux administration and Ansible automation.

Alongside my professional background, I build independent projects to explore real-world security problems, including automated web vulnerability scanning, AI model forensics, and industrial control system security.

### Areas I Work On

- Identity lifecycle management and access governance
- User provisioning, deprovisioning, and role-based access
- Vulnerability assessment and web application security testing
- Network reconnaissance and traffic analysis
- Security tools, Linux administration, and automation
- AI model security research and potential backdoor analysis
- Industrial and operational technology security concepts

---

## Technical Skills

| Category | Skills and Tools |
|---|---|
| IAM & Access Governance | Identity lifecycle, provisioning, de-provisioning, role management, access reviews |
| Vulnerability Assessment | VAPT, reconnaissance, vulnerability identification, security findings documentation |
| Security Tools | Burp Suite, Nmap, Wireshark, Nessus, OpenVAS, Metasploit |
| Network Security | Port scanning, service discovery, traffic inspection, network analysis |
| Linux & Administration | Linux, RHEL, user management, system configuration, server monitoring |
| Automation | Ansible |
| Programming & Scripting | Python, C++, JavaScript, HTML, CSS |
| AI Security Research | PyTorch, SafeTensors, Hugging Face ecosystem, model architecture inspection |
| Web & Application Development | HTML, CSS, JavaScript, PHP, Firebase-related web application components |

---

## Featured Projects

### 1. NeuroFence — LLM Weight Poisoning & Backdoor Scanner

**Domain:** AI Security · LLM Security · Model Forensics  
**Repository:** [NeuroFence-scanner](https://github.com/PranshuCyb3r/NeuroFence-scanner)

NeuroFence is an offline AI security research project that inspects local Large Language Model (LLM) checkpoints for suspicious weight patterns and potential backdoor-related activation behavior before deployment.

The project focuses on examining model files and architecture, monitoring activation behavior, and investigating whether specific prompts are associated with unusual model responses or internal activation patterns.

**Key capabilities and development areas**

- Local `.safetensors` checkpoint loading and model metadata inspection.
- SHA-256 integrity verification and checkpoint validation.
- Transformer architecture inspection, including layers and projection tensors.
- PyTorch hook-based activation monitoring and telemetry.
- Adversarial prompt generation and trigger-oriented testing.
- Statistical anomaly analysis using activation measurements.
- Heatmap visualization and layer-level inspection.
- PDF-based forensic reporting.

**Technology stack:** Python, PyTorch, SafeTensors, Hugging Face ecosystem, NumPy, CustomTkinter.

**Current focus:** Improving GUI-to-model integration, activation monitoring, and the reliability of the forensic workflow.

**Important limitation:** Unusual activation values alone do not prove that a model is malicious or backdoored. Findings require controlled testing and further validation.

---

### 2. Web Vulnerability Scanner

**Domain:** Application Security · VAPT  
**Repository:** [webvulnebilityscanner](https://github.com/PranshuCyb3r/webvulnebilityscanner)

A Python-based security assessment tool designed to bring multiple reconnaissance and web security utilities into one workflow. It helps examine a target's exposed services, web technologies, DNS information, and potential vulnerability indicators.

**Key features**

- Open-port and service discovery.
- Web application fingerprinting.
- DNS enumeration and subdomain discovery.
- SSL/TLS security checks.
- Directory and file enumeration.
- CMS identification for platforms such as WordPress, Joomla, and Drupal.
- Integration with multiple open-source security tools.

**Tools referenced in the repository:** Nmap, Nikto, Wafw00f, DNSRecon, DNSWalk, Wapiti, WhatWeb, Amass, Dirb, XSStrike and XSSer.

**Technology stack:** Python and command-line security utilities.

**Learning outcomes:** Security reconnaissance, tool integration, understanding web attack surfaces, and organizing assessment workflows.

**Responsible use:** Use only on systems you own or have explicit permission to assess.

---

### 3. Voltguard Firewall — Industrial Control System Security

**Domain:** OT Security · ICS/SCADA · Industrial Network Defense  
**Repository:** [Voltguard-Firewall](https://github.com/PranshuCyb3r/Voltguard-Firewall)

Voltguard explores a physics-aware security approach for industrial control systems. Instead of examining only whether a network packet is correctly formatted, the project focuses on whether an industrial control command appears consistent with defined physical and operational safety constraints.

The concept targets environments where unsafe commands may affect physical equipment, even when the network traffic itself looks legitimate.

**Project objectives and components described in the repository**

- Inspect industrial protocol traffic such as Modbus/TCP and related OT protocols.
- Parse industrial communication frames.
- Evaluate control commands against physical or operational constraints.
- Identify potentially unsafe control actions.
- Support a deterministic decision-making approach for industrial traffic.
- Explore fail-safe behavior and operator-oriented security monitoring.

**Technologies referenced in the project:** C++, Python, protocol parsing, and physics-based safety logic. The repository also describes broader planned or conceptual subsystems for industrial traffic interception and decision-making.

**Security objective:** Explore how cyber defenses can account for the possible physical consequences of industrial commands, not just packet syntax.

**Research note:** This is an engineering project, and any performance, safety, or deployment claims should be validated through appropriate testing before real-world industrial use.

---

### 4. VillanStudio — Website and Booking Interface

**Domain:** Web Development · User Interface  
**Repository:** [villanstudio](https://github.com/PranshuCyb3r/villanstudio)  
**Website:** [villanstudio.vercel.app](https://villanstudio.vercel.app/)

VillanStudio is a website project containing pages and components for a web-based user experience, including a main page, booking interface, and login-related pages.

**Repository components**

- Main website interface.
- Booking page.
- Login and authentication-related pages.
- CSS styling and image assets.
- PHP login-related component.

**Technology visible in the repository:** HTML, CSS, PHP, and web assets.

**Learning outcomes:** Structuring web pages, building user-facing interfaces, organizing frontend assets, and exploring the integration of web forms with server-side components.

The repository structure alone does not establish that every authentication or booking workflow is production-ready; those functions should be assessed independently.

---

### 5. Pranshu — Personal Portfolio Web Application

**Domain:** Portfolio Development · Web Application  
**Repository:** [Pranshu](https://github.com/PranshuCyb3r/Pranshu)  
**Portfolio:** [pranshu-Portfolio](https://zerocyb3r.netlify.app/)

This repository contains a personal web application with frontend pages, styling, JavaScript assets, and Firebase-related configuration and security-rule files.

**Components visible in the repository**

- Main website and hub pages.
- Login and registration pages.
- CSS and JavaScript files.
- Firebase-related configuration files.
- Firestore security rules.
- Package configuration for local development.

**Technology visible in the repository:** HTML, CSS, JavaScript, Node.js tooling, and Firebase-related components.

**Learning outcomes:** Web application organization, separating frontend assets, authentication-related interface development, and working with backend service configuration.

**Security considerations:** Firebase configuration, authentication flows, database rules, and environment secrets should be reviewed before deployment. Sensitive credentials must not be committed to a public repository.

---

## Professional Experience

### Identity & Access Management (IAM) Analyst
**MNB Soft Solution | August 2025 – June 2026**

- Supported identity lifecycle management and access provisioning/de-provisioning processes.
- Worked with user roles and access management activities.
- Supported user access reviews and identity governance processes.
- Contributed to access-control practices and security-related operational workflows.

### Cybersecurity Intern
**Pinak Infosec C9LAB | April 2024 – June 2024**

- Gained practical exposure to vulnerability assessment and web application security testing.
- Assisted with identifying potential security weaknesses and understanding associated risks.
- Supported security assessment activities and findings documentation.

### Cybersecurity Intern
**Samyak IT Solutions | February 2024 – June 2024**

- Gained exposure to practical cybersecurity activities and assessment workflows.
- Developed familiarity with security concepts, testing practices, and structured technical work.

### Linux & Ansible Administrator Intern
**Rostris Infotech | January 2022 – April 2022**

- Worked with Linux system administration in RHEL environments.
- Gained experience with user management and system configuration.
- Supported routine administration and server monitoring tasks.
- Developed familiarity with Ansible-based automation.

---

## Current Learning & Development

My ongoing work focuses on building practical security tools and improving my technical depth.

- **NeuroFence:** Working on AI model forensics, GUI integration, and activation-based analysis of local LLM checkpoints.
- **Web Security:** Exploring automated reconnaissance and vulnerability assessment workflows.
- **OT Security:** Developing my understanding of industrial protocol inspection and physics-aware security concepts through Voltguard.
- **IAM & Governance:** Continuing to strengthen identity lifecycle, role management, and access review knowledge.
- **Linux & Automation:** Building on Linux administration and Ansible experience.

Project status may change as development and validation continue; individual repositories contain the latest implementation details.

---

## Certifications

- Google Cybersecurity Certificate
- Ethical Hacking Essentials (EHE) — EC-Council
- Android Bug Bounty Hunting — EC-Council
- Introduction to Cybersecurity — Cisco
- Cybersecurity Essentials — Cisco

---

## Education

**Master of Computer Applications (MCA)**  
AKS University, Satna, Madhya Pradesh | 2022–2024

**Bachelor of Computer Applications (BCA)**  
AKS University, Satna, Madhya Pradesh | 2019–2022

---

## Connect With Me

I am interested in opportunities and collaboration related to cybersecurity analysis, SOC operations, IAM, vulnerability assessment, network security, Linux administration, and AI security research.

- **Email:** [pranshuverman12@gmail.com](mailto:pranshuverman12@gmail.com)
- **LinkedIn:** [Pranshu Verman](https://www.linkedin.com/in/pranshu-verman-2b39b9241/)
- **GitHub:** [PranshuCyb3r](https://github.com/PranshuCyb3r)
- **Portfolio:** [zerocyb3r.netlify.app](https://zerocyb3r.netlify.app/)

---

*Learn continuously. Investigate responsibly. Build securely. / ZeR0CyB3r* 
