# Privacy Policy for Monday

**Last Updated:** April 22, 2026  
**Effective Date:** April 22, 2026

---

## 1. Introduction

Monday ("we," "us," "our," or "Company") operates the Monday mobile application ("App"). This page informs you of our policies regarding the collection, use, and disclosure of personal data when you use our App and the choices you have associated with that data.

We use your data to provide and improve the App. By using the App, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information Collection and Use

### 2.1 Information You Provide Directly

**Email Address:**
- Collected during onboarding for account registration
- Used for OTP (One-Time Password) verification
- Used for account recovery if you reinstall the app
- NOT shared with third parties except Resend (email service)

**Voice Recordings:**
- Recorded when you tap the Monday orb to speak
- Automatically transcribed using Groq's speech-to-text service
- Transcriptions stored securely in our database
- Used to generate insights, patterns, and behavioral analysis
- Retained indefinitely until you delete your account

**Chat Messages:**
- Messages you send through the Chat interface
- Stored in our database for conversation history
- Used to maintain context for Monday's responses
- Retained indefinitely until you delete your account

**Name:**
- Collected during onboarding
- Used to personalize the app experience
- Stored in your account profile

### 2.2 Information Collected Automatically

**Device Information:**
- Device model and OS version
- App version number
- API key (unique identifier for your account)
- Device identifier (for push notifications)

**Usage Data:**
- Which features you use and when
- How often you interact with the app
- Duration of sessions
- Timestamps of your entries
- Voice characteristics (pitch, pace, clarity metrics - not recorded audio)

**Error Logs:**
- Crash reports and error messages
- App performance metrics
- Failed API calls and debugging information

---

## 3. How We Use Your Information

We use collected data for the following purposes:

| Purpose | Data Used | Why |
|---------|-----------|-----|
| **Core Functionality** | Voice, chat, name | To transcribe, analyze, and generate responses |
| **Pattern Recognition** | Voice, chat, usage | To identify behavioral patterns and habits |
| **Guard Alerts** | Voice, behavioral data | To detect and alert concerning patterns |
| **Account Recovery** | Email | To restore your account if you reinstall the app |
| **Service Improvement** | Usage data, error logs | To fix bugs and improve features |
| **Push Notifications** | Device token | To send you timely insights and reminders |

---

## 4. Third-Party Services

We use the following third-party services to provide the App:

