# Dopamine Tank Privacy Policy

Effective date: November 12, 2026

Dopamine Tank ("the app") is usable anonymously without account registration. This policy describes what we process.

## 1. Information We Process

| Item | Description | When |
|---|---|---|
| Display name | A nickname you choose (shown to friends) | Group create/join |
| Anonymous account identifier | Firebase anonymous auth UID (no email or phone number collected) | First launch |
| Group membership | Group identifier, pokes, water-ticket records | During use |
| Daily screen-time total | Your own device's total daily usage in whole minutes. **Per-app usage details are never collected or transmitted** | Measured automatically |
| Water-ticket request message | Short unlock-request text sent to a friend (optional) | User input |
| Subscription status | Whether you hold a paid plan (Pro/Group/Lifetime) and receipt verification results | Purchase |
| Advertising identifier | Device advertising ID for showing ads (Google AdMob SDK) | Ad display |
| Anonymous usage statistics (optional) | **Only if you turn on "Share anonymous usage stats"**: app opens and session length (in ranges), which features you use (onboarding steps, group create/join/leave, pokes, water tickets, skins, widgets, optional rewarded-ad stages and unlock results), app version, device model, OS version, language and approximate region (derived by Google from the IP address, which is not stored by us). It never contains app names, per-app usage, exact times, group or display names | After you opt in |

The app does **not** collect call content, message content, screen content, keystrokes, or per-app usage breakdowns.

## 2. Purpose

- Providing the shared water-tank service (group level calculation, locking/unlocking, pokes, water tickets)
- Verifying paid subscription entitlements
- Showing optional rewarded ads chosen by the user for a five-minute unlock on this device. Google UMP checks the required consent before ad requests; where applicable, choices can be changed using "Ad privacy choices" in Settings.
- Improving the app with aggregated, anonymous usage statistics (only with your consent)

We do not use your information for marketing, and we do not sell or share it with third parties for their own purposes.

## 3. Retention & Deletion

- Uninstalling the app removes its local data. Deleting a group removes the group document as described below. Uninstalling the app does not automatically delete events already received by analytics providers; see Section 4 for analytics controls and deletion requests.
- Deleting a group immediately deletes the group document; residual records become inaccessible.

## 4. International Transfer & Processors

- Data is stored in Google Cloud Firestore (us-central1, United States). Google maintains adequate transfer safeguards.
- The Google AdMob SDK processes the advertising identifier for ad display.
- Google Analytics for Firebase (Google LLC, United States) processes the optional usage statistics. It is off until you opt in; you can turn it off at any time in Settings → Account, which also deletes the analytics identifier on the device. We do not use the advertising identifier for analytics and do not link analytics to your account.
- Starting with version 1.0.11, PostHog Cloud (United States) also processes the same consented product-interaction events, using a separate random app-instance identifier that is not linked to your Firebase account or advertising ID. It does not receive screen-time data, app lists, names, email addresses, or screen recordings. Person profiles, session replay, automatic interaction capture, and IP-based geolocation enrichment are disabled. Turning statistics off stops future requests, drops pending events, and removes the local PostHog identifier; it does not retroactively erase previously received server events. Contact us for deletion requests.
- No other third-party sharing occurs.

## 5. Your Rights

- Delete your data at any time by deleting your group in the app or uninstalling the app.
- You can view and edit your display name directly in the app.
- For any other request, contact us below.

## 6. Children

The app is not directed at children under 14 (or under 13 where applicable by local law) and we do not knowingly collect their personal information.

## 7. Contact

- Developer: Jin Minseong
- Email: developerminsing@gmail.com

## 8. Changes

Policy changes will be posted on this page with a new effective date.
