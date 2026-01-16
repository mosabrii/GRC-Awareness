# Controls and Compliance

This section documents the security controls currently implemented by Botium Toys and identifies missing controls that expose the organization to security and compliance risks. The assessment is based on the internal audit scenario and aligned with common security best practices.

## Existing Security Controls

The organization has implemented the following controls:

### Technical Controls
- Network firewall configured to restrict unauthorized traffic (Preventive)
- Anti-malware software deployed on systems and monitored by the IT team (Detective)
- Basic data integrity mechanisms to protect system data

### Administrative Controls
- Documented security and privacy policies
- Defined procedures for handling customer and business data

### Physical / Operational Controls
- Physical locks securing offices, stores, and warehouses
- CCTV surveillance systems in physical store locations
- Fire detection and prevention systems protecting physical assets

## Missing or Weak Security Controls

The audit identified several critical control gaps, including:

- No implementation of least privilege access control
- Lack of data encryption for sensitive and regulated information
- Absence of intrusion detection or prevention systems (IDS/IPS)
- No centralized password management system
- No separation of duties for sensitive operations
- No regular backup strategy or disaster recovery plan
- Insufficient management of legacy systems nearing end-of-life

## Compliance Status

Based on the current control environment, the organization’s compliance posture is as follows:

- PCI DSS: Non-compliant due to unrestricted employee access to payment card data
- GDPR: Partially compliant, with notification procedures in place but weak data protection controls
- U.S. data protection regulations: High risk of non-compliance due to insufficient access control and encryption

This control and compliance assessment highlights significant gaps that increase the organization’s exposure to data breaches, regulatory penalties, and operational disruption.
