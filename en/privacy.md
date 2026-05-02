# DeMotion — Privacy Policy

**Effective date:** 2026-05-02
**Developer:** Maciej Siemiński (sole proprietor)
**Contact:** maciek.sieminski@gmail.com

DeMotion is a mobile application that strips Live Photo (iOS) and Motion Photo (Android) video components from existing photos in your device's photo library, in place. This document describes what data DeMotion processes, how, and why.

## Plain summary

- **DeMotion never uploads your photos anywhere.** All processing happens on your device.
- **DeMotion does not collect personal data about you.** No accounts, no analytics, no tracking by us.
- **DeMotion uses Google AdMob** to show ads in the free tier. AdMob may collect device identifiers and ad-interaction data per its own policy.
- **DeMotion uses Apple App Store / Google Play in-app purchases** for the optional Premium upgrade. Apple/Google process the payment; we receive only an entitlement flag (Premium yes/no).

## What data DeMotion accesses on your device

| Data | Why | Stays on device | Goes anywhere |
|---|---|---|---|
| Your photos in the photo library | To find Live/Motion Photos and strip the video component | Yes | No |
| Photo metadata (capture date, location, EXIF) | Preserved as-is during in-place edit | Yes | No |
| Theme/language/Premium-active preference | Saved to local app storage | Yes | No |
| Advertising identifier (IDFA on iOS, AAID on Android) | Sent to AdMob if you grant tracking | No (sent to AdMob) | Yes — AdMob only |
| In-app purchase receipt | Verified locally; entitlement saved | Yes | No (Apple/Google handle the receipt server-side) |

## DeMotion does NOT

- upload, copy, or transmit your photos to any server, ever;
- collect your name, email, address, phone, biometric, health, financial, or contact data;
- use crash reporting in this version (we may consider it in a future version, with explicit prior notice);
- use analytics in this version (we may consider it in a future version, with explicit prior notice);
- track you across other apps or websites beyond what AdMob does for advertising.

## Third-party services

DeMotion uses the following third parties:

### Google AdMob
- Purpose: serve banner and interstitial ads in the free tier.
- Data shared with AdMob: advertising identifier, device type, OS version, ad-interaction events.
- AdMob privacy: https://policies.google.com/privacy
- Opt out: enable Premium (purchase to remove ads) or revoke tracking permission in your device settings (iOS: Settings → Privacy → Tracking; Android: Settings → Privacy → Ads → Reset advertising ID / Delete advertising ID).

### Apple App Store / Google Play (in-app purchases)
- Purpose: process optional Premium upgrade purchases (annual subscription, lifetime, tip jar).
- Data shared: handled entirely by Apple/Google; we receive only a Premium-active flag.
- Apple privacy: https://www.apple.com/legal/privacy/
- Google privacy: https://policies.google.com/privacy

## Permissions DeMotion requests

| Permission | Why | Required? |
|---|---|---|
| Photo library (read + write) | Core feature: find Live Photos and edit them in place. Without this, the app cannot function. | Yes |
| App Tracking Transparency (iOS) | Required by Apple for AdMob personalized ads. You can decline; ads will be non-personalized. | No |
| Manage Media (Android 11+) | Optional. If granted, Motion Photos can be edited in batch without per-photo confirmation. If denied, the app will ask for confirmation per photo. | No |

## Your rights

- **You can stop using DeMotion at any time.** Uninstalling removes all local app data.
- **You can request information about data we hold.** Since DeMotion does not collect personal data on a server, we have no per-user data to deliver. Your local on-device data is yours alone.
- **You can revoke photo library access** in your device's privacy settings at any time.
- **EU users (GDPR):** Maciej Siemiński is the data controller for DeMotion. Since DeMotion processes data only on your device, the legal basis is your consent (you agreed by installing and granting permissions). You may withdraw consent at any time by uninstalling the app or revoking permissions.
- **California users (CCPA):** DeMotion does not sell your personal information, period.
- **Children:** DeMotion is not directed at children under 13. We do not knowingly process data from children under 13.

## Changes to this policy

If we change anything material (e.g., add analytics or crash reporting), the new policy will be published at the same URL with a new effective date. We will note material changes in the app's release notes.

## Contact

For privacy questions, write to maciek.sieminski@gmail.com.
