# 🛡️ PKI Implementatio with Dogtag

## 📋 Project Description
This project involves the complete implementation of a **Public Key Infrastructure (PKI)** using **Dogtag Certificate System** in a virtualized environment on **Google Cloud Platform (GCP)** via **EVE-NG**.

The deployed infrastructure includes a comprehensive **Certificate Authority (CA)** with certificate management, CRL/OCSP revocation, and integration with 389 Directory Server.

## 🎯 Objectives
- ✅ Master enterprise PKI deployment with Dogtag
- ✅ Understand certificate lifecycle management mechanisms
- ✅ Implement scalable security infrastructure in the cloud
- ✅ Automate certificate issuance and revocation processes

## 🏗️ Project Architecture
```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Kali Linux    │ ── │  Fedora Server   │ ── │  GCP Cloud      │
│     Client      │    │   Dogtag PKI     │    │  Environment    │
└─────────────────┘    └──────────────────┘    └─────────────────┘
         │                       │                       │
         └─── Certificates ──────┘                       │
                         │                               │
                 ┌───────────────┐                       │
                 │  EVE-NG Lab   │ ──────────────────────┘
                 └───────────────┘
```

## 🛠️ Technologies Used

### 🔐 Cybersecurity & PKI
- **Dogtag PKI** - Public Key Infrastructure
- **389 Directory Server** - LDAP Directory
- **OpenSSL** - Key and CSR generation
- **X.509 Certificates** - RFC 5280 Standard

### ☁️ Infrastructure & Cloud
- **Google Cloud Platform (GCP)** - Hosting environment
- **EVE-NG** - Network virtualization platform
- **Fedora Server 42** - Server operating system

### 🌐 Network & Protocols
- **TLS/SSL** - Communication encryption
- **HTTP/HTTPS** - Administration interfaces
- **LDAP** - Directory service
- **SCEP** - Simple Certificate Enrollment Protocol

## 🚀 Installation and Deployment

### Prerequisites
- GCP account with EVE-NG access
- Fedora Server machine (≥ 4GB RAM, 8GB disk)
- Linux administration knowledge

### Installation Steps
1. **Deploy Fedora VM on GCP**
2. **Configure network and FQDN**
3. **Install Dogtag PKI and 389 Directory Server**
4. **Configure Certificate Authority**
5. **Deploy PKI components**

## 💻 Implemented Features

### ✅ Certificate Management
- Manual and automatic certificate issuance
- Revocation with CRL management
- Renewal and key archiving

### ✅ Security and Compliance
- Certificate-based authentication
- X.509 and RFC 5280 compliance
- AES-256 encryption and SHA-256 signatures

### ✅ Administration Interfaces
- Web interface HTTPS (port 8443)
- Command-line tools (CLI)
- REST API for automation

## 📊 Results and Validation

### Tests Performed
- ✅ Successful server certificate issuance
- ✅ Revocation and CRL updates
- ✅ LDAP directory integration
- ✅ Secure admin interface access

### Performance Metrics
- Deployment time: < 1 hour
- Open ports: 389 (LDAP), 8080 (HTTP), 8443 (HTTPS)
- Certificates issued: Multiple with full validation

## 🎓 Skills Developed

### 🔧 Technical
- Advanced Linux system administration
- Enterprise PKI infrastructure management
- Network communication security
- Cloud virtualization with GCP and EVE-NG

### 🏆 Professional
- IT project management
- Technical documentation
- Complex problem solving
- Collaborative teamwork

## 📈 Improvement Perspectives
- HSM (Hardware Security Module) integration
- High availability setup
- Automation with Ansible/Terraform
- Extension with other protocols (ACME, EST)

---

**⭐ Want to recreate this project? The detailed implementation report is available in the repo!**
