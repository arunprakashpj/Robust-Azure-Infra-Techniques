# Robust-Azure-Infra-Techniques

## Project-Overview  
This project focuses on securing the Juice Store's infrastructure in Azure by implementing robust identity and access management, network security, data encryption, malware protection, and monitoring. The goal is to ensure a secure, compliant, and resilient environment.

---

## Objectives  

### Identity-and-Access-Management  
- Design authentication and authorization controls to manage access, role assignments, and identity.  

### Network-Security  
- Reduce the attack surface by removing public IP addresses from the Ops VM.  
- Configure **Azure Bastion** for secure connectivity to Azure Virtual Machines from the Azure Portal.  

### Data-and-Encryption  
- Secure SQL server and database traffic by:  
  - Limiting public network access.  
  - Enforcing TLS minimum requirements.  
  - Defining allowed IPs or network requirements.  
- Protect data at rest by encrypting data disks with a **customer-managed key**.  
- Secure Azure SQL by enforcing **Azure AD authentication** instead of weaker SQL authentication methods.  

### Protection  
- Protect virtual machines from malware by using built-in Azure extensions.  

### Monitoring  
- Enable and analyze **audit logs**.  
- Configure auditing to monitor and protect SQL databases.  

---

## Key-Features  

- **Identity and Role Management**  
  Centralized and secure identity management with tailored role assignments and strict access controls.  

- **Advanced Network Security**  
  Removal of public IPs and integration of Azure Bastion for secure remote connectivity, reducing attack exposure.  

- **Comprehensive Data Protection**  
  - Encryption of data at rest using customer-managed keys for enhanced security.  
  - Secure data in transit with TLS and strict IP/network policies.  

- **Threat Protection**  
  Proactive virtual machine protection against malware with Azure extensions.  

- **Enhanced Monitoring and Auditing**  
  Real-time audit logs and SQL database monitoring for compliance and threat detection.  

---

## Technologies-Used  

- **Azure Services**  
  - Azure Bastion  
  - Azure Virtual Machines  
  - Azure SQL  
  - Azure Monitor  
  - Azure Security Center  
  - Azure Audit Logs  
  - Disk Encryption with Customer-Managed Keys  

---

## Deliverables  

- Secure authentication and authorization controls for role and identity management.  
- Hardened Ops VM without public IPs, secured via Azure Bastion.  
- Encrypted SQL databases and data disks with customer-managed keys.  
- Configured malware protection for virtual machines.  
- SQL database monitoring and auditing configurations for security compliance.  
