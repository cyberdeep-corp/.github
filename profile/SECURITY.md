# Security Policy

<p align="center">
  <strong>CYBERDEEP CORPORATE</strong>
  <br/>
  Security • Responsibility • Trust
</p>

CyberDeep Corporate takes the security of its software, infrastructure, repositories, and users seriously.

We appreciate the work of security researchers and members of the community who help identify, responsibly report, and resolve security vulnerabilities.

This document outlines our security practices, supported versions, vulnerability reporting process, and responsible disclosure expectations.

---

## 1. Scope

This policy applies to software and projects that are:

- Developed and maintained by CyberDeep Corporate.
- Published under the official CyberDeep Corporate GitHub organisation.
- Explicitly identified as being covered by this security policy.

Individual repositories may contain additional security instructions or project-specific policies. Where applicable, those instructions should also be followed.

Third-party services, external infrastructure, and software that CyberDeep Corporate does not own or administer are outside our testing authorisation.

## 2. Reporting a Vulnerability

If you discover a potential security vulnerability in one of our projects, we encourage you to report it responsibly.

**Please do not disclose security vulnerabilities through public GitHub Issues, Discussions, pull requests, or social media before allowing us an opportunity to investigate.**

### Preferred reporting channel

Use GitHub Private Vulnerability Reporting where it is enabled:

[Report a vulnerability through GitHub](https://github.com/cyberdeep-corp)

Navigate to the affected repository:

1. Open the repository's **Security** tab.
2. Select **Report a vulnerability**.
3. Submit a private vulnerability report.

If private vulnerability reporting is unavailable, contact the organisation through its officially published security contact channel.

Do not send confidential vulnerability details to unverified accounts or unofficial representatives.

### Include in your report

Please provide as much of the following information as possible:

- **Project:** Name of the affected repository.
- **Affected version:** Release, commit, or branch.
- **Vulnerability type:** A brief description of the suspected issue.
- **Impact:** Potential security consequences.
- **Reproduction:** A minimal, safe proof of concept.
- **Environment:** Relevant operating system, browser, or configuration.
- **Evidence:** Relevant logs, screenshots, or non-sensitive supporting material.
- **Suggested remediation:** If you have a proposed fix.

Please avoid including real user credentials, personal information, private keys, production secrets, or other sensitive data.

## 3. Responsible Disclosure

We request that security researchers:

- Report vulnerabilities privately and in good faith.
- Avoid accessing, modifying, or disclosing other people's data.
- Avoid disrupting services or degrading system availability.
- Avoid destructive testing or actions that could affect real users.
- Avoid social engineering, phishing, or unauthorised physical access.
- Do not install persistent access mechanisms or introduce malicious code.
- Stop testing when a vulnerability has been sufficiently demonstrated.
- Allow reasonable time for investigation and remediation before public disclosure.

Security testing must only be conducted against systems for which you have explicit authorisation.

**This policy does not grant permission to test third-party infrastructure, production services, or systems outside the applicable scope.**

## 4. Our Response Process

After receiving a vulnerability report, CyberDeep Corporate aims to follow this process:

| Stage | Action |
|---|---|
| 1. Receipt | Acknowledge the report when reasonably possible. |
| 2. Assessment | Evaluate validity, severity, and potential impact. |
| 3. Investigation | Reproduce and investigate the reported issue safely. |
| 4. Remediation | Develop and test an appropriate security fix. |
| 5. Resolution | Release a patch or communicate an appropriate mitigation. |
| 6. Disclosure | Coordinate responsible public disclosure where appropriate. |

Response and remediation timelines depend on vulnerability severity, complexity, available resources, and project maintenance status.

We aim to communicate material updates to the reporter throughout the process.

## 5. Vulnerability Severity

We may use the Common Vulnerability Scoring System (CVSS) as a reference when assessing reported vulnerabilities.

| Severity | CVSS Score |
|---|---|
| Critical | 9.0 – 10.0 |
| High | 7.0 – 8.9 |
| Medium | 4.0 – 6.9 |
| Low | 0.1 – 3.9 |
| Informational | 0.0 |

Severity is determined by the actual impact, exploitability, affected components, and context of the vulnerability.

CVSS scores are indicative and do not automatically determine remediation priority.

## 6. Supported Versions

Security maintenance depends on the individual project's development and release lifecycle.

Unless a repository specifies otherwise:

- The latest stable release is the primary security maintenance target.
- Previously released versions may not receive security updates.
- Development branches may contain incomplete or experimental security changes.
- Users are encouraged to upgrade to supported releases.

Refer to the affected repository's documentation and release history for project-specific information.

## 7. Security Updates

When security vulnerabilities are confirmed, we may:

- Release security patches.
- Publish updated versions.
- Provide mitigation instructions.
- Update relevant documentation.
- Publish security advisories where appropriate.

Security fixes may be released independently of regular feature updates.

Users are encouraged to monitor repository releases and GitHub Security Advisories.

## 8. Researcher Recognition

We appreciate responsible security research and meaningful contributions to improving our projects.

With the researcher's permission, we may acknowledge valid vulnerability reports through:

- Security acknowledgements.
- GitHub Security Advisories.
- Project release notes.
- Public contributor recognition.

Recognition is not guaranteed and does not constitute a monetary reward, employment offer, or bug bounty unless separately agreed in writing.

Researchers should not assume that a financial reward is available.

## 9. Safe Harbour

CyberDeep Corporate supports good-faith security research conducted within the authorised scope of this policy.

To the extent permitted by applicable law, we will:

- Treat good-faith research as authorised when it complies with this policy and applies to systems we control.
- Not pursue legal action against researchers solely for qualifying activities conducted in accordance with this policy.
- Work with researchers to understand and resolve reported vulnerabilities.
- Consider the researcher's intent and adherence to responsible disclosure practices.

This statement does not override applicable laws, third-party rights, contractual obligations, or the need for explicit authorisation where required.

## 10. Exclusions

The following activities are not covered by this policy:

- Testing systems or services without appropriate authorisation.
- Accessing or extracting private user information.
- Denial-of-service or resource-exhaustion attacks.
- Spam, phishing, or social-engineering campaigns.
- Physical attacks or attempts to gain unauthorised access.
- Destructive exploitation or deliberate data modification.
- Testing third-party services using CyberDeep Corporate's name as implied authorisation.
- Public disclosure of unpatched vulnerabilities without appropriate coordination.

## 11. Third-Party Dependencies

Our projects may depend on external libraries, frameworks, APIs, hosting providers, and other third-party components.

Vulnerabilities originating in third-party dependencies may need to be reported to their respective maintainers.

We encourage contributors to use maintained dependencies, review security advisories, and follow appropriate dependency update practices.

## 12. Policy Maintenance

This security policy may be updated as our projects, infrastructure, and security practices evolve.

Repository-specific policies may supplement this document.

The latest published version of this document takes precedence over older copies, subject to applicable project-specific policies.

---

<p align="center">
  <strong>CYBERDEEP CORPORATE</strong>
  <br/>
  Engineering the Future. Securing the Digital World.
  <br/><br/>
  <sub>Responsible Research • Secure Engineering • Continuous Improvement</sub>
</p>
