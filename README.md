# Enterprise Azure Infrastructure Deployment for Cloud Consulting Client

## 📌 Business Scenario

A consulting client required deployment of a secure, publicly accessible web platform hosted in Microsoft Azure.

The solution needed to:

- Follow enterprise security principles
- Implement controlled remote administration
- Support HTTPS encryption
- Demonstrate cost governance
- Align with Agile delivery practices
- Include validation and testing documentation

This engagement was structured as a cloud consulting infrastructure deployment project.

---

## 🧠 Role & Responsibilities

**Role:** Cloud Infrastructure Consultant (Hybrid Technical + Delivery)

Responsibilities included:

- Azure IaaS architecture design
- Network segmentation planning
- Security boundary configuration
- VM deployment & configuration
- IIS web server setup
- SSL implementation
- Access control hardening
- Validation testing
- Cost governance implementation

---

## 🏗 Architecture Components

- Azure Resource Group
- Azure Virtual Network (VNet)
- Subnet segmentation
- Network Security Group (NSG) with layered inbound rules
- Windows Server 2025 (Gen2) Virtual Machine
- IIS Web Server
- Public IP with DNS label
- Self-signed SSL certificate
- Auto-shutdown configuration

---

## 🔐 Security Controls Implemented

- RDP restricted to a single public IP address
- NSG-based inbound traffic control
- Deny-all default inbound policy
- HTTPS binding with SSL certificate
- Controlled port exposure (80, 443, 3389)
- Public IP DNS configuration

---

## 🧪 Validation & Testing

Performed:

- Port connectivity testing using PowerShell (Test-NetConnection)
- VM agent validation
- NSG rule validation
- HTTPS binding verification
- DNS resolution testing
- External web accessibility validation
- Firewall profile verification

---

## 🔄 Agile Alignment

Project execution aligned with Agile principles:

**Sprint 1:** Network Foundation Deployment  
**Sprint 2:** Compute & OS Configuration  
**Sprint 3:** Web Server Installation & Validation  
**Sprint 4:** Security Hardening & SSL Implementation  
**Sprint 5:** Cost Governance & Final Testing  

User stories were structured around:

- Secure remote access
- Public web accessibility
- Controlled network exposure
- Encrypted communication

---

## 💰 Governance & Cost Management

- Implemented VM Auto-shutdown policy
- Controlled exposure of public endpoints
- Used appropriate VM sizing for workload
- Avoided unnecessary managed services

---

## 🌐 Live Deployment

https://leke-cloud-portfolio.centralus.cloudapp.azure.com

---

## 🎯 Skills Demonstrated

- Azure Infrastructure as a Service (IaaS)
- Cloud Networking & NSG Configuration
- Windows Server Administration
- IIS Web Server Deployment
- SSL & HTTPS Configuration
- Infrastructure Security Hardening
- Cloud Troubleshooting & Root Cause Analysis
- Hybrid Technical + Delivery Alignment
