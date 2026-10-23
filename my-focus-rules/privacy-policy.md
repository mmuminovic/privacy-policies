# Privacy Policy — My Focus Rules

_Last updated: 23 October 2026 · Applies to the Android app "My Focus Rules" (`com.myfocusrules.app`)._

My Focus Rules helps you decide when apps may reach you: it removes notifications according to rules you create, can turn on
Android's Do Not Disturb on a schedule and, with Premium, shows on a home-screen widget what was held back. It is built to work
**entirely on your phone**.

## 1. Summary

- No account, no cloud sync, no ads, no analytics. The only network services are the Premium purchase check (section 7) and optional
  crash reports (section 8).
- Everything you configure (rules, profiles, history, settings) is stored only on your device.
- Notification **content is never read into storage, logged or sent anywhere**.
- We do not sell or share personal data for advertising.

## 2. Who is responsible

The app is published by **Muhamed Muminovic**, who is the controller of the limited data described in sections 7 and 8.
Contact: **muminovic.muhamed01@gmail.com**.

## 3. Notification access

Android requires you to grant *Notification access* (a special permission) before an app can remove notifications. With this access
Android delivers every posted notification to the app, **including its text**. My Focus Rules only uses:

- the package name of the app that posted it (e.g. `com.Slack`),
- the notification category and flags (to protect calls, alarms, navigation, ongoing and system notifications),
- the current time on your phone.

It does not read, store, display or transmit titles, message text, images, senders or any other content.

## 4. Do Not Disturb access

If you create a Do Not Disturb profile (for example *Sleep Mode*), Android asks you for *Do Not Disturb access*. The app uses it only to
create, switch on/off and delete **its own** Do Not Disturb schedule with the exceptions you chose (calls, messages, alarms). It never
turns off a Do Not Disturb mode it did not turn on.

## 5. Other Android permissions

| Permission | Why |
| --- | --- |
| See launchable apps (a `<queries>` entry for launcher apps — not `QUERY_ALL_PACKAGES`) | Show the app picker, and app names and icons in history and the widget |
| Alarms & reminders (`SCHEDULE_EXACT_ALARM`) | Switch rules and profiles exactly on time |
| Run at startup (`RECEIVE_BOOT_COMPLETED`) | Restore your rules after a restart |
| Internet | Premium purchase check and optional crash reports only |

## 6. Data stored on your device

| Data | Purpose | Retention |
| --- | --- | --- |
| Rules (name, target app package names, days, times, action) | Apply your rules | Until you delete them or reset |
| Focus profiles (schedule, DND exceptions) | Switch Do Not Disturb | Until you delete them or reset |
| Filtering history (app package name, rule that removed it, time — **no content**) | Show what was removed | At most 30 days / 1,000 entries |
| Settings (pause, onboarding, crash-report choice, last sync/recovery times, count of notifications removed today) | Operate the app | Until reset |
| Whether Premium is active (a single yes/no copy of the purchase status) | Let the widget unlock itself while the app is closed | Until you uninstall the app |
| List of launchable apps, app names and icons (read from Android when needed, kept in memory) | App picker, history, widget | Not stored |

Android's backup may include app data according to your device settings. *Settings → Reset all data* deletes the rules, profiles,
history and settings from the device; uninstalling the app removes everything.

## 7. Premium purchase (RevenueCat)

The free plan includes one rule. *Premium* (unlimited rules and the home-screen widget) is a one-time in-app purchase made through
Google Play. To check whether Premium is unlocked, the app uses RevenueCat (RevenueCat, Inc., USA) as its purchase provider.

- Sent to RevenueCat: a random, anonymous app user ID created on your phone, the Google Play purchase record (product, purchase token,
  price, currency, time), app version, Android version and device locale. RevenueCat also sees your IP address when the app connects.
- Never sent: your rules, profiles, history, the apps on your phone, notification content, your name or e-mail.
- Payment details are handled by Google Play; neither we nor RevenueCat receive your card or Google account details.
- RevenueCat's privacy policy: https://www.revenuecat.com/privacy

## 8. Crash reports (optional)

Builds may include crash reporting through Sentry (Functional Software, Inc., USA). It is used only to find and fix bugs.

- Sent only when an error occurs and only if you have not turned off *Settings → Data → Send crash reports*.
- Contains: error type and stack trace, app version, device model and Android version.
- Never contains: notification content, names of other apps on your phone (they are replaced with `[package]`), your rules, or
  identifiers of you as a person. IP addresses are not stored as user data, and no screenshots or performance traces are sent.

## 9. Home-screen widget (Premium)

The widget shows how many notifications were removed today, from which apps (with their icons) and whether a focus rule or profile is
active. It reads this from the app's own storage on your phone and sends nothing anywhere. Keep in mind that a widget is visible to
anyone who can see your home screen; remove it if you do not want this information shown there.

## 10. Legal basis (EEA / UK users)

- Premium purchase check: performance of the contract when you buy or restore Premium.
- Crash reports: our legitimate interest in keeping the app working; you can object at any time by turning them off in Settings.
- Everything else is processed only on your device and is not collected by us.

## 11. Sharing and transfers

We do not sell personal data. Data leaves your phone only to RevenueCat (section 7) and, if enabled, Sentry (section 8). Both act as
our service providers, use encrypted connections (HTTPS) and may process data in the United States under their own safeguards for
international transfers (such as the EU Standard Contractual Clauses).

## 12. Your rights and choices

- Revoke Notification access or Do Not Disturb access at any time in Android Settings (rules stop working; the app warns you).
- Pause protection, delete rules, profiles and history, or reset all data in the app.
- Turn off crash reports in Settings.
- Depending on where you live, you may have the right to access, correct or delete data about you, object to processing and complain
  to your data protection authority. To request deletion of a purchase record or crash reports, e-mail us at the address in section 2
  and include your Google Play order number (from the purchase receipt) so we can find the matching RevenueCat record.

## 13. Children

The app is not directed at children under 13 and does not knowingly collect their data.

## 14. Changes

We will update this page when the app's data practices change and show the date above.
