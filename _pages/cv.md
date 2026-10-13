---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 2
description: My full CV. Prefer a shorter copy? Download the two-page resume instead.
---
<style>
.resume-doc { --ink:#1b1f24; --muted:#56606b; --accent:#0b5cad; --rule:#d5dbe1; --soft:#f1f5f9; }
.resume-doc, .resume-doc * { box-sizing: border-box; }
.resume-doc { font-family: "Inter", "DejaVu Sans", sans-serif; color: var(--ink); font-size: 9.4pt; line-height: 1.42; margin: 0; }
.resume-doc header { border-bottom: 2px solid var(--accent); padding-bottom: 8pt; margin-bottom: 10pt; }
.resume-doc h1 { font-size: 22pt; font-weight: 700; margin: 0; letter-spacing: -0.2pt; }
.resume-doc .tagline { font-size: 10.8pt; font-weight: 600; color: var(--accent); margin: 2pt 0 5pt; }
.resume-doc .contact { font-size: 8.8pt; color: var(--muted); }
.resume-doc .contact span + span::before { content: "  ·  "; color: var(--rule); }
.resume-doc h2 { font-size: 10.2pt; text-transform: uppercase; letter-spacing: 1pt; color: var(--accent); margin: 14pt 0 5pt; padding-bottom: 2pt; border-bottom: 1px solid var(--rule); font-weight: 700; page-break-after: avoid; }
.resume-doc h3 { font-size: 9.8pt; margin: 8pt 0 2pt; font-weight: 700; page-break-after: avoid; }
.resume-doc p { margin: 0 0 5pt; }
.resume-doc .skills div { margin-bottom: 3pt; }
.resume-doc .skills b { font-weight: 600; }
.resume-doc .job { margin-bottom: 11pt; }
.resume-doc .jobhead { display: flex; justify-content: space-between; align-items: baseline; page-break-after: avoid; }
.resume-doc .role { font-weight: 700; font-size: 10.4pt; }
.resume-doc .org { font-weight: 600; color: var(--muted); }
.resume-doc .dates { font-size: 8.8pt; color: var(--muted); white-space: nowrap; }
.resume-doc .context { font-style: italic; color: var(--muted); margin: 2pt 0 3pt; }
.resume-doc .lbl { font-weight: 600; color: var(--accent); font-size: 8.6pt; text-transform: uppercase; letter-spacing: 0.5pt; margin: 4pt 0 1pt; page-break-after: avoid; }
.resume-doc ul { margin: 2pt 0 0; padding-left: 13pt; }
.resume-doc li { margin-bottom: 2.4pt; }
.resume-doc li::marker { color: var(--accent); }
.resume-doc .subrole { font-weight: 600; font-size: 9.8pt; margin-top: 5pt; }
.resume-doc .tech { font-size: 8.7pt; color: var(--muted); margin-top: 3pt; }
.resume-doc .tech b { color: var(--ink); font-weight: 600; }
.resume-doc .case { background: var(--soft); border-left: 3px solid var(--accent); padding: 6pt 9pt; margin: 0 0 8pt; page-break-inside: avoid; }
.resume-doc .case .t { font-weight: 700; }
.resume-doc .case .w { color: var(--muted); font-size: 8.7pt; }
.resume-doc .case p { margin: 2pt 0 0; }
.resume-doc .case b.k { color: var(--accent); font-weight: 600; }
.resume-doc .quote { margin: 0 0 7pt; page-break-inside: avoid; }
.resume-doc .quote q { font-style: italic; }
.resume-doc .quote .who { display: block; color: var(--muted); font-size: 8.6pt; margin-top: 1pt; }
.resume-doc .two { display: grid; grid-template-columns: 1fr 1fr; column-gap: 20pt; }
.resume-doc a { color: inherit; text-decoration: none; }
.resume-doc { background:#fff; color:var(--ink); max-width: 8.5in; margin: 0 auto; padding: 0.6in 0.65in; box-shadow: 0 2px 14px rgba(0,0,0,.18); border-radius: 4px; font-size: 10.5pt; }
.resume-doc h1 { color: var(--ink); }
.resume-doc a { color: var(--accent); }
.resume-doc .two { display:grid; }
@media (max-width: 700px) { .resume-doc { padding: 20px 16px; } .resume-doc .jobhead { flex-direction: column; } .resume-doc .two { grid-template-columns: 1fr; } }
.cv-actions { max-width: 8.5in; margin: 0 auto 16px; display:flex; gap:10px; flex-wrap:wrap; }
</style>
<div class="cv-actions">
<a class="btn btn-sm z-depth-0" role="button" href="{{ '/assets/pdf/Benjamin_McCulloch_Resume_Full.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf"></i> Download full CV (PDF, 8 pages)</a>
<a class="btn btn-sm z-depth-0" role="button" href="{{ '/assets/pdf/Benjamin_McCulloch_Resume.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf"></i> Download 2-page resume</a>
</div>
<div class="resume-doc">
<header>
<h1>Benjamin Saul McCulloch</h1>
<div class="tagline">Senior DevSecOps &amp; Site Reliability Engineer · Cloud Security Lead</div>
<div class="contact"><span>Mexico City, Mexico (Remote)</span><span>benjaminsaulmcculloch@gmail.com</span></div>
<div class="contact"><span>linkedin.com/in/benjamin-saul-mcculloch</span><span>github.com/Benjamin-Saul-1989</span></div>
</header>
<h2>Summary</h2>
<p>Senior DevSecOps, SRE and cloud security engineer with 15+ years of experience making Azure, AWS and GCP platforms secure, reliable and cheaper to run. I work across the whole stack, from the network and the identity layer up through CI/CD, Kubernetes, observability and incident response, and I am happiest when I am automating away the repetitive work that slows teams down.</p>
<p>At Wolters Kluwer SureTax, a cloud tax engine processing millions of calculations a day, I cut mean time to recovery by 65% and mean time to remediation by 70%, and reduced Azure costs by 30% and then a further 25%. At AvidXchange I led enterprise monitoring that took recurring service failures from roughly one every three days to a handful a year. At Avertium I traced a live holiday intrusion to its entry point across 12 sites so the team could evict the attackers.</p>
<p>Today I lead Cyber Security, Technical Accounts and DevOps at Salvo Software, a multi-country engineering company, where I run the AI program for 50 developers, own CI/CD and security for three development teams (cutting the time between versions from 30 days to 10), and handle every security incident. I also freelance as a security consultant and volunteer as a cybersecurity and self-hosting instructor in Mexico City. Native English speaker (Australian), conversational Spanish, based in Mexico for 13 years.</p>
<h2>Core Skills</h2>
<div class="skills">
<div><b>Cloud:</b> Microsoft Azure (AKS, Azure SQL, Cosmos DB, Front Door, Application Gateway, Key Vault, API Management, Service Bus, App Service, Logic Apps, Container Registry, Azure Policy, Chaos Studio), AWS (compute, storage, serverless, Bedrock), Google Cloud Platform (Compute Engine, IAM, storage, serverless)</div>
<div><b>Containers &amp; Virtualization:</b> Kubernetes, AKS, Helm, Docker, Docker Compose, Proxmox, Hyper-V, VMware ESXi, bubblewrap sandboxing</div>
<div><b>Infrastructure as Code:</b> Terraform (reusable modules), Ansible, PowerShell DSC, Azure Policy, policy as code</div>
<div><b>CI/CD:</b> Azure DevOps (Pipelines, Repos, Boards), GitHub, GitHub Actions, Jenkins, TeamCity, Octopus Deploy, Bitbucket, blue-green and zero-downtime releases, branching strategy and release design</div>
<div><b>DevSecOps:</b> SonarQube (SAST), DAST, container, secret and dependency scanning, automated CVE scanning of builds, secure coding standards, threat modeling, OWASP Top 10 / ASVS</div>
<div><b>Security Operations:</b> Microsoft Sentinel, Defender XDR, Defender for Endpoint, Defender for Identity, Defender for Office 365, Defender for Cloud, CrowdStrike Falcon, SentinelOne, incident response, threat hunting, phishing simulation (Attack Simulation Training)</div>
<div><b>Identity &amp; Data:</b> Entra ID, Conditional Access, PIM, RBAC, Active Directory, Entra Connect, Okta, Duo, Google Workspace SSO/SAML, FIDO2 MFA, 1Password, Microsoft Purview (DLP, sensitivity labels), Intune, Autopilot</div>
<div><b>Offensive Security:</b> Burp Suite, OWASP ZAP, Nmap, Masscan, Metasploit, Kali Linux, Nessus, Qualys, OpenVAS, AI red-teaming with PyRIT and the OWASP LLM Top 10</div>
<div><b>SRE &amp; Observability:</b> SLOs and error budgets, Datadog, Dynatrace, Azure Monitor, Application Insights, Log Analytics, Grafana, Prometheus, Nagios, PagerDuty, Elasticsearch, chaos engineering, disaster recovery, blameless post-mortems</div>
<div><b>Networking:</b> Ubiquiti UniFi, VLANs, firewall rules, NSGs, VPN, WireGuard, Tailscale, Zero Trust and micro-segmentation, CCNA Routing &amp; Switching and Security</div>
<div><b>AI:</b> AI security frameworks and data governance, sandboxed AI development environments, local LLMs (Ollama, LM Studio) on NVIDIA hardware, Claude Code, Azure OpenAI, AWS Bedrock, agent harnesses</div>
<div><b>Compliance:</b> SOC 2, ISO 27001, NIST CSF / 800-53, CIS Benchmarks and Controls, PCI DSS, HIPAA, Essential Eight</div>
<div><b>Languages &amp; Platforms:</b> Python, PowerShell, Bash, TypeScript, Node.js, React, Kotlin, C, Java, C#/ASP.NET, SQL (SQL Server, MySQL, PostgreSQL); Linux (Debian, RHEL), Windows Server, IIS, Microsoft 365, Google Workspace</div>
</div>
<h2>Professional Experience</h2>
<div class="job">
<div class="jobhead"><div><span class="role">Lead of Cyber Security, Technical Accounts &amp; DevOps</span> · <span class="org">Salvo Software</span></div><div class="dates">Apr 2026 – Present · Remote</div></div>
<div class="context">Salvo's teams in Mexico, the USA and India were building code locally, with security spread across Microsoft 365, Google Workspace, Azure, AWS and GCP. I joined to own DevOps and security and was promoted within months to lead Cyber Security, Technical Accounts and DevOps.</div>
<div class="lbl">AI program</div>
<ul>
<li>Lead the company AI program. Built a sandboxed development environment on VMware ESXi with a custom Debian build and per-developer sandbox folders isolated with bubblewrap, so AI tools cannot read sensitive repository files or change host permissions. <b>50 developers</b> use it daily.</li>
<li>Run local models on an NVIDIA Vera Rubin NVL72 and through Ollama and LM Studio, so sensitive code and data never leave company hardware.</li>
<li>Built the backend that brokers every request to AI providers, with full logging of who asked what and when.</li>
<li>Wrote the company AI security framework covering approved tools, data classes, logging and review, with a policy engine that blocks actions against policy and data governance that keeps sensitive data away from AI.</li>
<li>Started the agent harness work on DeepSeek and Claude Code; now building an in-house harness from the ground up with the team.</li>
</ul>
<div class="lbl">DevOps and delivery</div>
<ul>
<li>Built Azure Pipelines and Azure Repos CI/CD (plus GitHub Actions) and delivery dashboards for all three development teams, cutting the development time between versions <b>from 30 days to 10 (3× faster)</b> and ending local builds; developers now just push code.</li>
<li>Wrote the software deployment design, branching strategy and standard release workflow the teams follow.</li>
<li>Helped develop xmlpids, the vehicle parameter ID (PID) definitions the company's diagnostic hardware uses, alongside the Kotlin team; reviewed its code and built the pipeline that delivers it to the client.</li>
<li>Wrote a tool that scans every build for known CVEs and notifies the owning dev team automatically, so vulnerabilities are caught before release instead of during a manual review.</li>
<li>Built the EZ LYNK Dashboard, a web app restricted to approved Google Workspace users that tracks committed code per project, checks that PIDs in the new version are correct and match legacy, and shows user activity (who logs in, when and what they do).</li>
<li>Fixed Kotlin app bugs in my first week on the job.</li>
</ul>
<div class="lbl">Data engineering</div>
<ul>
<li>Built Python VIN data pipelines for US vehicle marketplaces (commercial truck, snowmobile and ATV trader sites, cars.com GM VINs 2021–2025, Polaris), including sites where standard scrapers are blocked by bot protection, using rotating proxies.</li>
<li>Run them on a custom Linux server where users choose year, make and model, then load results into a database or receive an emailed CSV. The pipelines collect <b>about 1,000 VINs an hour</b>, and <b>100,000+</b> have been collected so far; the team uses them to test the diagnostic hardware and confirm vehicle information is passed correctly.</li>
</ul>
<div class="lbl">Security</div>
<ul>
<li>Rolled out Intune (device naming, standard software list, website blocking, remote-access tool blocking, Windows 11 readiness), Defender for Endpoint and Defender for Office 365, Entra ID Conditional Access, Google Workspace SSO/SAML, FIDO2 MFA and 1Password, giving one security baseline across five platforms. This work led to my promotion.</li>
<li>Launched the phishing program: first simulation, user groups and automatic training enrollment for anyone who fails, using Microsoft Attack Simulation Training and Google Workspace protections.</li>
<li>Handle every security incident for the company; have stopped a handful of cyberattacks and many phishing attempts.</li>
<li>Administer Microsoft 365 and Google Workspace for the company.</li>
</ul>
<div class="lbl">Infrastructure and cost</div>
<ul>
<li>Consolidated AWS, Azure and GCP and codified VMs, storage and serverless resources with Terraform, Ansible and PowerShell DSC, giving reproducible environments.</li>
<li>Cut costs by cancelling paid SaaS and self-hosting replacements on Docker, Proxmox and Hyper-V, and wrote TypeScript/Node.js tools that replaced paid billing and time tracking, plus an Azure Boards to EveryHour sync for live project visibility.</li>
<li>Set up the office network infrastructure on Ubiquiti UniFi across Mexico, the USA and India, with VLANs, firewall rules, WireGuard and Tailscale; built the US office backup on a UniFi NAS with scheduled server sync jobs.</li>
<li>Monitor with Grafana, Prometheus, Azure Monitor and Log Analytics; automate with Python, PowerShell and Bash.</li>
</ul>
<div class="tech"><b>Technologies:</b> Azure, AWS, GCP, Azure DevOps, GitHub Actions, Terraform, Ansible, PowerShell DSC, Docker, Proxmox, Hyper-V, VMware ESXi, Debian, bubblewrap, NVIDIA Vera Rubin NVL72, Ollama, LM Studio, Claude Code, Intune, Defender, Entra ID, Google Workspace, 1Password, UniFi, WireGuard, Tailscale, Grafana, Prometheus, Python, TypeScript, Node.js, React, Kotlin, Postman, Slack</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">Cyber Security Specialist (Freelance)</span> · <span class="org">Affila Technology</span></div><div class="dates">Mar 2025 – Present · Remote</div></div>
<div class="context">Clients running hybrid Azure, AWS, GCP and on-prem environments need to find and fix weaknesses before attackers do. Across about five engagements I lead their assessments, remediation and security roadmaps.</div>
<ul>
<li>Supporting MSP client UIDN on an ongoing basis; personally fixed every misconfiguration in their Microsoft 365 environment, leaving a hardened tenant that meets their security baseline.</li>
<li>Tested a client AI chatbot built on Azure OpenAI and AWS Bedrock with PyRIT against the OWASP LLM Top 10, found data-leak issues and drove remediation before they could be exploited.</li>
<li>Run penetration tests with Burp Suite, OWASP ZAP, Nmap, Masscan and Metasploit from Kali Linux, validating exploitable weaknesses and delivering prioritized fixes.</li>
<li>Scan infrastructure with Nessus, Qualys and OpenVAS, and cloud posture with Microsoft Defender for Cloud, mapping findings to NIST CSF / 800-53, CIS Benchmarks and OWASP ASVS to produce clear remediation roadmaps.</li>
<li>Hunt threats and handle incidents in Microsoft Sentinel; automate engagements with Python, PowerShell and Bash for faster, repeatable assessments.</li>
</ul>
<div class="tech"><b>Technologies:</b> Burp Suite, OWASP ZAP, Nmap, Masscan, Metasploit, Kali Linux, Nessus, Qualys, OpenVAS, Defender for Cloud, Microsoft Sentinel, Microsoft 365, Azure OpenAI, AWS Bedrock, PyRIT, Python, PowerShell, Bash</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">UST</span> · <span class="org">Client: Wolters Kluwer SureTax</span></div><div class="dates">Apr 2025 – Apr 2026 · Remote</div></div>
<div class="context">SureTax, Wolters Kluwer's cloud tax engine, processes millions of calculations a day for enterprise clients and must stay available and SOC 2 / ISO 27001 compliant. I owned reliability and DevSecOps, working with and mentoring about 15 engineers.</div>
<div class="jobhead"><span class="subrole">Senior Site Reliability Engineer</span><span class="dates">Sep 2025 – Apr 2026</span></div>
<ul>
<li>Cut <b>mean time to recovery by 65%</b>, mainly by stabilizing the Azure network setup and adding redundancy, backed by SLOs, error budgets, Datadog and Application Insights alerting, Grafana dashboards and PagerDuty on-call.</li>
<li>Noticed East US users slowed down every Microsoft Patch Tuesday, traced it to Elasticsearch timeouts during Microsoft's regional maintenance, and built timeout compensation with the team so users stopped seeing errors while the region was patched.</li>
<li>Audited Azure spend, removed unused resources from subscriptions and moved environments to on-demand spin-up and teardown; right-sized AKS workloads with Helm. <b>Costs fell 30%, then a further 25%.</b></li>
<li>Built automated failover across Azure SQL and Cosmos DB behind Azure Front Door and proved it with Azure Chaos Studio experiments.</li>
<li>Delivered blue-green, zero-downtime releases on a two-week cycle in Azure DevOps Pipelines, with SonarQube and infrastructure-as-code validation gates.</li>
<li>Codified Azure in Terraform with Azure Policy, Key Vault secrets and Application Gateway, minimizing drift and enforcing SOC 2 / ISO 27001 controls.</li>
<li>Led threat modeling, penetration tests and training on secure coding and incident response; mentored about <b>15 engineers</b> in SRE practice.</li>
</ul>
<div class="jobhead"><span class="subrole">Senior DevOps Engineer</span><span class="dates">Apr 2025 – Sep 2025</span></div>
<ul>
<li>Cut <b>mean time to remediation by 70%</b> by introducing zero-downtime patching, runbooks and automated remediation.</li>
<li>Added SonarQube static analysis, dynamic testing, container and secret scanning and dependency checks as Azure DevOps Pipelines gates, blocking vulnerable code before production without slowing releases.</li>
<li>Enforced least privilege, segmentation and encryption with Terraform, Azure Policy and Key Vault, automating SOC 2 and ISO 27001 checks.</li>
<li>Set secure coding standards, ran OWASP Top 10 training and introduced blameless post-mortems, so developers fix issues before merge.</li>
</ul>
<div class="tech"><b>Technologies:</b> Azure (AKS, Azure SQL, Cosmos DB, Key Vault, Front Door, Application Gateway, Chaos Studio), Helm, Terraform, Azure Policy, Azure DevOps Pipelines, SonarQube, Datadog, Azure Monitor, Application Insights, Grafana, Prometheus, PagerDuty, Elasticsearch</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">Architecture and Optimization (Cloud Security)</span> · <span class="org">Avertium</span></div><div class="dates">Jul 2024 – Apr 2025 · Hybrid</div></div>
<div class="context">Avertium's 13 managed security clients needed to meet CIS, Essential Eight, NIST CSF, PCI DSS and HIPAA requirements and respond fast when attacked. I designed and deployed their controls and led investigations.</div>
<ul>
<li>Over the Christmas break, attackers were moving through a large confectionery manufacturer's back-end systems and no one could find the entry point. My full network scans traced it to third-party supplier machines running a vulnerable FTP server; we contacted every supplier and blocked external FTP access across <b>12 sites</b>, closing the entry point so the team could evict the attackers.</li>
<li>Wrote Python scripts that audit Azure, AWS and GCP against CIS Benchmarks and generate reports, so misconfigurations are found in minutes instead of days.</li>
<li>Deployed Entra ID MFA, Conditional Access, PIM and RBAC, integrated with Active Directory through Entra Connect, Okta and Duo, blocking identity attacks and enforcing least privilege.</li>
<li>Rolled out Defender XDR, Defender for Endpoint and Defender for Identity alongside CrowdStrike and SentinelOne, and built Microsoft Sentinel detections and investigations for faster SOC triage.</li>
<li>Implemented Microsoft Purview DLP, sensitivity labels and compliance policies; enrolled and hardened devices with Intune and Autopilot to CIS and Essential Eight baselines.</li>
<li>Designed Zero Trust network controls (NSGs, firewalls, VPN, micro-segmentation) to limit lateral movement.</li>
</ul>
<div class="tech"><b>Technologies:</b> Defender XDR / Endpoint / Identity, Microsoft Sentinel, Purview, Intune, Autopilot, Entra ID, PIM, Active Directory, Entra Connect, Okta, Duo, CrowdStrike, SentinelOne, NSGs, firewalls, VPN, Python, CIS Controls, Essential Eight, NIST CSF, PCI DSS, HIPAA</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">Senior Cloud &amp; DevOps Engineer</span> · <span class="org">UST · Client: AvidXchange</span></div><div class="dates">Apr 2021 – Jun 2024 · Remote</div></div>
<div class="context">AvidXchange's payments platform ran on legacy applications with limited visibility and strict SOC compliance. Over three years I worked across its Enterprise Monitoring, modernization and security teams.</div>
<ul>
<li>Led the Enterprise Monitoring rollout of Dynatrace and Azure Monitor with Logic Apps automation for alerting and response. Recurring service failures fell from about one every three days to a handful a year, <b>a ~95% reduction</b>.</li>
<li>When a critical production Logic App suddenly failed, traced the cause to an update Microsoft had pushed to the Logic Apps framework, adjusted the workflow and restored service quickly.</li>
<li>Moved <b>18 legacy applications</b> to Docker, Azure Container Registry and AKS with Helm, turning them into scalable microservices.</li>
<li>Integrated services through Azure API Management, Service Bus, App Service and Azure SQL for reliable, decoupled payment flows.</li>
<li>Built reusable Terraform modules and Azure DevOps Pipelines so teams could deploy their own infrastructure, with access control, encryption and auditing built in for consistent, SOC-compliant environments.</li>
<li>Automated operations with PowerShell and Bash and tracked work in Azure Boards.</li>
</ul>
<div class="tech"><b>Technologies:</b> Azure (AKS, Azure SQL, App Service, API Management, Service Bus, Logic Apps, Container Registry, Azure Monitor), Dynatrace, Docker, Helm, Terraform, Azure DevOps (Pipelines, Boards), PowerShell, Bash, Linux</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">DevOps Engineer</span> · <span class="org">WSAudiology</span></div><div class="dates">2021</div></div>
<p>A Red Hat Enterprise Linux Node.js application with MySQL and PostgreSQL needed reliable releases. I automated deployments with Jenkins and Ansible from Bitbucket and added Prometheus and Nagios monitoring, giving consistent, repeatable releases with less downtime.</p>
<div class="tech"><b>Technologies:</b> Jenkins, Ansible, RHEL, Node.js, MySQL, PostgreSQL, Bitbucket, Prometheus, Nagios, shell scripting</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">Software Specialist / DevOps Engineer</span> · <span class="org">iTexico</span></div><div class="dates">2020 – 2021</div></div>
<p>For clients BestPass and GetGiddy, I built TeamCity and Octopus Deploy CI/CD for an IIS and SQL Server web application, plus Azure Logic Apps automation, and analyzed Log Analytics data, delivering faster, reliable releases and insights that informed sales strategy.</p>
<div class="tech"><b>Technologies:</b> TeamCity, Octopus Deploy, IIS, SQL Server, Azure Logic Apps, Log Analytics, Bitbucket</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">DevOps Specialist</span> · <span class="org">Muttual</span></div><div class="dates">2019 – 2020</div></div>
<p>For clients Boxer Property and Stemmons Enterprise, I owned deployments, SQL Server troubleshooting and automation for an ASP.NET / C# business platform on Windows Server and IIS, keeping releases smooth with minimal downtime.</p>
<div class="tech"><b>Technologies:</b> ASP.NET, C#, SQL Server, Windows Server, IIS</div>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">G Suite &amp; GCP Support Specialist</span> · <span class="org">EPAM Systems (for Google)</span></div><div class="dates">2018 – 2019</div></div>
<p>Google's premier customers needed expert support, so on Google's behalf I troubleshot Google Workspace Admin Console, GCP Compute Engine and IAM issues and guided feature rollouts, giving smooth adoption with minimal disruption.</p>
<div class="tech"><b>Technologies:</b> Google Workspace Admin Console, Google Cloud Platform (Compute Engine, IAM)</div>
</div>
<h2>Selected Case Studies</h2>
<div class="case">
<div class="t">Releases every 10 days instead of every 30 <span class="w">· Salvo Software</span></div>
<p><b class="k">Situation:</b> Three development teams in Mexico, the USA and India built code on their own machines, and a new version took about 30 days of development time to reach release.</p>
<p><b class="k">Action:</b> Built Azure Pipelines CI/CD with a standard branching and release workflow, plus dashboards tracking committed code, PID accuracy against legacy and user activity, so problems surfaced early instead of at release.</p>
<p><b class="k">Result:</b> Time between versions fell from 30 days to 10, three times faster, and local builds ended.</p>
</div>
<div class="case">
<div class="t">Securing AI adoption for 50 developers <span class="w">· Salvo Software</span></div>
<p><b class="k">Situation:</b> Developers wanted AI coding tools, but the repositories hold sensitive client data and the company had no rules for AI use.</p>
<p><b class="k">Action:</b> Built an ESXi/Debian sandbox with per-developer folders isolated by bubblewrap so AI agents cannot read sensitive files or change permissions; ran local models on an NVIDIA Vera Rubin NVL72; put a logged backend in front of every AI provider; and wrote the AI security framework and policy engine.</p>
<p><b class="k">Result:</b> 50 developers use AI daily without exposing sensitive data or the host OS, and every AI interaction is auditable.</p>
</div>
<div class="case">
<div class="t">Patch Tuesday timeouts <span class="w">· Wolters Kluwer SureTax</span></div>
<p><b class="k">Situation:</b> East US users of a tax engine processing millions of calculations a day slowed down and saw errors on a recurring schedule.</p>
<p><b class="k">Action:</b> Correlated the slowdowns with Microsoft's Patch Tuesday maintenance in the region and traced them to Elasticsearch timeouts, then built timeout compensation with the team.</p>
<p><b class="k">Result:</b> Users stopped seeing errors while Microsoft patched the region.</p>
</div>
<div class="case">
<div class="t">Finding the entry point in a holiday intrusion <span class="w">· Avertium</span></div>
<p><b class="k">Situation:</b> Over Christmas, attackers were moving through a large manufacturer's back-end systems, and the team could not find how they got in.</p>
<p><b class="k">Action:</b> Ran full network scans and found third-party supplier machines running an FTP server version with a serious known exploit; contacted every supplier and blocked external FTP access across 12 sites.</p>
<p><b class="k">Result:</b> The entry point was closed and the team evicted the attackers.</p>
</div>
<div class="case">
<div class="t">From failures every three days to a handful a year <span class="w">· AvidXchange</span></div>
<p><b class="k">Situation:</b> A payments platform built on legacy applications had services failing roughly every three days with little visibility into why.</p>
<p><b class="k">Action:</b> Led the Enterprise Monitoring rollout of Dynatrace and Azure Monitor, with Logic Apps automation to alert and respond before users were affected.</p>
<p><b class="k">Result:</b> Recurring failures dropped to a handful a year, about a 95% reduction.</p>
</div>
<div class="case">
<div class="t">VIN collection at scale <span class="w">· Salvo Software</span></div>
<p><b class="k">Situation:</b> The hardware team needed large numbers of real vehicle VINs to test that diagnostic code reads vehicle information correctly, and standard scrapers were blocked by bot protection.</p>
<p><b class="k">Action:</b> Built Python pipelines with rotating proxies and a self-service Linux server where users pick year, make and model and get results in a database or an emailed CSV.</p>
<p><b class="k">Result:</b> About 1,000 VINs an hour and more than 100,000 collected for hardware testing.</p>
</div>
<div class="case">
<div class="t">Catching CVEs before release <span class="w">· Salvo Software</span></div>
<p><b class="k">Situation:</b> Checking each build for vulnerable dependencies was manual and repetitive.</p>
<p><b class="k">Action:</b> Wrote a tool that scans every build for known CVEs and notifies the owning dev team automatically.</p>
<p><b class="k">Result:</b> Vulnerabilities are flagged at build time instead of after release, with no manual effort.</p>
</div>
<h2>Open Source &amp; Personal Projects</h2>
<ul>
<li><b>Linux Sync</b> (open source, github.com/Benjamin-Saul-1989/Linux-Sync): peer-to-peer Linux system sync with a GTK GUI, mDNS discovery, QR-code pairing and SSH transport; built in under a day.</li>
<li><b>PortBuster</b> (open source): Python CLI that queries registered ports for TCP/UDP availability and service descriptions.</li>
<li><b>ADS-B Business Card</b> (in progress): a custom PCB business card that detects aircraft on 1090 MHz and blinks an LED.</li>
<li><b>Home lab</b>: Debian server self-hosting Immich (photos), Nextcloud and NocoDB, the same stack I teach in my self-hosting class.</li>
<li><b>Personal scripts</b>: automation tools on GitHub, including a SharePoint file checker.</li>
</ul>
<h2>Teaching &amp; Volunteering</h2>
<div class="job">
<div class="jobhead"><div><span class="role">Volunteer Instructor, Cybersecurity and Self-Hosting</span> · <span class="org">FAC (non-profit, Mexico City)</span></div><div class="dates">Jul 2025 – Present</div></div>
<ul>
<li>Teach an in-person cybersecurity class every second Saturday morning and a self-hosting class in the afternoon, in English and Spanish, to 10–30 students.</li>
<li>Mentor junior DevSecOps engineers in Mexico City.</li>
</ul>
</div>
<div class="job">
<div class="jobhead"><div><span class="role">Volunteer Maker, 3D-Printed Prosthetics</span> · <span class="org">Enable the Future</span></div></div>
<ul><li>3D-print prosthetic hands for children.</li></ul>
</div>
<div class="two">
<div>
<h2>Education</h2>
<p><b>Advanced Diploma, Security and Networking</b><br/>TAFE SA, Australia · 2013</p>
<p><b>Certificate IV, Electronics and Computer Systems</b><br/>TAFE SA, Australia · 2012</p>
<h2>Languages</h2>
<p>English (native) · Spanish (conversational) · Japanese (elementary)</p>
</div>
<div>
<h2>Certifications</h2>
<p>Microsoft Certified Solutions Expert (MCSE) · 2013<br/>
Cisco CCNA Security · 2013<br/>
Cisco CCNA Routing and Switching<br/>
Microsoft Certified Solutions Associate (MCSA) · 2012<br/>
Microsoft Technology Associate (MTA) · 2012</p>
<h2>Interests</h2>
<p>Amateur radio, PCB design, 3D printing, self-hosting and home-lab security.</p>
</div>
</div>
<h2>Recommendations</h2>
<p style="color:var(--muted)">Excerpts from 15 recommendations on LinkedIn, four of them from direct managers.</p>
<div class="quote"><q>He demonstrated a highly collaborative and solution oriented mindset. He was always proactive and involved when challenges arose, communicating clearly while keeping everyone aligned.</q><span class="who">Esteban Fernandez Cuevas, UST Delivery Manager · managed Benjamin directly (2026)</span></div>
<div class="quote"><q>Benjamin is a solid employee with a diverse background and many skillsets. He always completed his projects on time and excelled at meeting customers' needs. I would be happy to have him as an employee again.</q><span class="who">Brian Gladfelter, Cyber Security Consultant · managed Benjamin directly at Avertium (2025)</span></div>
<div class="quote"><q>He played a pivotal role in implementing Dynatrace. Ben's meticulous attention to detail, positive attitude, and straightforward communication style are invaluable assets… a significant asset to any team.</q><span class="who">Ashok Ganpathi, Engineering Leader, Reliability, Observability &amp; Cloud Operations · managed Benjamin directly at AvidXchange (2024)</span></div>
<div class="quote"><q>Ben has been instrumental in the success of the Enterprise Monitoring workstream… I highly recommend utilizing Ben in any area that his passion and swiss army knife of skillsets drive him towards.</q><span class="who">Nic Henderson · managed Benjamin directly at AvidXchange (2022)</span></div>
<div class="quote"><q>He works from a very positive perspective and never brings a problem to the table without also bringing a solution. I enjoyed working with him and often learned from him.</q><span class="who">Nathan French, CISSP, Cybersecurity Leader · same team at Avertium (2025)</span></div>
<div class="quote"><q>He consistently demonstrated a strong aptitude for identifying and mitigating security risks… Benjamin's attention to detail and ability to stay calm under pressure were invaluable in maintaining the integrity of our operations.</q><span class="who">Kevin Roe, Acceleration and Optimization Consultant II, Avertium · same team (2025)</span></div>
<div class="quote"><q>He consistently delivered high-quality results on complex projects, often going above and beyond to ensure that everything was done efficiently and correctly.</q><span class="who">Eldon Sheckles, CISM, CDPSE · senior colleague at Avertium (2025)</span></div>
<div class="quote"><q>Their ability to analyze complex security challenges and present clear, actionable solutions has been instrumental in ensuring the success of our projects… effectively translating technical findings into business-friendly language.</q><span class="who">Dominique Devereux, Project Manager, Cybersecurity · Avertium (2025)</span></div>
<div class="quote"><q>Beyond his technical skills, Benjamin is a team player, always willing to share his knowledge and mentor others.</q><span class="who">Carlos Cañedo, Mexico Operations Manager, Avertium (2025)</span></div>
<div class="quote"><q>His expertise in CI/CD, Linux administration, Dynatrace monitoring, and scripting is unparalleled… His contributions have had a lasting impact on our team's success.</q><span class="who">Prashant Dasamantarao, Dynatrace Certified Admin · same team at AvidXchange for 2 years (2024)</span></div>
<div class="quote"><q>Ben has demonstrated exceptional proficiency in designing and implementing cloud solutions, optimizing infrastructure, and maintaining rigorous security standards.</q><span class="who">Pritam Majumder, Azure Cloud Architect · same team at AvidXchange (2024)</span></div>
<div class="quote"><q>He was always very helpful and ready to lend his technical expertise where needed to solve problems and remove blockers.</q><span class="who">Sean Russell, Senior Site Reliability Engineer · AvidXchange (2024)</span></div>
<div class="quote"><q>Ben will make an effort to contribute to company culture and make a place a better place to work.</q><span class="who">Baylee Corder, Cyber Security Recruiter · Avertium (2025)</span></div>
<div class="quote"><q>If you're looking for someone that not only does the job but also provides support and shares knowledge, he is definitely the person you are looking for!</q><span class="who">Nadia López Contreras, Accounting Manager · Avertium (2025)</span></div>
<div class="quote"><q>Ben has a great technical skill-set and is a tenacious teammate.</q><span class="who">Michael Watson-Fore, Engineer · different company (2020)</span></div>
<p style="color:var(--muted);font-size:8.6pt">Full recommendations on LinkedIn. References and contact details available on request.</p>
</div>
