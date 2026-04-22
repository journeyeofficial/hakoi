---
layout: default
title: Hakoi — Privacy Policy
---

# Hakoi — Privacy Policy

**Last Updated:** April 22, 2026

**Effective Date:** April 13, 2026

---

## 1. Introduction

This Privacy Policy describes how Journeye ("we," "us," or "our") collects, uses, stores, shares, and protects your personal information when you use the Hakoi mobile application and related services (collectively, the "Service"). Hakoi is a habit-tracking application available on Android, iOS, and other platforms.

We are committed to protecting your privacy. Please read this Privacy Policy carefully to understand our practices regarding your data. By using the Service, you agree to the collection and use of information in accordance with this policy.

**Data Controller:** Putz Tímea Edit, Budapest, Hungary  
**Contact Email:** journeye.official@gmail.com

---

## 2. Information We Collect

### 2.1 Information You Provide Directly

When you create an account or use the Service, you may provide us with:

- **Account Information:** Email address, username, and password (if using email/password registration). If you register through a third-party authentication provider (Google or X), we receive your email address and basic profile information from that provider.
- **Habit Data:** Habit titles, descriptions, categories, icons, colors, frequency settings, scheduled times, priorities, start and end dates, and any notes you attach to habits.
- **Habit Completion Data:** Daily completion status (completed, failed, skipped), numerical values, timed durations, checklist completion states, and associated notes.
- **Timer Data:** Time tracking records associated with timed habits, including duration and timestamps.
- **Category Data:** Custom categories you create, including names, icons, and colors.
- **Reminder Settings:** Scheduled reminder times, alarm preferences, timezone, and notification settings.
- **Profile Settings:** Profile visibility preferences (public or private), username, and display settings.

### 2.2 Information Generated Through Use

As you use the Service, the following information is generated:

- **Karma and Gamification Data:** Karma points earned, karma logs, and related gamification metrics.
- **Leaderboard Data:** Rankings derived from your habit completion and Karma data.
- **Contract Data:** Accountability partnerships you form with other users, including the linked habit and participating user references.
- **Backup Metadata:** Timestamps and scheduling preferences related to your cloud backups.
- **Subscription Information:** Your subscription tier (Free, Plus, or Premium), purchase confirmation timestamps, and subscription status.

### 2.3 Information Collected Automatically

- **Device Information:** We may collect general device information necessary for the Service to function, such as operating system version and device type, for the purpose of ensuring compatibility and delivering notifications.
- **Authentication Tokens:** Session tokens and authentication identifiers managed by Supabase for maintaining your login state.

### 2.4 Information We Do NOT Collect

We want to be transparent about what we do not collect:

- We do **not** use analytics or tracking SDKs (no Firebase Analytics, Google Analytics, Mixpanel, Amplitude, Segment, or similar services).
- We do **not** collect your IP address for tracking purposes.
- We do **not** access your camera, microphone, contacts, calendar, location, or health/fitness sensors.
- We do **not** collect browsing history or usage patterns outside of the Service.
- We do **not** serve advertisements or share data with advertising networks.
- We do **not** use crash reporting services (no Sentry, Crashlytics, or similar).

---

## 3. How We Use Your Information

We use the information we collect for the following purposes:

- **Providing the Service:** To operate, maintain, and deliver the core features of Hakoi, including habit tracking, reminders, timers, statistics, and gamification.
- **Cloud Sync and Backup:** To synchronize your data across devices and provide backup and restore functionality through Supabase.
- **Social Features:** To enable Leaderboard rankings, Contracts (accountability partnerships), Karma sharing, friend connections, and user profile display for users who opt in to social features.
- **Subscription Management:** To manage your subscription status, verify entitlements, and provide access to paid features through RevenueCat.
- **Authentication:** To verify your identity and maintain secure access to your Account via Supabase Auth and third-party OAuth providers.
- **Notifications:** To deliver habit reminders, alarms, and in-app notifications you have configured.
- **Home Screen Widget:** To display your habit data on your device's home screen widget, if you choose to use this feature.
- **Service Improvement:** To identify and fix bugs, improve features, and ensure the Service functions correctly.
- **Communication:** To respond to your support requests or inquiries.

---

## 4. Legal Basis for Processing (GDPR)

If you are located in the European Economic Area (EEA), the United Kingdom, or Switzerland, we process your personal data on the following legal bases:

- **Performance of a Contract:** Processing necessary to provide the Service to you under our Terms of Service (e.g., account creation, habit tracking, backups, subscription management).
- **Legitimate Interests:** Processing necessary for our legitimate interests, provided these are not overridden by your rights (e.g., improving the Service, ensuring security, preventing abuse).
- **Consent:** Where you have given consent for specific processing activities (e.g., enabling a public profile, participating in social features). You may withdraw consent at any time.
- **Legal Obligation:** Processing necessary to comply with legal requirements applicable to us.

