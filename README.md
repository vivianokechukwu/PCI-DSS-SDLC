<h1>Integration of PCI-DSS Requirements into Software Development Lifecycle</h1>

<h2>Overview</h2>

I drove the integration of PCI DSS 4.0 secure coding practices into the software development lifecycle (SDLC), embedding security across design, build, test, and deploy to reduce compliance risks and strengthen cardholder data protection.

<h2>Key Contributions</h2>

### SDLC Assessment:

Partnered with DevOps and engineering to review Agile + CI/CD workflows. Exposed critical gaps including missing threat modeling, inconsistent secure design, and poor credential handling practices

### Secure Coding Enhancement:

Standardized input validation and output encoding (OWASP ESAPI), enforced bcrypt + MFA for authentication, eliminated hardcoded secrets with HashiCorp Vault, and mandated TLS 1.2+.

### Security Testing Integration:

Embedded SAST/DAST into CI/CD pipelines with Jenkins gates blocking high-severity vulnerabilities

### Code Review Improvements:

Mitigated SQL injection via parameterized queries, enforced card number masking in logs, and strengthened password resets with single-use JWTs.

### Developer Training: 

Delivered a PCI Secure Coding program through videos, labs, and GitHub examples.

### Results & Impact

- Reduced production vulnerabilities by 60% within months of rollout.<br>
- Established a culture shift, developers began raising security issues proactively in PRs.<br>
- Prepared the organization for a PCI DSS mock audit (Q3 2025), ensuring readiness for external review.








<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
