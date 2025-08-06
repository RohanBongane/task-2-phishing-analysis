# Phishing Email Analysis Report

## 📨 Email Summary
- **From**: Amazon Security <secure@amazon-verification.com>
- **To**: rohan.bongane@protonmail.com
- **Subject**: [Action Required] Unusual Login Attempt Detected
- **Date**: August 6, 2025

Identified Phishing Traits

Suspicious URL
- The link says: `https://amaz0n-secure-helpdesk.com/verify`
- But the domain is fake (`amaz0n` instead of `amazon`)
- Real Amazon would use something like `amazon.in` or `amazon.com`

Spoofed Sender Address
- Email is sent from `secure@amazon-verification.com`, which is not an official Amazon domain
- Return-Path shows `noreply@amaz0n-secure-helpdesk.com` — clearly fake

Urgency & Fear
- Uses phrases like "Failure to act within 24 hours will result in a temporary hold" to create panic

Generic Greeting
- Starts with just "Hello Rohan" — phishing emails often scrape names, but still feel impersonal
- Real Amazon support emails usually address with full name and partial account info

Header Analysis
- No SPF, DKIM, or DMARC verification present
- Sending server uses a private IP address (`172.16.x.x`) — unusual for real service providers
- `Message-ID` is not from Amazon's domain


Conclusion
This email is a phishing attempt trying to steal login credentials. It cleverly uses:
- Fake domains
- Urgent language
- Masked links

Recommendations
- Never click suspicious links in emails
- Always verify sender domains
- Use 2FA (Two-Factor Authentication)
- Report such emails using Gmail/Outlook's **“Report Phishing”** option
