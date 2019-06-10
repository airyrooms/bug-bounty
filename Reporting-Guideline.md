
<img src="./airyrooms.png" width="250"><br />

# Airy Bug Bounty

## Reporting Procedure
Before you follow the steps in Reporting Procedure listed below, please make sure you have read all of the sections in [General Guideline](./General-Guideline.md) respectively.

**All email communication should use PGP. See the footer of the document.**

The reporting procedure will be as follow:
1. Submit bug report by sending an email with subject: **[AIRY-BUG-BOUNTY] Short description of the bug/vulnerability**. The content of the email should be as follow:
   * **CVSS v3 Score**. Please follow the guideline described at https://www.first.org/cvss/specification-document and provide a link using the CVSS Calculator (https://www.first.org/cvss/calculator/3.0#CVSS:3.0/) containing the scoring metrics. For example: https://www.first.org/cvss/calculator/3.0#CVSS:3.0/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N/E:H/RL:O/RC:C
   * **_[Attachment] Bug Reporting Document_**. You can download the provided bug reporting document template via this [(Bug Reporting Document)](./files/bug-reporting-template.docx). 
   * **_[Attachment] Vulnerability Demonstration Video_**. You can provide a private accessible or upload & attach the demonstration video in the email. **_You are not advised to put the video via YouTube, or any public video space. The video should have hosted in private and should have its access control list open for email bug@airyrooms.com_**. This video is intended to help and assist us in reproducing the issue when we are conducting the investigation

2. Once we have received the bug report, we'll conduct a proper investigation of the reported bug. We'll reply and notify you via email once we're starting our investigation process. The process itself may takes **1-2 weeks** depending on the complexity of the bug report.
3. Assuming the bug report is a valid bug / security hole / vulnerability, we'll acknowledge the bug and inform you also via correspondence email. We'll inform you the possible reward bounty associated with the bug. 
4. We'll need some time to resolve & fix the reported bug. This bug-resolving process may take up-to **4-8 weeks** depending on the complexity of the bug. After this, we'll expect you to provide us with details about your identity and account information that will be required for the payment of the bounty reward.
5. Download the [Identity Registration Form](./files/identity-registration-form.xlsx). You are expected to complete the form, sign it, provide us with proof-of-identity (KTP, NPWP). 
6. Once we have received your identity, we'll need you to send us an invoice for our finance process to transfer the bounty reward to your bank account. To do that, please download the [Invoice Template](./files/invoice-template.doc). Please complete the template with the necessary details that we'll help to provide you through the correspondence email. You'll be required to send us the invoice so that our finance team are able to process the payment. We'll provide you the data regarding the following, to help you to complete the form:
   * Invoice Number (InvoiceNumber)
   * Invoice Date (InvoiceDate)
   * Reward / Bounty Value (Reward)
   * Bug Bounty ID (BugId)
7. After you send the invoice, you may need to wait about **7-10 working days** before the bounty reward is transferred to your bank account.

**You are required to send physical document of invoice and identity registration form for accounting and audit purpose.**

## PGP Public Key

Please use PGP for transmitting your email to us (bug@airyrooms.com):

```
-----BEGIN PGP PUBLIC KEY BLOCK-----

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
=0OnT
-----END PGP PUBLIC KEY BLOCK-----
```
