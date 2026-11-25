# Monetis privacy policy

Last updated: November 25, 2026

Monetis is made by Hussain Shirazi ("we"). Contact: hussainshirazi100@gmail.com.

## The short version
Monetis keeps your subscriptions, bills, expenses and settings on your phone. We have no servers and no accounts, and we never receive your data. The app shows no ads and contains no analytics or crash-reporting tools.

## What stays on your phone
Everything you enter or the app works out: subscriptions, bills, prices, dates, reminders, expenses, notes, and your settings. It is stored in the app's private storage on your phone. Uninstalling the app deletes it.

- **Screenshots, photos and shared text** you use to fill in a form are read by Google's ML Kit text recognition, which runs on your phone. The image or text is not uploaded, and the app does not keep it (unless you attach it, below). ML Kit's usage logging is switched off in the app.
- **Attachments**: a receipt, bill or screenshot you attach to a subscription or purchase is copied, shrunk, into the app's private storage on your phone (up to 5 for each). It is never uploaded. It is deleted with the item, and it is part of the encrypted backups you make yourself.
- **Photos you take in the app** ("Take photo") are saved to your phone's gallery (Pictures/Monetis), so your gallery app, and its cloud backup if you turned that on, can see them.
- **Bank statements** (PDF or CSV) you open are read on your phone to find repeating payments. The file is not uploaded or kept. If you choose, the payments to subscriptions you track are saved in the app as their payment history; nothing else from the statement is. A PDF password you type is used once to open the file and is never saved.
- **Payment history**: payments you record (from a statement, a shared receipt, or by answering "Was it charged?" after a renewal) are stored in the app with the rest of your data.
- **The home screen widget**, if you add it, shows subscription names and prices on your home screen, where anyone holding your phone can see them.
- **Reminders** are shown as notifications. On a locked screen they hide the subscription's name.

## What the app downloads
Only when something you track is in a currency other than your main one, and you haven't typed your own rate for it, the app downloads public exchange-rate data from the free fawazahmed0/exchange-api feed, served by jsDelivr and, as a fallback, Cloudflare (at most about twice a day). If everything is in one currency, the app never connects to it. The request is the same for every user and contains nothing about you or your subscriptions. Like any website, the server sees your phone's IP address; jsDelivr and Cloudflare handle that under their own privacy policies. You can switch this off at any time ("Live exchange rates" in Settings); the app works fully offline.

## Purchases
Monetis Pro is bought through Google Play. Google handles the payment under Google's privacy policy. We receive the order details Google Play gives developers, such as the order number, date, product, price and your country or region, never your payment details. The app checks with Google Play on your phone whether Pro was bought.

## Your rights (EU, UK and elsewhere)
For the EU and UK General Data Protection Regulation, Hussain Shirazi is the controller of the little personal data we handle. We are based in Pakistan.

- **What we handle**: only the Google Play order details of a Pro purchase, and any email you send us. We never receive anything you keep in the app.
- **Why**: to provide Pro and handle refunds (performing our contract with you), to keep the sales records tax and accounting laws require (a legal obligation), and to answer you (your request).
- **How long**: order details for as long as those laws require, then they are deleted; emails until your question is settled.
- **Where**: the order details stay in Google Play, which we use from outside the EU and UK; Google protects such transfers under its own agreements.
- **Your rights**: you can ask for a copy of what we hold about you, and to correct or delete it, restrict or object to its use, or receive it in a portable form. Write to hussainshirazi100@gmail.com. If you are unhappy with our answer, you can complain to your data protection authority (in the UK, the Information Commissioner's Office).
- We do not sell or share personal information, show ads, profile anyone or make automated decisions about you.
- **What's on your phone** is yours alone: delete it by uninstalling the app or clearing its storage, and copy it with Backup.

## Ratings
Once, after you have used the app for a while, it may show Google Play's rating window; "Rate Monetis" in Settings opens the app's Play Store page. Ratings and reviews go to Google Play under Google's privacy policy. The app is not told whether or how you rated it, and sends nothing itself.

## Backups
- **Backup files** you create are encrypted (AES-GCM, with a key derived from your passphrase) and saved only where you choose. We cannot open them or recover a forgotten passphrase.
- **Automatic backup**, if you turn it on, stores its passphrase sealed by a key in your phone's Android Keystore, which never leaves the phone.
- **Android's own backups**: Monetis's data is excluded from Google's cloud backup. Moving it to a new phone with a direct device-to-device transfer is allowed.

## Permissions
- **Internet**: the exchange-rate download (see above).
- **Notifications**: renewal reminders.
- **Run at startup**: to set reminders again after a restart.
- **Storage**: Android 8 and 9 only, to save photos you take to the gallery.
- **Google Play billing**: to buy Monetis Pro.
- **Fingerprint or face**: only if you turn on the optional app lock and choose it. Android does the checking and tells Monetis only yes or no; Monetis never receives a fingerprint or a face. The PIN itself is kept on your phone only as a salted hash.

The app does not use the camera permission. "Take photo" opens your phone's camera app.

## Children
Monetis is not directed at children under 13.

## Terms of use
Using Monetis and buying Pro are covered by the [terms of use](terms).

## Changes
If this policy changes, the new version will be published at this address with a new date.

## Contact
hussainshirazi100@gmail.com
