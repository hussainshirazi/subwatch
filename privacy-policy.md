# Pockitry privacy policy

Last updated: November 26, 2026

Pockitry is made by Hussain Shirazi ("we"). Contact: hussainshirazi100@gmail.com.

## The short version
Pockitry keeps your subscriptions, bills, expenses and settings on your phone. We have no servers and no accounts of our own, and we never receive your data. If you turn on the optional sync between your phones, an encrypted copy goes to your own Google Drive, which we cannot see. The app has no analytics or crash-reporting tools of its own. It shows an ad only if you choose to watch one, to export a report without Pro (see "Ads").

## What stays on your phone
Everything you enter or the app works out: subscriptions, bills, prices, dates, reminders, expenses, accounts and their balances, notes, and your settings. It is stored in the app's private storage on your phone. Uninstalling the app deletes it (what sync put in your Google Drive stays until you delete it, see below).

- **Screenshots, photos and shared text** you use to fill in a form are read by Google's ML Kit text recognition, which runs on your phone. The image or text is not uploaded, and the app does not keep it (unless you attach it, below). ML Kit's usage logging is switched off in the app.
- **Attachments**: a receipt, bill or screenshot you attach to a subscription or purchase is copied, shrunk, into the app's private storage on your phone (up to 5 for each). It leaves the phone only inside your encrypted backups and, if you turn sync on, encrypted to your own Google Drive. It is deleted with the item.
- **Photos you take in the app** ("Take photo") are saved to your phone's gallery (Pictures/Pockitry), so your gallery app, and its cloud backup if you turned that on, can see them.
- **Bank statements** (PDF or CSV) you open are read on your phone to find repeating payments. The file is not uploaded or kept. If you choose, the payments to subscriptions you track are saved in the app as their payment history; nothing else from the statement is. A PDF password you type is used once to open the file and is never saved.
- **Payment history**: payments you record (from a statement, a shared receipt, or by answering "Was it charged?" after a renewal) are stored in the app with the rest of your data.
- **Home screen widgets**, if you add them, show names, prices, spending and account balances on your home screen, where anyone holding your phone can see them. "Hide amounts" hides the figures there too.
- **Reminders** are shown as notifications. On a locked screen they hide the subscription's name. A reminder you set to ring an alarm shows the name and price on a full screen, also over the lock screen.

## What the app downloads
Only when something you track is in a currency other than your main one, and you haven't typed your own rate for it, the app downloads public exchange-rate data from the free fawazahmed0/exchange-api feed, served by jsDelivr and, as a fallback, Cloudflare (at most about twice a day). If everything is in one currency, the app never connects to it. The request is the same for every user and contains nothing about you or your subscriptions. Like any website, the server sees your phone's IP address; jsDelivr and Cloudflare handle that under their own privacy policies. You can switch this off at any time ("Live exchange rates" in Settings); the app works fully offline.

## Sync between phones (optional, part of Pro)
Sync is off until you turn it on. Then:

- **What is sent**: the data you keep in the app (including attachments and your own pictures, not app settings such as the app lock) is encrypted on your phone with your backup passphrase (AES-GCM, with a key derived from it) and stored in a hidden folder that belongs to Pockitry in **your own Google Drive**. Your other phones read it from there.
- **Who can read it**: only someone with your passphrase. We never receive it, and Google cannot read its contents. Google sees the encrypted files, their sizes and times, your Google account and your phone's IP address, under Google's privacy policy.
- **Google access**: Google asks you once to let Pockitry use that folder (the "drive.appdata" permission, through Google Play services). Pockitry cannot see your other files in Drive, and it does not receive your name, email address or password.
- **Google user data**: Pockitry uses information received from Google APIs only to sync your data between your phones, in line with the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.
- **Stopping and deleting**: "Turn off on this phone" stops sync. "Delete sync data from Google Drive" removes the files (turn sync off on your other phones first). You can also remove Pockitry's access and its hidden data in your Google account or Google Drive settings.