---

## 5. Data Storage and Security

### 5.1 Local Storage

Your habit data is stored locally on your device in an **encrypted SQLite database** using SQLite3MultipleCiphers (sqlcipher-compatible encryption). The encryption key is a 32-byte randomly generated value stored securely in your device's hardware-backed keystore (Android Keystore or iOS Keychain). The database operates in WAL (Write-Ahead Logging) mode for performance and data integrity. On devices where hardware-backed keystore is unavailable, software-backed encryption is used as a fallback. We recommend using devices running Android 6.0+ or iOS 13+ for optimal security.

### 5.2 Cloud Storage

When you create a backup or use features requiring cloud synchronization (social features, Contracts, Leaderboard), your data is stored on **Supabase** infrastructure. Supabase provides:

- PostgreSQL database with row-level security policies.
- TLS/HTTPS encryption for all data in transit.
- Server-side access controls and authentication verification.

Supabase infrastructure may process and store data in the European Union, the United States, or other regions depending on the project configuration. If you are located in the EEA, UK, or Switzerland and your data is transferred to a country outside the EEA that has not been deemed to provide an adequate level of data protection, we rely on Standard Contractual Clauses (SCCs) approved by the European Commission as the legal mechanism for such transfers. For further details on Supabase's infrastructure and data handling, refer to their privacy policy at [https://supabase.com/privacy](https://supabase.com/privacy).

### 5.3 Security Measures

We implement the following security measures:

- At-rest encryption of local database on your device.
- Secure storage of encryption keys using platform-native hardware keystores.
- HTTPS/TLS encryption for all network communications.
- Server-side RPC functions for sensitive operations (e.g., account deletion, subscription sync) to prevent client-side manipulation.
- Row-level security policies on cloud database tables.

While we take reasonable measures to protect your data, no method of electronic transmission or storage is 100% secure. We cannot guarantee absolute security.

---

## 6. Data Sharing and Third-Party Services

### 6.1 Third-Party Service Providers

We share limited data with the following third-party service providers who assist us in operating the Service:

