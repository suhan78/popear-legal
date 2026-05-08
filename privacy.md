---
title: Privacy Policy
permalink: /privacy/
---

# PopEar Privacy Policy

**Effective date:** May 9, 2026

PopEar is an iOS app that helps you practice English listening using curated YouTube clips and a spaced-repetition review system. This policy explains what we collect, how we use it, and your rights over it.

We keep this simple because the app is simple: no ads, no tracking SDKs, no selling data, no marketing profiling.

**Contact:** [support@normaleer.com](mailto:support@normaleer.com)

## What we collect

**Anonymous account identifier**

- When you first open the app, Supabase generates an anonymous user ID for you. This ID is not tied to your name, email, phone, or any real-world identity. You can use PopEar fully without providing any personal information.
- If you later choose to upgrade to a permanent account (for example by linking an email), we will collect only the email address you provide at that point.

**Learning activity**

- Which clips you watch and when (watch history).
- Your progress within a clip (step completion, playback position, phase within Step 2).
- Your ratings of clip difficulty.
- Sentences you save and the flashcards they become.
- Spaced-repetition review outcomes (cards reviewed, your ratings, timestamps).
- Derived scores (vocabulary score, listening score, daily streak).

**App preferences**

- Settings you configure inside the app, including your native language, learning goal, and skill level. These are stored both on your device and on our servers so they persist across reinstalls and across devices.

**Device information**

- Technical information the app needs to run (iOS version, device model). We do not build a device fingerprint and we do not use this for advertising.

## What we do not collect

- No name, phone number, precise location, contacts, photos, health data, or any identifier we don't need.
- No analytics or advertising SDKs.
- No selling, renting, or sharing your data with advertisers or data brokers.

## How we use your data

We use the data above solely to:

- Deliver the learning experience (play clips, track progress, run spaced repetition).
- Personalize which clips are recommended to you based on your in-app activity and skill level.
- Diagnose bugs and improve the app.

We do not use your data for advertising, profiling outside the app, or any purpose not listed here.

## Where your data is stored

- **On your device:** progress and flashcard data is stored locally on your iPhone using SQLite and AsyncStorage. Your Supabase session token is stored in the iOS Keychain.
- **On our servers:** the same data is synced to a Supabase Postgres database so you don't lose progress if you reinstall or switch devices. Supabase, Inc. is our backend provider; their privacy policy is at [https://supabase.com/privacy](https://supabase.com/privacy).

All data in transit is encrypted with HTTPS/TLS. Server-side access is restricted by Row Level Security so each user can only read and write their own rows.

## International data transfers

Our backend runs on Supabase's infrastructure in Singapore. Depending on your location, your data may be processed in or transferred to Singapore or to other countries as part of normal cloud service operations. Where required by law (such as for users in the European Union or United Kingdom), we rely on standard contractual clauses or equivalent legal mechanisms to safeguard your data during transfer.

## Third parties

PopEar uses a small, deliberate set of third-party services:

- **Supabase:** backend database, authentication, and file storage. The data described above is stored on Supabase infrastructure.
- **YouTube:** video clips play through YouTube's official iframe player. When you watch a clip, your device communicates with YouTube directly to stream the video, and YouTube's privacy policy applies to that interaction ([https://policies.google.com/privacy](https://policies.google.com/privacy)). We do not control what YouTube collects during playback, and PopEar does not tell YouTube who you are. By using PopEar, you are also bound by the YouTube Terms of Service, which you can find at [https://www.youtube.com/t/terms](https://www.youtube.com/t/terms).
- **Apple:** distributes the app via the App Store under Apple's own privacy practices.

We do not use any other third-party SDK for tracking, analytics, crash reporting, or advertising as of the effective date above.

## Data retention

- Learning activity (watch history, flashcards, reviews) is kept as long as your account exists, because it's what makes the app useful.
- If you delete your account using the in-app button, your server-side data is removed immediately. If you request deletion by email, we remove your server-side data within 30 days.
- Local data on your device is removed when you delete the app. However, your account credentials are stored in the iOS Keychain, which persists across app uninstalls. This means reinstalling PopEar on the same device will restore your existing anonymous account along with all server-side data. To fully delete your account and all associated data, use the in-app delete option or request it by email (see Your Rights below).

## Your rights

At any time you can:

- **Access your data:** email us and we will provide a machine-readable export.
- **Delete your data:** the fastest way is in the app: open Settings, tap **Delete my data**, and confirm. This immediately removes your account and all associated data from our servers, wipes local data on your device, and signs you out. If you can't access the app, email us with the subject line "Delete my account" along with the anonymous user ID; we will delete your server-side data within 30 days and confirm by reply.
- **Ask questions:** email us about anything in this policy.

If you are in the European Union, United Kingdom, or California, you have additional rights under GDPR, UK GDPR, or CCPA, including access, correction, deletion, portability, and objection. Exercise them by contacting us at the email above.

## Children

PopEar is not directed at children under 16, and we do not knowingly collect data from children under 16. We do not actively verify age beyond the App Store's age rating system and the parental controls available on iOS. If you believe a child has used the app, contact us and we will delete their data.

## Security

- Data in transit is encrypted with TLS.
- Session tokens on iOS are stored in the Keychain, which is hardware-backed.
- Server data is protected by Supabase's security controls and per-user Row Level Security policies.

No system is perfectly secure, but we follow industry-standard practices and only collect what the product actually needs.

## Changes to this policy

We may update this policy as the app evolves. For example, we may in future add limited crash reporting or anonymous usage analytics to help us diagnose issues and improve PopEar; if we do, we will limit collection to what is necessary for the stated purpose, update this policy, and notify you in-app before any change takes effect. We will also update the effective date at the top of this page when material changes are made.

## Contact

**Email:** [support@normaleer.com](mailto:support@normaleer.com)
