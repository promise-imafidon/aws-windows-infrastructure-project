# AWS Windows Server & Active Directory Infrastructure Lab

A multi-week cloud systems engineering portfolio built on **Amazon Web Services (AWS) EC2**, covering Windows Server provisioning, remote management orchestration, identity and access administration, security hardening, and domain networking.

---

## Weekly Lab Roadmap & Documentation

| Week | Module Title | Key Technologies | Documentation | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Week 01** | **Deploy Windows Server 2022 & Fleet Manager RDP** | AWS EC2, RDP (`TCP 3389`), Systems Manager Fleet Manager, ICMP | [Open Week 01 Docs](docs/01-windows-server-deployment.md) | Completed |
| **Week 02** | **Local Security Policy, User-Specific GPOs & P2P File Sharing** | Local Security Policy (`secpol.msc`), User GPOs (`mmc.exe`), Workgroup SMB (`TCP 445`), ACLs | [Open Week 02 Docs](docs/02-users-security-domain-join.md) | Completed |

---

## Environment Architecture
* **Cloud Provider:** Amazon Web Services (AWS EC2, VPC Security Groups, IAM, Systems Manager)
* **Server OS:** Microsoft Windows Server 2022 Base
* **Repository Convention:** All technical SOPs are stored in `docs/` with matching verification screenshot directories in `images/`.