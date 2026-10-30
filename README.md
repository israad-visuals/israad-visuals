<div align="center">
  <h1>Ismail Abdi</h1>
  <p><strong>Cloud Infrastructure &amp; Engineering</strong></p>
  <p>Terraform · Networking · Identity · Automation · Cloud Operations</p>
  <p>
    <a href="#about-me">About</a> •
    <a href="#certifications--training">Certifications</a> •
    <a href="#technologies">Technologies</a> •
    <a href="#selected-projects">Projects</a> •
    <a href="#professional-experience">Experience</a> •
    <a href="https://www.linkedin.com/in/ismail-abdi-8bbaa0176/">Connect</a>
  </p>
</div>

### About Me

I build cloud infrastructure and work on the applications it supports. My programming background helps me connect application requirements with networking, access control, automation and operations.

My recent infrastructure work started with a live eSIM and telecommunications provider running on a single VPS. I analyzed the business requirements, designed the architecture and developed separate production and development Terraform configurations, with private service access, monitoring and a resource-by-resource cost model.

**Open to cloud infrastructure, cloud engineering and administration co-op or internship opportunities in Toronto.**

### Certifications & Training

- **[Microsoft Certified: Azure Administrator Associate (AZ-104)](https://learn.microsoft.com/en-gb/users/ismailabdi-6877/credentials/8f847fd3319e3ed3)**
- **[Microsoft Certified: Azure Fundamentals (AZ-900)](https://learn.microsoft.com/en-gb/users/ismailabdi-6877/credentials/2deaf6eb430d6a65)**
- **AZ-305: Designing Microsoft Azure Infrastructure Solutions** — In progress

<a id="technologies"></a>

### 🛠️ Technologies

**Cloud infrastructure**
<p>
  <img alt="Microsoft Azure" src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img alt="AWS fundamentals" src="https://img.shields.io/badge/AWS_Fundamentals-232F3E?style=for-the-badge" />
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />
  <img alt="Networking" src="https://img.shields.io/badge/Networking-00599C?style=for-the-badge" />
  <img alt="Identity and access" src="https://img.shields.io/badge/Identity_%26_Access-243A5E?style=for-the-badge" />
</p>

Virtual Machines · Storage Accounts · Virtual Networks · NSGs · Microsoft Entra ID · RBAC · Key Vault · Azure Monitor · Azure Backup · Infrastructure as Code

**Linux, delivery & operations**
<p>
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**Software development foundation**
<p>
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
</p>

**Automation, testing & collaboration**

Azure CLI · PowerShell · Python · Shell scripting · CI/CD validation · Vitest · Playwright · JUnit · Gitleaks · Agile · SDLC · Jira · GitHub Projects · Issue and bug tracking

### Selected Projects

#### [Azure Cloud Migration Architecture — eSIM & Telecommunications Solutions Provider](https://github.com/israad-visuals/restsim-azure-infrastructure)

*Microsoft Azure, Terraform, Infrastructure as Code (IaC), Linux, Azure Networking, Azure Monitor*

- Deployed and tested Microsoft Azure infrastructure for a live eSIM and telecommunications provider; developed separate production and development Terraform configurations for business-critical web and mobile services.
- Defined production private networking across 3 subnets and 4 private endpoints using Virtual Networks, Private DNS and Network Security Groups (NSGs); scoped managed-identity access to individual Azure Key Vault secrets through RBAC.
- Configured a Virtual Machine Scale Set (VMSS) design across 2 availability zones with a 2–4-instance autoscaling range, Standard Load Balancer health probes, shared sessions and a separate background worker.
- Codified Azure Monitor, Log Analytics and Application Insights configurations with 7 metric alerts and Resource Health notifications, alongside backup policies and Azure Policy governance controls.
- Produced 7 architecture diagrams and a 52-line infrastructure cost model, documenting resource sizing, availability, security, CI/CD and GitHub OIDC release-design decisions.

[View the full project, architecture decisions and documentation](https://github.com/israad-visuals/restsim-azure-infrastructure) · [Architecture diagrams](https://github.com/israad-visuals/restsim-azure-infrastructure/tree/main/docs/architecture) · [Cost review](https://github.com/israad-visuals/restsim-azure-infrastructure/blob/main/docs/costs/README.md)

#### [Currency Exchange API](https://github.com/israad-visuals/somaliland-fx-api)

Integrated external exchange-rate data through a Java/Spring Boot REST API, using USD as an intermediate currency and storing local exchange-rate history in PostgreSQL via Spring Data JPA.

### Professional Experience

#### Software Engineer (Part-time) | RestSim
**February 2024–September 2026**

Travel eSIM platform · [Website](https://restsim.com/) · [Google Play](https://play.google.com/store/apps/details?id=com.restsim.app&hl=en_CA) · [App Store](https://apps.apple.com/us/app/restsim-esim-data-call-sms/id6786134566)

- Administered production Ubuntu/Linux VPS environments through the CLI, configured servers and deployed validated updates.
- Investigated application and backend logs to resolve customer-reported issues affecting live web and mobile services.
- Implemented GitHub Actions CI checks for unit/API tests, PostgreSQL migrations, Playwright end-to-end tests and Gitleaks secret scanning.
- Maintained production PostgreSQL databases and backups.
- Developed React/TypeScript and Flutter features; collaborated on defect fixes, release planning and Android/iOS releases.

#### Creative Director | Astaan TV
**August 2022–June 2026**

- Translated user research into streaming-app requirements and coordinated implementation with developers and stakeholders.

#### Security Engineer | Sifalo Pay
**October 2024–January 2026**

- Supported payment-gateway development, security and operations, working on transaction-processing reliability.

#### Junior Software Engineer Intern | Safaricom
**February 2022–August 2022**

- Developed Java/Spring Boot backend features and resolved defects as part of a junior engineering team.
- Implemented automated tests and assisted with deployment testing across releases.

---

<div align="center">
  <p><strong>Toronto, Ontario · Cloud Infrastructure &amp; Engineering</strong></p>
  <p><a href="https://www.linkedin.com/in/ismail-abdi-8bbaa0176/">Let’s connect on LinkedIn</a></p>
</div>
