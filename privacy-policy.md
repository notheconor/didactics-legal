---
layout: default
title: Privacy Policy
---
# Privacy Policy

**Didactics** is developed by Night Float Labs LLC ("we", "us", or "our").
Effective date: April 1, 2026

---

## Overview

Didactics is an educational app for general surgery residents and medical students. The short version: **Free and Pro users have no cloud data**. Your study activity stays on your device unless you create an account and subscribe to Pro+.

---

## What We Collect and Why

### Free and Pro Users — Local by Default

If you use Didactics on the Free or Pro plan without creating an account, **no personal data leaves your device**. All study progress, flashcard reviews, quiz results, notes, highlights, and settings are stored locally in the app's private storage.

### Account Creation (optional)

If you create an account, we collect:

- **Email address** — used for authentication and account recovery.
- **Display name** (optional) — shown in the leaderboard and streak views.
- **User ID** — a UUID generated at sign-up, used to associate your data across devices.

Authentication is handled by **Supabase** (supabase.com). Your credentials are processed and stored by Supabase in accordance with their [privacy policy](https://supabase.com/privacy).

### Cloud Sync (Pro+ only)

If you subscribe to Pro+, your study data is synced to Supabase so it is available across multiple devices. Data synced includes:

- Study plan progress and module completion history
- Flashcard SRS review logs
- Quiz session results and accuracy metrics
- Streak and streak-freeze usage

This data is stored in a Supabase-hosted PostgreSQL database in the United States (AWS us-east-1). It is associated with your user ID and is never shared with third parties for advertising or analytics purposes.

Free and Pro users who have not enabled cloud sync have **no data stored on our servers**.

### Subscriptions and Purchases

Purchase receipts and subscription status are validated through **RevenueCat** (revenuecat.com). RevenueCat receives an anonymous installation ID and your purchase transaction record to verify entitlements. No personally identifiable information is shared with RevenueCat beyond what Apple or Google provide as part of the transaction. See RevenueCat's [privacy policy](https://www.revenuecat.com/privacy).

### Push Notifications (Pro+ only)

If you enable push notifications, reminders are scheduled **on-device** using the Expo notifications SDK. No push token is transmitted to our servers.

---

## Data Retention

- **Local data** is retained until you uninstall the app or clear app data.
- **Account data** (email, display name) is retained until you delete your account.
- **Cloud sync data** is deleted within 30 days of account deletion.

To delete your account and all associated cloud data, go to **Settings > Account > Delete Account**. To clear all local data, go to **Settings > Reset All Data**.

---

## Third-Party Services

| Service | Purpose | Privacy Policy |
|---|---|---|
| Supabase | Authentication and cloud sync | https://supabase.com/privacy |
| RevenueCat | Subscription management | https://www.revenuecat.com/privacy |
| Expo | Push notification SDK | https://expo.dev/privacy |

The app does not use advertising SDKs, third-party analytics, or crash-reporting services.

---

## Health and Patient Data

This app contains only educational content for training purposes. It does not collect, process, or display any patient health information. It is not a clinical tool and is not subject to HIPAA.

---

## Children's Privacy

Didactics is intended for medical students and healthcare professionals. We do not knowingly collect personal information from users under 13 years of age.

---

## GDPR

Free and Pro users have no cloud data, so GDPR obligations are minimal. Signed-in Pro+ users may request export or deletion of their data by contacting support@nightfloatlabs.com or using the in-app account deletion flow.

---

## Changes to This Policy

We will update this page when our data practices change. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## Contact

Night Float Labs LLC
support@nightfloatlabs.com
