# Privacy Policy — My Medusa Stores

_Last updated: 9 November 2026 · Applies to the iOS and Android app "My Medusa Stores" (`com.mymedusastores.app`)._

My Medusa Stores lets merchants run their Medusa stores from a phone: orders, payments, fulfilment, products, customers, sales
figures, new-order alerts and home-screen widgets. **The app has no server of its own.** It talks directly from your phone to your own
Medusa server, using an API key that stays on your phone.

## 1. Summary

- No account with us and no ads. We do not sell personal data or share it for advertising.
- Your store data (orders, customers, products, sales) goes **only between your phone and your own Medusa server**. We never receive it.
- Your API key is kept in your phone's secure storage and is sent only to your own store.
- Data leaves your phone for three other purposes only: checking your subscription (section 6), fetching exchange rates (section 7) and,
  when included in the app version you use, usage analytics (section 8).

## 2. Who is responsible

The app is published by **Muhamed Muminovic**, who is the controller of the limited data described in sections 6 to 8.
Contact: **muminovic.muhamed01@gmail.com**.

**Your customers' data.** Orders and customer records belong to your store, and you (the merchant) decide how they are used. You remain
responsible for them towards your customers, including when you view them in this app. We do not receive this data and do not act on it.

## 3. Connecting a store

You connect a store in one of two ways, and both go directly to the server address you enter:

- **Signing in to Medusa Admin.** Your email and password are sent once to your own Medusa server. The app creates its own secret API key
  there and does not keep the password. The key's name, visible in Medusa Admin, includes your phone's name (for example
  "My Medusa Stores – Ana's iPhone"). The email is kept with the key on your phone, to sign the internal order notes you write.
- **Pasting a secret API key** that you created yourself.

The app uses HTTPS unless you enter an address that starts with `http://`.

The key gives whoever holds it admin access to your store, so it never goes anywhere except your store. You can revoke it at any time in
Medusa Admin under *Settings → Secret API Keys*. The app then stops working with that store until you connect it again.

## 4. Data stored on your device

| Data | Purpose | Retention |
| --- | --- | --- |
| Secret API key and the sign-in email, if you signed in (iOS Keychain / Android Keystore) | Connect to your store, sign internal notes | Until you remove the store (see below) |
| Store details: name, address, currencies and your settings for it | Operate the app | Until you remove the store or uninstall |
| Recently loaded orders, customers, products and figures (the app's own storage) | Open quickly and work offline | Replaced as data refreshes; deleted when you remove the store or uninstall |
| Where the new-order check last stopped (the time and IDs of the newest orders seen) | Tell you only about new orders | Until you turn alerts off, remove the store or uninstall |
| Snapshot of today's sales and open orders | Show the widgets | Until replaced, or until you uninstall |
| Settings: language, theme, App lock, check interval, a random install ID | Operate the app | Until you uninstall |
| Whether your subscription is active (a yes/no copy) | Let alerts and widgets work while the app is closed | Until replaced, or until you uninstall |

**Removing a store** in the app deletes its key and cached data from the phone. If the app created the key, it also tries to revoke it on
your server. On iOS, the system can keep Keychain items after an app is uninstalled, so remove your stores in the app before uninstalling
it, or revoke the key in Medusa Admin.

**Device backups.** iCloud and Android backups may include the app's stored data, including cached customer and order data, according to
your device settings.

**Shared phones.** Anyone who can open the app can see your store data. App lock in Settings protects it with Face ID, Touch ID or your
device passcode. The app only receives the yes/no result of that check, and never your biometric data.

## 5. Device permissions

| Permission | Why | Where the data goes |
| --- | --- | --- |
| Notifications | New-order alerts, and a notice if your store rejects its key | Created on your phone; no push service is used |
| Camera | Take product photos and scan barcodes to find products | Photos you add go to your own store; barcodes are used on your phone only |
| Photos | Choose product images | Only the photos you pick, to your own store |
| Face ID / biometrics | App lock, if you turn it on | Checked by your phone's operating system |
| Background refresh | Check for new orders and update widgets | Requests go only to your own store |

**Alerts and widgets** can show store names, order numbers and amounts on your lock screen or home screen, where anyone who can see your
phone can read them. With App lock on, alerts leave out amounts. You can turn alerts off per store and remove widgets at any time.

## 6. Subscriptions (RevenueCat, Apple, Google)

Connected stores need a Pro subscription, bought through the App Store or Google Play. The demo store is free. The app uses RevenueCat
(RevenueCat, Inc., USA) to check whether your subscription is active.

- Sent to RevenueCat: a random, anonymous app user ID created on your phone, your store purchase record (product, purchase token, price,
  currency, time, trial status), which paywall screen led to the purchase, app and operating system version, and device locale.
  RevenueCat also sees your IP address when the app connects.
- Never sent: your store data, API keys, store address, name or email.
- Payment is handled by Apple or Google. Neither we nor RevenueCat receive your card details.
- Manage or cancel your subscription in your App Store or Google Play account. Removing the app does not cancel it.
- RevenueCat's privacy policy: https://www.revenuecat.com/privacy

## 7. Exchange rates

To show amounts in other currencies, the app downloads a public list of exchange rates from `currency-api.pages.dev`, an independent
service hosted on Cloudflare. The request contains only the date and asks for the same public file for everyone, so no store data or
identifier is sent. Like any website, the service can see your IP address.

## 8. Usage analytics (Google Firebase)

When included in the app version you use, Firebase Analytics (Google LLC, USA) helps us see which features are used and where connecting
fails.

- Sent: screens opened and features used, an analytics ID that Firebase creates for the app install, a scrambled (hashed) store ID, device
  model, operating system version, language and approximate country. Events about connecting a store include its **web address (host name)**,
  so we can see which sites fail to connect.
- Never sent: API keys, passwords, order or customer details, or product data. Full web addresses are reduced to the host name.
- The data is not used for advertising.
- The app currently has no switch to turn analytics off. You can ask us to delete data linked to your install (section 11).
- Google's privacy policy: https://policies.google.com/privacy

## 9. Legal basis (EEA / UK users)

- Subscription check: performance of the contract when you start or restore a subscription.
- Exchange rates and analytics: our legitimate interest in showing correct amounts and in keeping the app working and improving it.
- Everything else is processed only on your phone or between your phone and your own server, and is not collected by us.

## 10. Sharing and transfers

We do not sell personal data. Apart from your own store, data leaves your phone only as described in sections 6 to 8. These providers use
encrypted connections and may process data in the United States or other countries, under their own safeguards for international
transfers (such as the EU Standard Contractual Clauses).

We keep no store data, so we have none to share. RevenueCat keeps subscription records and Google keeps analytics data according to their
own retention policies.

## 11. Your rights and choices

- Remove a store, or revoke its key in Medusa Admin, at any time.
- Turn off alerts, remove widgets, or withdraw camera, photo and notification access in your phone's settings.
- Depending on where you live, you may have the right to access, correct or delete data about you, object to processing and complain to
  your data protection authority.
- To request deletion of a subscription record or analytics data, email the address in section 2. Include your install ID (the *Request
  data deletion* button in *Settings → Privacy and data* fills it in) or your App Store or Google Play order number.

## 12. Children

The app is a tool for merchants. It is not directed at children under 13 and does not knowingly collect their data.

## 13. Changes

We will update this page when the app's data practices change, for example if a future version adds push notifications through a server,
and show the date above.
