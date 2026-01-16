# Internal Security Audit – Botium Toys

This project simulates a real-world **internal security audit** conducted as part of **GRC (Governance, Risk, and Compliance)** activities.  
The audit is based on a fictional company scenario and aligned with common industry frameworks such as **NIST CSF**.

---

## Scope

The audit focuses on the overall information security program of Botium Toys, including:

- IT systems, applications, and databases  
- End-user devices (desktops, laptops, remote workstations)  
- Physical locations (retail store, warehouse, CCTV, fire systems)  
- Sensitive data (PII, SPII, payment card data)  
- Legacy systems nearing end-of-life  

Regulatory considerations include **PCI DSS**, **GDPR**, and U.S. data protection laws.

---

## Risk Assessment

Botium Toys operates in a **high-risk environment (8/10)** due to:

- Limited asset visibility and classification  
- Excessive user access to sensitive data  
- Lack of data encryption  
- Absence of IDS/IPS and centralized monitoring  
- No backup or disaster recovery planning  

These gaps increase the likelihood of data breaches, regulatory penalties, and business disruption.

---

## Security Controls

### Existing Controls
- Network firewall and anti-malware solutions  
- Basic data integrity mechanisms  
- Security and privacy policies  
- Physical security controls (locks, CCTV, fire detection)

### Missing or Weak Controls
- Least privilege access and separation of duties  
- Data encryption at rest and in transit  
- IDS/IPS and continuous monitoring  
- Centralized password management  
- Backup and disaster recovery plan  
- Proper legacy system risk management  

---

## Compliance Status

- **PCI DSS**: Non-compliant due to unrestricted access to payment data  
- **GDPR**: Partially compliant (notification procedures exist, controls are weak)  
- **U.S. regulations**: High risk of non-compliance  

---

## Findings & Recommendations

**Key Findings**
- Excessive access to sensitive data  
- Weak access control and password management  
- No encryption, IDS/IPS, or backups  
- Partial GDPR compliance and PCI DSS non-compliance  

**Recommendations**
- Enforce least privilege and separation of duties  
- Encrypt sensitive data  
- Implement IDS/IPS and monitoring  
- Establish backups and disaster recovery  
- Align controls with PCI DSS and GDPR  

---

## Disclaimer

This project is for **educational and portfolio purposes only**.  
All scenarios and organizations are fictional.
