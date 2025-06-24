# 📧 Task 2: Phishing Email Analysis

## 🎯 Objective
To analyze a suspicious email sample and identify phishing characteristics such as spoofed sender addresses, header anomalies, malicious links, dangerous attachments, and social engineering tactics.
This task helps build awareness of phishing strategies and improve email threat analysis skills.

---

## 📝 Steps Followed

### 1. Obtained a Phishing Email Sample
- Used sample phishing mails->  https://caniphish.com/phishing-email-examples
- Analyzed the email content and structure based on the provided screenshot and actual message.

### 2. Verified Sender Information
- **Displayed Sender Name**: `Seb from CanIPhish`
- **Actual Email Address**: Not visible, but likely spoofed or misleading.
- **Technique Used**:
  - Spoofing GitHub notifications to exploit trust.
  - Possible use of impersonated or lookalike domains.

### 3. Analyzed Email Headers
- Header analysis not possible in this case (headers not provided).
- Typically, tools like [MXToolbox Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)  used to inspect:
  - Sender IP address
  - Return-path
  - SPF/DKIM/DMARC validation results

### 4. Inspected Links and Attachments
- **Visible Links in the Email**:
  - `https://github.com/settings/connections/applications/41387c6857fcb0509a45`
  - `https://github.com/settings/security-log`
  - `https://github.com/contact`
  - In legitimate emails, these URLs are safe — however, attackers often:
    - Use link spoofing or redirection
    - Mask malicious URLs with trusted anchors
    - Register similar-looking domains (e.g., `gìthub.com`, `github-secure.com`)

### 5. Identified Phishing Triggers in Email Body
- **Subject Line**: *"[GitHub] A third-party OAuth application has been added to your account"*
- **Psychological Triggers**:
  - Urgency: Implying unauthorized access
  - Action pressure: Prompting user to check security logs
