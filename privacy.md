# Privacy Policy

Last updated: August 29, 2026

Etchloom is designed to keep your personal mood and Journal content private. This Privacy Policy explains what information is stored on your device, what you may choose to synchronize, what limited product metrics we process, and how you can manage your data.

## Who we are

Etchloom is a private mood journaling and reflection app provided by whilework. If you have questions, support requests, or privacy requests, contact us at mood.mirror.bot@gmail.com.

## Summary

- Your mood archive is stored on your device by default.
- Cloud Save is optional and remains off until you sign in and enable it.
- We do not sell personal or sensitive user data.
- We do not use your mood entries, notes, tags, context answers, or Journal content for advertising.
- Etchloom does not track you across apps or websites owned by other companies.
- Etchloom processes a limited set of first-party, aggregate-only product metrics that exclude private archive content and account identifiers.

## Data stored on your device

Etchloom stores app data locally in its database and settings storage on your device. This may include:

- Mood check-ins, dates, scores, tags, notes, context answers, and created or updated timestamps.
- Journal pages and their titles.
- App settings, such as theme, reminder settings, progress preferences, achievements, account and Cloud Save state, and cached subscription status.
- Local deletion markers used to keep deleted entries from reappearing during synchronization.
- A limited queue of anonymous product events waiting to be aggregated, as described below.

Your mood entries, notes, tags, context answers, and Journal content remain on your device unless you sign in and explicitly enable Cloud Save. Your device operating system may also include app data in device backups depending on your personal backup settings. Those backups are controlled by your device platform, not by Etchloom.

## Accounts, sign-in, and Cloud Save

You can use the free local features without an account. An Etchloom account is required to purchase or restore Etchloom Space and to use Cloud Save.

Authentication and Cloud Save are provided through Supabase. Depending on your platform and availability, sign-in may use Apple or Google. When you create or use an account, the relevant services may process:

- Your Supabase user ID.
- Your email address, name, and other basic profile information made available by the sign-in provider.
- Authentication session data needed to keep you signed in.

On mobile, authentication session data is stored using secure device storage where available. On web builds, session data may be stored in browser or app storage.

Cloud Save is optional and remains off until you explicitly enable it. When enabled, supported content is synchronized to Supabase under the cloud copy attached to your Etchloom account. This may include:

- Your user ID.
- Dates, mood scores, notes, tags, context answers, and mood timestamps.
- Journal pages and titles.
- Backup versions, synchronization timestamps, and deletion markers.

Supabase row-level security rules are intended to allow only the authenticated owner to read, create, update, or delete that account's cloud archive.

Etchloom does not send your mood entries, notes, tags, context answers, or Journal content to analytics, advertising, or payment providers.

## Anonymous product analytics

Etchloom processes a small set of first-party product metrics to understand whether core features work and which product flows are useful. These metrics are designed to be anonymous and aggregate-only.

The metrics may include:

- App version, platform, event day, and broad app-age range.
- Broad duration and count ranges rather than exact values.
- Allowlisted product actions and outcomes, such as completing onboarding or a check-in, opening or closing the paywall, selecting a plan, completing or cancelling a purchase, using Journal, changing a setting, or completing a backup.
- Coarse states needed to interpret an outcome, such as signed in or signed out, Cloud Save enabled or disabled, or trial shown or not shown.
- A locally calculated summary of whether Journal was used within seven days after Space was activated.

Etchloom does not include your mood score, tags, notes, context answers, Journal titles or text, search text, selected dates, email address, Etchloom account ID, RevenueCat user ID, receipts, purchase tokens, advertising ID, device ID, contact information, or precise location in product analytics.

Product events are placed in a bounded queue on your device when they cannot be sent immediately. The queue keeps no more than 500 items, removes items older than 30 days, and is cleared when you delete local app data. After a batch is accepted, its local items are deleted.

Analytics batches are sent to a dedicated Supabase endpoint without your Etchloom login session. Each batch uses a random one-time delivery token only to prevent duplicate counting. The server immediately adds accepted values to daily aggregate totals; it does not store a raw event history or a user-level analytics profile. One-time delivery tokens are removed after 35 days, and daily aggregate totals are retained for up to 24 months.

Supabase acts as our infrastructure provider and may process ordinary network information, such as an IP address, in operational logs under its own policies. Etchloom does not copy an IP address into its analytics tables or use it to build an analytics profile. We do not sell analytics data or provide it to third parties for advertising or their own purposes.

## Purchases and subscriptions

Etchloom Space subscriptions are processed by Apple App Store or Google Play and managed through RevenueCat.

When you view plans, purchase, restore, or check a subscription, Apple, Google, and RevenueCat may process purchase and technical information needed to provide and validate access. This may include:

- An anonymous app user ID while you are signed out.
- Your Etchloom account-linked RevenueCat user ID after sign-in.
- Product, subscription, transaction, receipt, or purchase-token information.
- Store, device, operating system, app version, subscription status, and entitlement information.

Etchloom does not send mood entries, notes, tags, context answers, or Journal content to RevenueCat, Apple, or Google.

For more information, see:

- [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy/)
- [Apple Privacy Policy](https://www.apple.com/privacy/)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Supabase Privacy Policy](https://supabase.com/privacy)

## Reminders and notifications

If you enable daily reminders, Etchloom asks your device for notification permission and schedules reminders through the device notification system. Reminder settings are stored on your device. Reminder content does not include your private notes, Journal pages, or mood entries.

Etchloom does not use push notification tokens for reminder delivery in the current app. You can turn reminders off in the app settings or in your device notification settings.

## Import, export, sharing, and support

If you export your archive, Etchloom creates a CSV file on your device and lets you share it through your device's share sheet. If you import an archive, the app reads the CSV file you choose. These actions are initiated by you.

If you contact support, we process the email address you use, your subject, your message, and any information you choose to include. Do not include private mood or Journal content unless it is necessary for your request.

## Diagnostics and crash information

Etchloom does not include a third-party crash-reporting SDK. The anonymous product analytics described above is first-party, limited to allowlisted product actions, and does not include crash logs or private content. Apple, Google, your device operating system, Supabase, RevenueCat, or other service providers may process technical, network, diagnostic, or crash information as part of their services and platform operations under their own policies.

## How we use information

We use information to:

- Provide app functionality, including mood tracking, insights, reminders, backup, restore, import, and export.
- Authenticate your account and maintain your sign-in session.
- Synchronize and restore your archive when Cloud Save is enabled.
- Check, purchase, restore, and manage Space subscription access.
- Provide customer support.
- Protect the app, prevent fraud or abuse, troubleshoot problems, and comply with legal obligations.

We do not use your personal mood archive for advertising.

## Third-party services

Etchloom uses service providers and platform services to operate the app:

- Supabase for authentication, Cloud Save storage, and aggregate-only product analytics infrastructure.
- Apple for Apple sign-in, App Store distribution and billing, and iOS platform services.
- Google for Google sign-in, Google Play distribution and billing, and Android platform services.
- RevenueCat for subscription and entitlement management.

These services may process data as described above and under their own policies. We may also disclose information if required by law, to protect rights and safety, or in connection with a merger, acquisition, financing, or sale of assets, subject to appropriate notice where required.

## Store privacy disclosures

For Apple App Privacy and Google Play Data safety disclosures, data transmitted off the device depends on the features you choose to use:

- Mood archive and Journal data are transmitted only when you sign in and enable Cloud Save.
- Account identifiers and sign-in data are transmitted when you sign in.
- Purchase and subscription data are transmitted when you view, purchase, restore, or check Space access.
- Support message content is transmitted only when you choose to contact us.
- Limited anonymous product events are transmitted for aggregate-only analytics as described above.
- Data is encrypted in transit using modern transport security where supported by the relevant service.
- Etchloom does not use this data for third-party advertising or cross-app tracking.

## Your choices

You can use Etchloom locally without signing in. You can:

- Turn Cloud Save on or off in Settings.
- Delete local data in Settings.
- Delete cloud data in Settings when signed in.
- Delete your Etchloom account in Settings when signed in.
- Export or import your archive from Settings.
- Turn reminders off in the app or in your device settings.
- Sign out from Settings.
- Manage or cancel subscriptions through your Apple App Store or Google Play account settings.

## Data retention and deletion

Local app data remains on your device until you delete it in the app, uninstall the app, or your operating system removes it. Device backups may retain app data depending on your personal device backup settings.

Cloud archive data remains associated with your signed-in account while Cloud Save is used. You can remove data from inside the app:

- `Settings > Danger zone > Delete local data` deletes the local copy on that device.
- `Settings > Danger zone > Delete cloud data` deletes the cloud copy attached to the signed-in account while keeping the account active.
- `Settings > Danger zone > Delete account` deletes the Etchloom account and its cloud copy and clears local app data on that device.

The synchronization system may retain minimal deletion markers, such as dates and deletion timestamps, to prevent deleted entries from reappearing during later synchronization. Aggregate metrics that do not identify an event or user cannot be connected back to your account.

If you cannot use the in-app controls, see [Delete your Etchloom account](delete-account) or [Delete Etchloom data without deleting your account](mirror-data), or contact mood.mirror.bot@gmail.com. We may need to verify that you control the account before completing a request.

Deleting local data, cloud data, or your account does not automatically cancel an active subscription. Subscription and purchase records controlled by Apple, Google, or RevenueCat may be retained under their own policies. Manage or cancel the subscription through the store where you purchased it.

## Security

We use reasonable technical and organizational measures designed to protect personal and sensitive user data. Cloud communications use encrypted transport where supported, Supabase access is restricted by authentication and row-level security rules, and mobile authentication sessions use secure device storage where available.

No method of storage or transmission is completely secure. Protecting access to your device and Etchloom account helps protect your app data. We recommend using your device passcode, biometric lock, and operating system security updates.

## Children

Etchloom is not directed to children under 13 or to children below the minimum age required by applicable law in their country. If you believe a child has provided personal information through the app, contact us at mood.mirror.bot@gmail.com.

## International processing

Your information may be processed in countries other than the country where you live, including where our service providers operate. Those countries may have different data protection laws.

## Changes to this policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the "Last updated" date and, where appropriate, provide additional notice.

## Contact

mood.mirror.bot@gmail.com