## Ads (only if you ask for one)
Without Pro, you can watch an ad to export a report once. Nothing about ads starts until you tap "Watch ad". Then Google's consent form and Google's AdMob (the Google Mobile Ads SDK) run. Google receives information such as your phone's IP address (which can show your approximate location), device identifiers such as the app set ID, how you interact with the ad, and diagnostic information, and uses it to show and measure the ad and to prevent fraud, under [Google's privacy policy](https://policies.google.com/privacy) and [how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites). Pockitry turns off ad personalisation, the Android advertising ID, coarse location collection and the ad library's crash reports, and gives Google nothing you keep in the app. In the European Economic Area, the UK and Switzerland, Google's form asks for your consent first; you can change your answer in Settings > Ad privacy choices.

## Purchases
Pockitry Pro is bought through Google Play, as a monthly or yearly subscription or as a one-time purchase. Google handles the payment under Google's privacy policy. We receive the order details Google Play gives developers, such as the order number, date, product, price and your country or region, never your payment details. The app checks with Google Play on your phone whether Pro was bought or the subscription is running. A tip to the developer is paid the same way, and we receive the same order details for it.

## Your rights (EU, UK and elsewhere)
For the EU and UK General Data Protection Regulation, Hussain Shirazi is the controller of the little personal data we handle. We are based in Pakistan.

- **What we handle**: only the Google Play order details of a Pro purchase or a tip, and any email you send us. We never receive anything you keep in the app, synced or not.
- **Why**: to provide Pro, including subscriptions, take tips and handle refunds (performing our contract with you), to keep the sales records tax and accounting laws require (a legal obligation), and to answer you (your request).
- **How long**: order details for as long as those laws require, then they are deleted; emails until your question is settled.
- **Where**: the order details stay in Google Play, which we use from outside the EU and UK; Google protects such transfers under its own agreements.
- **Your rights**: you can ask for a copy of what we hold about you, and to correct or delete it, restrict or object to its use, or receive it in a portable form. Write to hussainshirazi100@gmail.com. If you are unhappy with our answer, you can complain to your data protection authority (in the UK, the Information Commissioner's Office).
- **Ads**: if you ask for one, Google handles the information described under "Ads", on the basis of your consent where the law asks for it.
- We do not sell personal information or share it for personalised advertising, and we do not profile you or make automated decisions about you.
- **What's on your phone** is yours alone: delete it by uninstalling the app or clearing its storage, and copy it with Backup. What sync keeps in your Google Drive is yours too: delete it as described above.

## Ratings
Once, after you have used the app for a while, it may show Google Play's rating window; "Rate Pockitry" in Settings opens the app's Play Store page. Ratings and reviews go to Google Play under Google's privacy policy. The app is not told whether or how you rated it, and sends nothing itself.

## Backups
- **Backup files** you create are encrypted (AES-GCM, with a key derived from your passphrase) and saved only where you choose. We cannot open them or recover a forgotten passphrase.
- **Automatic backup**, if you turn it on, stores its passphrase sealed by a key in your phone's Android Keystore, which never leaves the phone.
- **Android's own backups**: Pockitry's data is excluded from Google's cloud backup. Moving it to a new phone with a direct device-to-device transfer is allowed.

## Permissions
- **Internet and network state**: the exchange-rate download, sync with your Google Drive if you turn it on, and an ad if you ask for one (see above).
- **Notifications**: renewal reminders.
- **Full-screen alarms and exact alarms**: only for reminders you set to ring. Android may ask you to allow each in its settings.
- **Keep awake and foreground service**: declared by Google's ad library.
- **Run at startup**: to set reminders again after a restart.
- **Storage**: Android 8 and 9 only, to save photos you take to the gallery.
- **Google Play billing**: to buy Pockitry Pro.
- **Fingerprint or face**: only if you turn on the optional app lock and choose it. Android does the checking and tells Pockitry only yes or no; Pockitry never receives a fingerprint or a face. The PIN itself is kept on your phone only as a salted hash.

The app does not use the camera permission. "Take photo" opens your phone's camera app.

## Children
Pockitry is not directed at children under 13.

## Terms of use
Using Pockitry and buying Pro are covered by the [terms of use](terms).

## Changes
If this policy changes, the new version will be published at this address with a new date.

## Contact
hussainshirazi100@gmail.com