### 4.1 Groq
- **Service:** Speech-to-text transcription
- **Data Shared:** Audio recordings (your voice)
- **Purpose:** Converts voice to text
- **Privacy:** [Groq Privacy Policy](https://groq.com/privacy)
- **Retention:** Audio processed and discarded after transcription

### 4.2 Anthropic (Claude API)
- **Service:** AI analysis and conversation
- **Data Shared:** Your text entries, transcriptions, chat messages
- **Purpose:** Generates insights, patterns, behavioral analysis
- **Privacy:** [Anthropic Privacy Policy](https://www.anthropic.com/privacy)
- **Retention:** Data used for analysis but not stored by Anthropic

### 4.3 Resend
- **Service:** Email delivery (OTP codes)
- **Data Shared:** Your email address
- **Purpose:** Sends 6-digit verification codes
- **Privacy:** [Resend Privacy Policy](https://resend.com/privacy)
- **Retention:** Email logs may be retained per Resend's policy

### 4.4 Railway
- **Service:** Cloud hosting and database
- **Data Shared:** All user data (encrypted)
- **Purpose:** Secure storage and API infrastructure
- **Privacy:** [Railway Privacy Policy](https://railway.app/privacy)

### 4.5 Expo
- **Service:** Push notifications
- **Data Shared:** Device token (not personally identifiable)
- **Purpose:** Sends you timely alerts and insights
- **Privacy:** [Expo Privacy Policy](https://expo.io/privacy)

---

## 5. Data Storage and Security

### 5.1 How We Store Data
- **Database:** Encrypted PostgreSQL database on Railway
- **Encryption:** TLS/SSL for data in transit
- **Authentication:** API key-based access control
- **Backup:** Automated daily backups with encryption

### 5.2 Security Measures
- ✓ All data transmitted over HTTPS (encrypted in transit)
- ✓ Database access requires API authentication
- ✓ Regular security audits
- ✓ No plaintext storage of sensitive information
- ✓ Rate limiting on API endpoints (5 OTP attempts per day)

### 5.3 Data Retention
- **Voice entries:** Stored indefinitely until account deletion
- **Chat messages:** Stored indefinitely until account deletion
- **Email:** Stored while account is active
- **Device data:** Stored indefinitely until account deletion
- **Error logs:** Automatically deleted after 30 days

---

## 6. Data Sharing and Disclosure

### 6.1 What We DO Share
- Voice audio with **Groq** for transcription
- Transcribed text with **Anthropic (Claude)** for analysis
- Email address with **Resend** for OTP delivery
- Device tokens with **Expo** for push notifications
- All encrypted data with **Railway** for storage

### 6.2 What We DO NOT Do
- ❌ We do NOT sell your data to advertisers
- ❌ We do NOT share your data with marketing companies
- ❌ We do NOT use your data for any purpose without consent
- ❌ We do NOT share your email with third parties (except Resend for OTP)
- ❌ We do NOT allow Google Analytics or tracking pixels

### 6.3 Legal Requirements
We may disclose your information if required to do so by law (subpoena, court order, government request) or if we believe in good faith that disclosure is necessary to:
- Comply with applicable law
- Enforce our Terms of Service
- Protect the safety of our users

---

## 7. Your Privacy Rights and Controls

### 7.1 Access Your Data
**Endpoint:** `GET /api/mobile/privacy/summary`

You can request a summary of:
- Total number of beliefs recorded
- Total number of patterns identified
- Total people mentioned
- Total decisions tracked
- Total chat messages
- Email address on file

### 7.2 Download Your Data
All your data is in a standard format in our database. You can request a data export by emailing us at: **harshroy950@gmail.com**

### 7.3 Delete Your Data (Right to Be Forgotten)
**Endpoint:** `DELETE /api/mobile/privacy/clear`

You can permanently delete ALL your data:
- All voice entries and transcriptions
- All chat messages and conversation history
- All patterns and behavioral analysis
- All beliefs and insights
- Your email and profile information

**Deletion Process:**
1. Open Monday app → Profile tab → Privacy
2. Tap "Clear all data"
3. Confirm deletion (cannot be undone)
4. All data deleted from our servers within 30 days

### 7.4 Account Recovery
If you delete your account and want to recover it:
1. Reinstall Monday app
2. Onboarding asks for your email
3. Enter your email address
4. Receive OTP code
5. Account restored with original data

**Note:** If data has been purged (>30 days), recovery may not be possible.

---

## 8. Children's Privacy

Monday is NOT intended for children under 13 years of age. We do not knowingly collect personal information from children under 13. If we become aware that a child under 13 has provided us with personal information, we will immediately delete such information and terminate the child's account.

**Parental Concern?** Email us at: harshroy950@gmail.com

---

## 9. Data Processing and Retention

### 9.1 Processing Location
- Primary servers: United States (Railway)
- Processing: May occur in multiple jurisdictions
- Your consent to this privacy policy constitutes your consent to such transfers

### 9.2 Data Retention Summary
| Data Type | Retention Period | Deletion Method |
|-----------|-----------------|-----------------|
| Voice entries | Until account deletion | /api/mobile/privacy/clear |
| Chat messages | Until account deletion | /api/mobile/privacy/clear |
| Email address | Until account deletion | /api/mobile/privacy/clear |
| Device token | Until uninstall | Automatic |
| Error logs | 30 days | Automatic |
| Backups | 90 days | Automatic |

---

## 10. International Data Transfers

If you are located in the European Union, United Kingdom, or other regions with data protection laws, please note:

- We transfer data internationally to provide the service
- We rely on lawful mechanisms for such transfers
- You consent to such transfers by using the App

**GDPR Compliance:**
- Right to access your personal data
- Right to correct inaccurate data
- Right to delete data (right to be forgotten)
- Right to data portability
- Right to object to processing

To exercise any of these rights, email: **harshroy950@gmail.com**

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting the new Privacy Policy on this page
- Requiring your acceptance on next app launch

**Your continued use of the App following the posting of revised Privacy Policy means that you accept and agree to the changes.**

---

## 12. Contact Us

If you have any questions about this Privacy Policy, please contact us at:

**Email:** harshroy950@gmail.com  
**App:** Monday  
**Developer:** Harsh Roy  
**Last Updated:** April 22, 2026

---

## 13. Summary (TL;DR)

✅ **What we collect:**
- Voice recordings (transcribed to text)
- Chat messages
- Email (for OTP only)
- Device info for push notifications

✅ **What we do:**
- Analyze your patterns
- Provide personalized insights
- Send you alerts and reminders
- Keep your data secure

❌ **What we don't do:**
- Sell your data
- Show ads
- Track you
- Share your email (except for OTP)

✅ **Your rights:**
- Delete all your data anytime
- Download your data
- Recover your account via email
- Request what data we have

**Bottom line:** We collect minimal data to make Monday work. We keep it private. You can delete everything anytime.

---

**Questions?** Email: harshroy950@gmail.com
