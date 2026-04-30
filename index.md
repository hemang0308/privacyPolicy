# Privacy Policy — Jashn

**Last updated:** 30 April 2026

This Privacy Policy describes how the Jashn mobile application ("Jashn", "we",
"our", or "the app") collects, uses, and shares information when you use the
app. By using Jashn you agree to the practices described below.

---

## 1. Who we are
Jashn is operated by **Jashn Team**, **Mathura, Uttar Pradesh, India**. For any privacy-related question, contact us at
**jashn.cxsupport@gmail.com** (replace with your real support address).

## 2. Information we collect

### 2.1 Information you provide
- **Account information** — phone number, email address, display name, profile
  photo (optional), and authentication credentials when you sign up or sign in.
- **Booking information** — event date, occasion, guest count, venue
  preferences, and free-text notes you enter while booking.
- **Host information** — when you list a venue you provide venue name, address,
  capacity, photos, menu cards, pricing, and bank/UPI details required for
  payouts.
- **Communications** — messages, ratings, and reviews you submit through the
  app.

### 2.2 Information collected automatically
- **Approximate and precise location** — only when you tap "Use my location" on
  the occasion screen, the location picker, or the venue map. Coordinates are
  used in-memory to fetch nearby venues; they are not written to your profile.
- **Device + diagnostic data** — when Sentry is enabled we collect crash
  reports, stack traces, OS version, device model, and the app version. We do
  not attach personal identifiers (`sendDefaultPii = false`).
- **Usage data** — minimal in-app analytics to understand which screens are
  used. We do not use third-party advertising SDKs.

### 2.3 Information from cameras and microphones
- **Camera / photo library** — used (a) when a host uploads venue photos or
  scans a menu card with on-device OCR, and (b) when a guest sets a profile
  photo. Images are uploaded to our Supabase storage only when you explicitly
  attach them.
- **Microphone** — used only while you are pressing the voice-search button.
  Audio is processed by the Android speech recognizer (on-device where
  supported) and is **never stored** by Jashn.

## 3. How we use the information
We use the information to:
- Authenticate you and keep your session secure.
- Show venues, menus, and prices relevant to your selected city and occasion.
- Process bookings and notify hosts of new requests.
- Help hosts manage listings, calendars, payouts, and customer messages.
- Detect abuse, fraud, and platform misuse.
- Improve reliability via crash reports.

## 4. How we share information
We share data only with the following categories of recipients:
- **Supabase** (database, auth, storage) — our backend host.
- **Google Maps Platform** — to render maps and geocode addresses.
- **Sentry** — crash diagnostics (only if you have not opted out).
- **SMS / OTP provider (e.g. Fast2SMS)** — to deliver one-time passwords to
  your phone number.
- **Hosts of venues you book** — your name, contact number, and booking
  details so they can serve you.
- **Law enforcement / regulators** — when required by valid legal process.

We do **not** sell personal data and we do **not** use it for ad targeting.

## 5. Data retention
- Account data is retained while your account is active.
- Booking and payout records are retained for the period required by Indian
  tax / accounting law (typically 7 years).
- Crash reports are retained by Sentry for 90 days.
- You may request account deletion from inside the app or by emailing
  **jashn.cxsupport@gmail.com**; we will erase or anonymise your data within 30 days
  except where retention is legally required.

## 6. Security
- All traffic uses HTTPS / TLS 1.2+.
- Passwords and OTPs are never stored in plaintext.
- Android backups are disabled (`allowBackup="false"`) so auth tokens cannot
  be exfiltrated via `adb backup`.
- Access to production data is limited to authorised personnel.

## 7. Children
Jashn is not directed at children under 13 (or the equivalent minimum age in
your jurisdiction). We do not knowingly collect data from children.

## 8. Your rights
Depending on your jurisdiction (DPDP Act 2023 in India, GDPR in the EU, etc.)
you may have rights to access, correct, port, or delete your data, and to
withdraw consent. Email **jashn.cxsupport@gmail.com** to exercise any of these rights.

## 9. Changes to this policy
We will post the updated policy at the same URL and update the "Last updated"
date. Material changes will be announced inside the app.

## 10. Contact
**Email:** jashn.cxsupport@gmail.com
**Postal:** [Legal entity, full postal address]
