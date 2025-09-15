<h1>Secure SDLC Integration - PCI DSS 4.0 Alignment</h1>

<h2>Overview</h2>

I drove the integration of PCI DSS 4.0 secure coding practices directly into our software development lifecycle (SDLC). My goal was to embed security into every stage of delivery: design, build, test, and deploy to reduce compliance risks and strengthen the protection of cardholder data.

<h2>Key Contributions</h2>

### SDLC Assessment:

Partnered with DevOps and engineering to review our Agile + CI/CD workflows. Exposed critical gaps including missing threat modeling, inconsistent secure design, and poor credential handling practices

### Secure Coding Enhancement:

- Standardized input validation and output encoding using OWASP ESAPI.<br>
- Strengthened authentication and session management with bcrypt, MFA enforcement, and strict token expiry.<br>
- Eliminated hardcoded secrets via HashiCorp Vault for secure storage.<br>
- Mandated TLS 1.2+ for all environments.

### Security Testing Integration:

- Embedded SAST (GitHub Advanced Security) and DAST scans into CI/CD.<br>
- Implemented Jenkins “security gates” to block builds with high-severity vulnerabilities.

### Code Review Improvements:

- Eliminated SQL injection risks with parameterized queries.<br>
- Introduced card number masking for all logs to meet PCI DSS logging controls.<br>
- Strengthened password reset flow using single-use JWTs.

### Developer Training: 

 Designed and delivered a tailored PCI Secure Coding program — including on-demand video modules, live hands-on labs, and GitHub examples.

### Results & Impact

Reduced production vulnerabilities by 60% within months of rollout.<br>
Established a culture shift, developers began raising security issues proactively in PRs.<br>
Prepared the organization for a PCI DSS mock audit (Q3 2025), ensuring readiness for external review.








<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
