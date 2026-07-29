#Privacy Policy

Last updated: July 29, 2026

Mood Mirror is designed to keep your personal mood and journal content private. This Privacy Policy explains what information is stored on your device, what you may choose to synchronize, what limited product metrics we process, and how you can manage your data.

## Who we are

Mood Mirror is a private mood journaling and reflection app. If you have questions about this Privacy Policy, contact us at mood.mirror.bot@gmail.com.

## Data stored on your device

Mood Mirror stores app data locally on your device. This may include:

- Mood check-ins, dates, scores, tags, notes, and context answers.
- Journal pages and their titles.
- App settings, such as theme, reminder settings, progress preferences, achievements, account and Cloud Save state, and cached subscription status.
- A limited queue of anonymous product events waiting to be aggregated, as described below.

Your mood entries, notes, tags, context answers, and Journal content remain on your device unless you sign in and explicitly enable Cloud Save. Your device operating system may also include app data in device backups depending on your personal backup settings. Those backups are controlled by your device platform, not by Mood Mirror.

## Accounts and Cloud Save

You can use the free local features without an account. A Mood Mirror account is required to purchase or restore Mood Mirror Space and to use Cloud Save.

Authentication and Cloud Save are provided through Supabase. When you create or use an account, Supabase processes the account identifier and authentication information needed to maintain your session. If you enable Cloud Save, your mood archive and Journal content are synchronized to the cloud copy attached to your Mood Mirror account. Cloud Save remains off until you explicitly enable it, and you can turn it off later in Settings.

Mood Mirror does not sell your account or Cloud Save data or send your mood entries, notes, tags, context answers, or Journal content to analytics, advertising, or payment providers.

## Anonymous product analytics

Mood Mirror processes a small set of first-party product metrics to understand whether core features work and which product flows are useful. These metrics are designed to be anonymous and aggregate-only.

The metrics may include:

- App version, platform, event day, and broad app-age range.
- Broad duration and count ranges rather than exact values.
- Allowlisted product actions and outcomes, such as completing onboarding or a check-in, opening or closing the paywall, selecting a plan, completing or cancelling a purchase, using Journal, changing a setting, or completing a backup.
- Coarse states needed to interpret an outcome, such as signed in or signed out, Cloud Save enabled or disabled, or trial shown or not shown.
- A locally calculated summary of whether Journal was used within seven days after Space was activated.

Mood Mirror does not include your mood score, tags, notes, context answers, Journal titles or text, search text, selected dates, email address, Mood Mirror account ID, RevenueCat user ID, receipts, purchase tokens, advertising ID, device ID, contact information, or precise location in product analytics.

Product events are placed in a bounded queue on your device when they cannot be sent immediately. The queue keeps no more than 500 items, removes items older than 30 days, and is cleared when you delete local app data. After a batch is accepted, its local items are deleted.

Analytics batches are sent to a dedicated Supabase endpoint without your Mood Mirror login session. Each batch uses a random one-time delivery token only to prevent duplicate counting. The server immediately adds accepted values to daily aggregate totals; it does not store a raw event history or a user-level analytics profile. One-time delivery tokens are removed after 35 days, and daily aggregate totals are retained for up to 24 months.

Supabase acts as our infrastructure provider and may process ordinary network information, such as an IP address, in operational logs under its own policies. Mood Mirror does not copy an IP address into its analytics tables or use it to build an analytics profile. We do not sell analytics data or provide it to third parties for advertising or their own purposes.

## Purchases and subscriptions

Mood Mirror Space subscriptions are processed by Apple App Store or Google Play and managed through RevenueCat.

When you view plans, purchase, restore, or check a subscription, Apple, Google, and RevenueCat may process purchase and technical information needed to provide and validate access. This may include an anonymous app user ID while you are signed out, your Mood Mirror account-linked RevenueCat user ID after sign-in, device or operating system information, Apple receipt data, and Google purchase tokens. Mood Mirror does not send mood entries, notes, tags, context answers, or Journal content to RevenueCat, Apple, or Google.

For more information, see:

- RevenueCat Privacy Policy: https://www.revenuecat.com/privacy/
- Apple Privacy Policy: https://www.apple.com/privacy/
- Google Privacy Policy: https://policies.google.com/privacy
- Supabase Privacy Policy: https://supabase.com/privacy

## Notifications

If you enable daily reminders, Mood Mirror asks your device for notification permission and schedules reminders through the device notification system. Reminder settings are stored on your device. Notification content does not include your private notes, Journal pages, or mood entries.

You can turn reminders off in the app settings or in your device notification settings.

## Diagnostics and crash information

Mood Mirror does not include a third-party crash-reporting SDK. The anonymous product analytics described above is first-party, limited to allowlisted product actions, and does not include crash logs or private content. Apple, Google, or your device operating system may collect diagnostic or crash information if you have enabled those platform features. Any such information is handled under the relevant platform privacy policy.

## Data deletion

You can delete local app data from inside the app by using Settings > Delete local data. This deletes locally stored mood entries, tags, notes, context answers, Journal pages, settings, achievements, the pending analytics queue, analytics state, and related app data from the app database on that device. It does not automatically delete a previously synchronized cloud copy or aggregate metrics that no longer identify an event or user.

If you use Cloud Save, Settings provides a separate action to delete the cloud backup. Deleting your Mood Mirror account deletes the account and its cloud backup and also clears local app data on that device.

You can also remove local app data by uninstalling the app, subject to your device platform's backup and restore behavior.

Deleting local data, cloud data, or the Mood Mirror account does not cancel a subscription or delete purchase records held by Apple, Google, or RevenueCat. You can manage or cancel subscriptions through your App Store or Google Play account settings.

## Children

Mood Mirror is not directed to children under 13. If you believe a child has provided personal information through the app, contact us at mood.mirror.bot@gmail.com.

## Security

Protecting access to your device and Mood Mirror account helps protect your app data. We recommend using your device passcode, biometric lock, and operating system security updates.

No method of storage or transmission is completely secure. If we learn of a security issue that affects Mood Mirror users, we will take reasonable steps to address it.

## Changes to this policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the "Last updated" date and, where appropriate, provide additional notice.

## Contact

mood.mirror.bot@gmail.com
