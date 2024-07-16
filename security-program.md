# Security and Privacy at Hiring Branch

Security is at the core of our operations. Helping our customers improve their security and compliance posture starts with our own.

## Governance

Our Security and Privacy teams establish policies and controls, monitor compliance, and demonstrate our security to third-party auditors.

### Foundational Principles

1. Access is limited to those with a legitimate business need, based on the principle of least privilege.
2. Security controls are layered according to the principle of defense-in-depth.
3. Controls are applied consistently across all areas.
4. Controls are continuously improved for effectiveness, auditability, and reduced friction.

## Data Protection

### Data at Rest

All data stores with customer data are encrypted at rest. Sensitive data is encrypted at row-level for additional security.

### Data in Transit

We use TLS 1.2+ for data transmission, with HSTS to enhance security. Server TLS keys and certificates are managed by AWS.

### Secret Management

Encryption keys are managed via AWS KMS, stored in Hardware Security Modules (HSMs). Application secrets are securely managed via AWS Secrets Manager.

## Product Security

### Penetration Testing

We conduct annual penetration testing with top industry firms. All product and cloud infrastructure areas are assessed, with source code for thorough testing.

### Vulnerability Scanning

We require vulnerability scanning at key stages of our Secure Development Lifecycle (SDLC):
- Static analysis (SAST)
- Software composition analysis (SCA)
- Malicious dependency and subdependency scanning
- Dynamic analysis (DAST)
- Cloud security posture management (CSPM)
- Docker container & image scanning
- Network vulnerability scanning
- External attack surface management (EASM)

## Enterprise Security

### Endpoint Protection

Corporate devices are managed with mobile device management software and anti-malware protection. Security alerts are monitored 24/7/365.

### Vendor Security

We use a risk-based approach to evaluate vendors, assessing factors such as data access, production environment integration, and brand impact.

### Secure Remote Access

We use <REDACTED> for secure remote access.

### Security Education

Employees receive comprehensive security training upon onboarding and annually. Regular threat briefings keep employees informed of important updates.

### Identity and Access Management

We use <REDACTED> for identity management, enforcing phishing-resistant authentication. Access is role-based and deprovisioned upon termination.

## Data Privacy

Data privacy is a top priority, and we aim to be trustworthy stewards of all sensitive data and follow both PIPA/PIPEDA and GDPR requirements.

### Regulatory Compliance

We continuously evaluate regulatory updates to evolve our privacy program.

### Privacy Policy

- [Privacy Policy](https://www.hiringbranch.com/privacy-policy)
- [Terms of Service](https://www.hiringbranch.com/legal-terms-conditions-of-service)
- [Master Services Agreement](https://www.hiringbranch.com/saas-subscription-agreement)

## Responsible Disclosure

To report a security concern, please visit our [Responsible Disclosure page](./responsible-disclosure.md)

Get compliant and build trust with Hiring Branch.