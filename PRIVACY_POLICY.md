# Privacy Policy for CallMusicGuard

**Last Updated:** 2026-11-20

This Privacy Policy describes how **CallMusicGuard** (`com.dx9901mk5.callmusicguard`) handles information when you use the application.

## 1. Notification Access & Media Control (On-Device Only)
- CallMusicGuard uses Android's `NotificationListenerService` solely **on your device** to detect incoming/ongoing call notifications from messaging apps you select (such as LINE, WhatsApp, Telegram, or Messenger) so it can pause your music during calls and resume playback afterward.
- Notification contents, caller names, messages, and installed app lists are **never** stored permanently, logged, or transmitted off your device.

## 2. Pro License Verification & Device Limit
- If you purchase or restore **CallMusicGuard Pro** via Google Play Billing, the app sends your Google Play `purchaseToken`, a SHA-256 hashed Widevine device identifier, and your device model name over HTTPS (encrypted in transit) to our Firebase verification server solely to verify purchase validity and enforce the 10-device binding limit.
- Device bindings cannot be removed or transferred by users.

## 3. No Ads & No Third-Party Tracking
- CallMusicGuard contains **no advertisements**, **no analytics SDKs**, and **no third-party tracking**.

## 4. Contact
If you have any questions about this Privacy Policy, please contact the developer via GitHub:  
https://github.com/dx9901mk5/CallMusicGuard/issues