| Provider | Purpose | Data Shared | Privacy Policy |
|----------|---------|-------------|----------------|
| **Supabase** | Cloud database, authentication, backup storage | Account data, habit data (when syncing/backing up), profile data | [supabase.com/privacy](https://supabase.com/privacy) |
| **RevenueCat** | Subscription and in-app purchase management | User ID, subscription status, purchase history | [revenuecat.com/privacy](https://www.revenuecat.com/privacy) |
| **Google** (Sign-In) | OAuth authentication | Email address, basic profile (when using Google Sign-In) | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **X (Twitter)** | OAuth authentication | Email address, basic profile (when using X sign-in) | [x.com/privacy](https://x.com/en/privacy) |

### 6.2 Other Users

If you enable a public profile or participate in social features, the following information may be visible to other Hakoi users:

- Your username.
- Your Karma score and Leaderboard ranking.
- Your participation in Contracts (visible to the other party).

Your habit details, notes, completion data, and other personal Content are **never** shared with other users.

### 6.3 When We May Disclose Information

We may disclose your information in the following circumstances:

- **Legal Requirements:** If required to do so by law, regulation, legal process, or governmental request.
- **Protection of Rights:** To protect our rights, property, or safety, or the rights, property, or safety of our users or others.
- **Business Transfers:** In connection with a merger, acquisition, reorganization, or sale of assets, in which case your data would be transferred to the successor entity under equivalent privacy protections.
- **With Your Consent:** When you have given us explicit consent to share your information for a specific purpose.

### 6.4 No Sale of Personal Data

We do **not** sell, rent, or trade your personal information to third parties for marketing, advertising, or any other commercial purposes.

---

## 7. Data Retention

We retain your personal data for as long as your Account is active or as needed to provide the Service. Specifically:

- **Account Data:** Retained until you delete your Account.
- **Habit and Usage Data:** Retained until you delete your Account or remove individual data items within the Service.
- **Cloud Backups:** Retained until you manually delete your backup or delete your Account.
- **Subscription Records:** Retained as necessary for billing records and legal compliance after Account deletion. RevenueCat may retain transaction records in accordance with their data retention policies.
- **Aggregated/Anonymized Data:** We may retain truly anonymized, aggregated statistical data (e.g., average completion rates across all users) that cannot identify any individual user, for analytical and service improvement purposes indefinitely. Individual pseudonymized or de-identified records are not retained beyond the applicable retention periods above.

When you delete your Account, all personally identifiable data is permanently deleted from our servers via a server-side deletion function. This process is executed immediately and removes your authentication record, profile, habits, habit instances, backups, and all associated data within 24 hours. Transaction records held by RevenueCat may be retained for up to 7 years for tax and legal compliance purposes in accordance with their data retention policies.

---

## 8. Your Rights

Depending on your location, you may have the following rights regarding your personal data:

### 8.1 Rights Under GDPR (EEA, UK, Switzerland)

- **Right of Access:** You have the right to request a copy of the personal data we hold about you.
- **Right to Rectification:** You have the right to request correction of inaccurate personal data.
- **Right to Erasure ("Right to Be Forgotten"):** You have the right to request deletion of your personal data. You can exercise this right by deleting your Account through the Service's settings.
- **Right to Restriction of Processing:** You have the right to request that we restrict processing of your personal data under certain conditions.
- **Right to Data Portability:** You have the right to receive your personal data in a structured, commonly used, and machine-readable format. Upon request, we will provide your data (including habit data, completion records, categories, Karma history, and profile information) in JSON or CSV format within 30 days.
- **Right to Object:** You have the right to object to processing of your personal data based on legitimate interests.
- **Right to Withdraw Consent:** Where processing is based on consent, you have the right to withdraw consent at any time.

### 8.2 Rights Under CCPA (California Residents)

If you are a California resident, you have the following rights under the California Consumer Privacy Act:

- **Right to Know:** You have the right to request disclosure of the categories and specific pieces of personal information we have collected about you.
- **Right to Delete:** You have the right to request deletion of your personal information.
- **Right to Correct:** You have the right to request correction of inaccurate personal information we hold about you.
- **Right to Non-Discrimination:** We will not discriminate against you for exercising your privacy rights.
- **Right to Opt-Out of Sale/Sharing:** We do not sell, share, or disclose personal information for monetary or other valuable consideration. You therefore have no need to opt out, but you may submit a request to confirm this at any time.

### 8.3 Exercising Your Rights

To exercise any of these rights, please contact us at **journeye.official@gmail.com**. We will respond to your request within 30 days (or within the time period required by applicable law).

For account deletion, you can delete your Account directly within the Service's settings, which permanently removes all your data from our servers.

---

## 9. Children's Privacy

The Service is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe that your child has provided us with personal information, please contact us at **journeye.official@gmail.com**. If we become aware that we have collected personal information from a child under 13 without verification of parental consent, we will take steps to delete that information from our servers promptly.

---

## 10. International Data Transfers

If you are accessing the Service from outside the jurisdiction where our servers are located, your data may be transferred to and processed in a different country. By using the Service, you consent to such transfers. We ensure that any international transfers of personal data are made in compliance with applicable data protection laws, including the use of appropriate safeguards such as Standard Contractual Clauses where required.

---

## 11. Cookies and Tracking Technologies

The Hakoi mobile application does **not** use cookies, web beacons, pixel tags, or similar tracking technologies. We do not track your activity across third-party websites or applications.

If you access any Hakoi-related web pages (such as this Privacy Policy or Terms of Service), standard web server logs may record your access, but we do not use these for tracking or profiling purposes.

---

## 12. Push Notifications and Alarms

The Service uses push notifications and alarms to deliver habit reminders you configure. These notifications are processed locally on your device using the operating system's native notification system. We do not use third-party push notification services that would transmit notification content through external servers.

You can manage or disable notifications at any time through your device's system settings or within the Service's settings.

---

## 13. Home Screen Widget

The Service offers an optional home screen widget that displays your habit data. The widget reads data exclusively from your local encrypted database and does not transmit any data to external servers. Sync or backup operations do not occur through the widget. Widget display preferences (theme, language) are synchronized with the main application through local shared preferences on your device.

---

## 14. Data Breach Notification

In the event of a personal data breach that is likely to result in a high risk to your rights and freedoms, we will notify affected users without undue delay and, in compliance with applicable law (including GDPR Article 34), within 72 hours of becoming aware of the breach. Notification will be provided via email (if we have your email on file) or through an in-app notice.

---

## 15. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes to our practices, technology, legal requirements, or other factors. When we make material changes, we will notify you by updating the "Last Updated" date at the top of this document and, where appropriate, providing notice through the Service (e.g., an in-app notification).

We encourage you to review this Privacy Policy periodically to stay informed about how we protect your data.

---

## 16. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Putz Tímea Edit**  
**Email:** journeye.official@gmail.com  
**Location:** Budapest, Hungary

If you are located in the EEA and believe that your data protection rights have not been adequately addressed, you have the right to lodge a complaint with your local data protection supervisory authority. In Hungary, this is the Nemzeti Adatvédelmi és Információszabadság Hatóság (NAIH) — [https://naih.hu](https://naih.hu).

---

*By using Hakoi, you acknowledge that you have read and understood this Privacy Policy.*
