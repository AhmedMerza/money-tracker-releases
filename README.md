# MoneyTrack — Releases

**MoneyTrack** is a privacy-first Android money tracker built for Bahrain bank
SMS. It auto-creates transactions from your bank's text messages, categorizes
them with rules + a learning layer, and reminds you to review the rest.
**Everything stays on your phone — there's no server.**

This repo hosts the signed APK releases. Source code lives in
[**money-tracker**](https://github.com/AhmedMerza/money-tracker).

---

## 📥 Download

Grab the latest `money-tracker-vX.Y.Z.apk` from the
**[Releases](https://github.com/AhmedMerza/money-tracker-releases/releases/latest)**
page and open it on your Android phone.

> Requires **Android 8.0 (API 26)** or newer. Android only.

---

## 📲 Install (one-time setup)

Because the app reads bank SMS to auto-log transactions, Android adds a couple
of safety gates the first time. You only do these once.

### 1 · Get past Play Protect
When the install dialog says **"Blocked to protect your device"**:
1. Tap **More details**
2. Scroll to the bottom → **Install anyway** (may be greyed out for ~5 seconds — wait it out)

If there's no **Install anyway** button:
1. **Settings → Security & privacy → Google Play Protect → ⚙ (top-right)**
2. Turn **off** "Scan apps with Play Protect"
3. Install the APK
4. Turn Play Protect back **on** — already-installed apps are left alone

### 2 · Unlock Restricted Settings (Android 13+)
The first time the app asks for SMS permission, Android silently denies it until
you allow restricted settings:
1. **Settings → Apps → MoneyTrack → ⋮ (top-right) → "Allow restricted settings"**
2. Go back → **Permissions → SMS → Allow** (and **Notifications → Allow** while you're there)

### 3 · Open the app
On first launch it scans your inbox for past bank messages and starts logging
new ones automatically.

---

## 🔄 Updates

Updates install **over** the previous version — they're signed with the same key,
so **your data is kept** and Play Protect won't re-flag a trusted app.

In the app: **Settings → App → Check for updates** (or turn on **Auto-check on
open**) fetches the newest release and shows the changelog **in-app** — no need
to come back here.

---

## 🔒 Privacy

- **100% on-device.** No account, no server, no analytics.
- Bank SMS are read locally and **never leave your phone**.
- Optional Google Drive backup goes to a **private app-only folder** you control.
