<img src="./airyrooms.png" width="250"><br />

# Airy Bug Bounty
- [Airy Bug Bounty](#airy-bug-bounty)
    - [Policy](#policy)
    - [Rules & Eligibility](#rules--eligibility)
    - [Reward & Disclosure Rules](#reward--disclosure-rules)
    - [In Scope Vulnerability](#in-scope-vulnerability)
    - [Out of Scope Vulnerability](#out-of-scope-vulnerability)

## Policy
Airy is committed to keep its services safe for everyone, which is why data security is our utmost priority. Airy welcomes any contributions and information by security researchers who find various types of security vulnerabilities seen in our services, in which case we would be appreciative if you would privately disclose your findings to us, giving us time to fix it before making a public disclosure. Airy offers a bounty or reward to these external security researchers for their invaluable contribution in improving security at Airy. 

Airy will not take any legal action against security researchers who report a vulnerability as long as they comply to the Airy bug bounty rules. However, Airy will take legal action against those who do not follow the rules based on applicable laws, including but not limited to, Undang-Undang Republik Indonesia No. 11 Tahun 2008 tentang Informasi dan Transaksi Elektronik, Electronic Transactions Act of Singapore, or any local law of Electronic Information and Transactions. Please read the following rules before reporting a vulnerability. By participating in this program, you agree to be bound by these rules. 

## Rules & Eligibility

- Reporter of vulnerability is not an employee, family, or contractor of Airy.

- Reporter of vulnerability are advised to send the bug reports via an approved channel (email: bug@airyrooms.com). We will not respond to any reports outside the approved channel.

- Reporter of vulnerability should only use their own accounts when performing testing or producing vulnerability, DO NOT attempt to view or tamper with data belonging to others.

- Reporter of vulnerability is prohibited to disturb, change, add, or delete any data or configuration inside Airy systems.

- Reporter of vulnerability is prohibited to take advantage of found vulnerability as a pivot or chaining to find another vulnerability inside Airy systems.

- DO NOT perform DDoS or DoS attack to Airy systems.

- Airy will only process bug reports within the in-scope vulnerability as stated in the “In Scope Vulnerability” section below. 

- Airy will review and verify incoming bug reports within 3 days after submission.

- Airy development teams have up to 90 days to implement a fix based on the severity of the report.

- By participating in this program, you have agreed to comply with all applicable local and international laws.

- By sending a bug report to Airy, reporter of vulnerability agrees to give Airy the full rights to keep using it for internal purposes without paying any royalty, license, or intellectual property rights.

- Airy reserves the right to cancel or modify this program at any time without prior announcement.

## Reward & Disclosure Rules
Airy, at its discretion, may provide monetary rewards to vulnerability reporters. The amount and payment method for reward is decided by Airy only. Reward amounts may vary depending upon the severity of the vulnerability and its impact on Airy, the quality of the report, and the type of affected system. Airy uses the international standard for risk calculations, such as OWASP Risk Rating Methodology and Common Vulnerability Scoring System (CVSS).
 

To qualify for a monetary reward under this program, you should:

- Be the first to report a specific vulnerability. Duplicate report is not eligible for bounty reward.

- Include a detailed and verifiable proof of concept of the vulnerability (screenshot/video/script) in the report. If our security team cannot reproduce or verify an issue, a bounty cannot be awarded. 

- Disclose the vulnerability report directly and exclusively to us. Public disclosure in any form before the issue has been resolved will result in disqualification for the bounty, and Airy may take legal procedures for such action.

- Provide your identity. Airy staff will need to know your identity to process the reward procedures.

- It can take up to 90 days for security researchers to receive the reward. 

## In Scope Vulnerability
This includes, but is not limited to:

- Cross-site scripting (XSS)

- Cross-site request forgery on critical activity

- Server-Side request forgery (SSRF)

- SQL injection

- Server-side remote code execution (RCE)

- XML external entity attacks (XXE)

- Unvalidated open redirect 

- Access control issues on sensitive data (Insecure Direct Object Reference issues, etc)

- Administrative Login Panel without password or weak password

- Directory traversal

- Local file disclosure (LFD)

- Information disclosure of Sensitive Information (system configurations, user data, etc)

- Publicly accessible login or admin panels

- Local exploit for Airy mobile application


## Out of Scope Vulnerability
The following issues won't be considered for a bounty:

- DDOS & Dos attack (but in rare case will be considered depends on the case)

- Social engineering (Fraud, Phishing, etc.)

- Vulnerability on second-party and third-party systems that are integrated with, or outside of, Airy core system.

- Self XSS  (e.g. input payloads by intercepting the request or tricking other users to input the payloads in their browser/console)

- Bugs that do not affect the latest version of common browsers (Chrome, Edge, Firefox, Safari)

- Reports that state that software is out of date/vulnerable without proof of concept

- Password, account and email policies, such as reset link expiration or password complexity.

- Cross-site Request Forgery (CSRF) with minimal security impact (Logout CSRF, etc.)

- Clickjacking

- Missing best practices or Security enhancements (HSTS, X-frame options, etc.)

- Missing cookie flags

- Recently disclosed 0-day vulnerabilities. Please allow us 30 days before reporting these types of issues, since we need time to patch our systems just like everyone else.

- Attacks requiring physical access to a user's device, Airy property, or data center.

- Attacks requiring physical access to device or MiTM

- Compromise of a Airy user or Airy employee's account.