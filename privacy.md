---
title: Privacy Policy
permalink: /privacy/
---

# Globi Privacy Policy

**Effective date: October 19, 2026**

Globi ("the app") is a geography learning game. This policy explains what information the app collects, why, who receives it, how long it's kept, and the choices you have.

**The short version:**

- You can play the whole game without an account, and your progress stays on your device.
- By default, the app sends **anonymous usage events** (for example, "a lesson was completed") to our own database so we can see how the app is used and improve it. These events aren't tied to your name, email or account. You can turn this off in **Settings → Preferences → Share anonymous usage**.
- If you choose to create an account, we store your email address, the display name and avatar you pick, and your game progress. We use these to back up and sync your progress and to show you on the leaderboard.
- Globi Pro subscriptions are paid through Apple and managed with a service called **RevenueCat**.
- Globi has no ads and no advertising or third-party tracking SDKs, and we don't sell your information.

In this policy, **Settings** means the screen you open by tapping the gear icon on the **Profile** tab.

## Who we are

Globi is developed and run by Eugene Barnes, an independent developer ("we", "us").

Questions, requests, or concerns: **ejbarness@icloud.com**

## What we collect and why

### 1. On your device (no account needed)

The whole game works without signing in. The app saves the following **only on your device**:

- **Your progress:** XP, level, streaks, hearts, completed lessons, quiz statistics (by region, topic and country), recent lesson history, the last 30 days of daily XP, your Review Mistakes deck, badges, streak freezes, reward chests, and your best Survival run.
- **Your settings:** the display name and avatar you chose during setup, your language, sound, haptics and reminder settings, your reminder time, and your preferred regions.
- **Small extras:** which cosmetics Globi is wearing, and when the app last asked you for an App Store rating.

Apart from the few details included in anonymous usage events (section 2), none of this leaves your device unless you create an account (section 3). It's erased when you use **Settings → Data → Reset Progress** or delete the app.

The app also stores a few technical items on your device:

- the random ID used for usage analytics, plus any analytics events not yet sent (section 2);
- an anonymous ID created by RevenueCat (section 5);
- if you sign in, a sign-in session so you stay signed in.

When you first set up the app, it reads your device's language setting (on the device) to choose English, Spanish or French.

### 2. Anonymous usage analytics (on by default)

**What it is.** The app records a small set of usage events and sends them to our own database, which Supabase hosts. We use them to see where people get stuck, whether they come back, and how the Globi Pro screen performs. We built this ourselves. It is **not** a third-party analytics or advertising SDK, and we never share the events with anyone else.

**It's on by default**, starting the first time you open the app. You can turn it off at any time (see "Turning it off" below).

**Each event contains these fields and nothing else:**

| Field | What it is |
|---|---|
| Random install ID | A random ID the app creates on your device the first time analytics runs. It is not your Apple advertising ID (IDFA), not Apple's per-vendor device ID (IDFV), and not your account ID. |
| Event name | One of the events listed below. |
| Event details | A few short details about the event (listed below). |
| App version | For example, 1.2.0. |
| Platform | iOS or Android. |
| Time | When the event happened, according to your device's clock. Our database also records when it received the event. |

**The events, and the details sent with each:**

| Event | When it's recorded | Details sent |
|---|---|---|
| App opened | The app starts or comes back to the foreground | None |
| Setup step | You move through first-time setup | Which step; how many regions you picked |
| Setup completed | You finish first-time setup | Whether you skipped picking regions; whether you entered a name (yes or no; **the name itself is not sent**); the app language (English, Spanish or French) |
| Lesson started | A quiz screen opens | The game mode (such as a lesson, Daily Challenge, Review, Survival or Map Mode); the region and topic; whether you resumed a quiz |
| Lesson, Daily Challenge or Survival completed | You finish a quiz | Your score; the number of questions; whether it was perfect; whether you levelled up; your total number of lessons completed |
| Pro screen viewed or closed | You open or close the Globi Pro screen | Which part of the app sent you there (such as Settings, the shop, or a locked topic); on open, whether you already have Pro |
| Purchase started, succeeded or failed | You tap subscribe, a purchase or free trial starts, or a purchase fails (cancelling isn't recorded) | The plan (such as monthly); whether a free trial was offered; which part of the app sent you there; for failures, whether the payment is still pending |
| Share tapped | You tap Share on a results screen | Which results screen (quiz or Survival) |
| Rating prompt shown | Apple's "rate this app" prompt appears | None |
| Reminder opened | You open the app by tapping a reminder notification | Which kind of reminder (streak, or "we miss you") |

**What the events don't contain:** your account ID, email address, display name, or any text you type. They also don't include your advertising ID, your location, or your contacts, photos or other content. The table that stores the events has no column for your account or your IP address.

**How they're sent.** Events wait on your device, which holds up to the 200 most recent. The app sends them in small batches: when it starts, every 30 seconds or so while you're using it, and when you leave it. Like any internet request, sending them shows your device's IP address to our hosting provider. If you're signed in, the request also carries your normal sign-in session. Neither of these is saved in the analytics table (see "Connection information" below).

**Why we collect them.** We use the events to fix confusing setup steps, see which lessons people finish, and decide which features to build. We don't use them to profile you, to target ads, or to make decisions about you.

**Turning it off.** Go to **Settings → Preferences → Share anonymous usage** and switch it off. The app stops recording and sending events, and deletes any events still waiting on your device. Events already sent stay in our database until they're deleted automatically (see "How long we keep information"). **Reset Progress** also gives you a new random install ID, so a fresh start can't be linked to the old one.

### 3. If you create an account (optional)

You don't need an account to play. An account lets you back up your progress, sync it between devices, and appear on the global leaderboard. You can sign up with an email address and password, **Sign in with Apple**, or **Sign in with Google**.

**What we store for your account:**

- **Email address.** We use it to sign you in. If email confirmation is switched on, we also use it to send you a confirmation link when you sign up. Other players never see it, and we don't use it for marketing.
- **Password** (email sign-up only). It goes to our sign-in provider, Supabase, which stores it in hashed form. It isn't stored in Globi's own database tables or saved on your device.
- **Account ID.** Supabase gives your account a random ID.
- **Sign in with Apple.** Apple gives us your email address. If you choose **Hide My Email**, it gives us a private relay address that forwards to you instead. Apple may also offer to share your name, but the app doesn't send or store it.
- **Sign in with Google.** You sign in on Google's own page. Google shares your email address, your name and a link to your profile photo with Supabase, which stores them with your sign-in record. Globi doesn't display or use your Google name or photo. Your leaderboard name is always the one you choose in the app.
- **Your synced progress and settings.** These are the same progress and settings listed in section 1, stored so you can restore them on your other devices. Other players can't see them.
- **Your leaderboard profile.** See section 4.

Supabase also keeps standard records about your account, such as when you created it and when you last signed in.

### 4. The leaderboard

Every account has a leaderboard profile. It contains your **display name, avatar, level, all-time XP, this week's XP and current streak**, along with your random account ID and the time the profile was last updated.

- **Any signed-in Globi player can read these profiles.** The leaderboard screen shows the display names, avatars, levels and XP of the top 50 players. Players who aren't signed in can't see the leaderboard.
- Your email address is never part of your profile.
- You choose your display name, and it doesn't need to be your real name. Please don't use your full real name. Names can be up to 20 characters, and the app checks them against a basic list of offensive words.
- There's currently no setting to hide your account from the leaderboard. If you don't want to appear on it, you can play without an account, use a name that doesn't identify you, or delete your account.

### 5. Purchases (Globi Pro)

Globi Pro is an optional subscription sold through Apple's App Store.

- **Apple** handles the payment. We never see your payment card, your billing address or your Apple Account details.
- **RevenueCat** is a service we use to check whether you have an active subscription and to handle purchases, restores and free trials.
  - When the app starts, RevenueCat's software creates an **anonymous ID** for this install and checks whether it has Pro. This happens for every player, even if you never buy anything.
  - If you buy or restore a subscription, RevenueCat receives your subscription details from Apple, such as the plan, purchase and renewal dates, price and currency, free-trial status, and transaction IDs.
  - Like most such services, RevenueCat also receives basic technical information, such as your device platform, operating system and app version, and your App Store country.
- **If you're signed in,** the app gives RevenueCat your random Globi **account ID** (not your email or name) so your subscription follows you to your other devices. This happens whenever you're signed in, whether or not you've bought anything. When you sign out, the app switches RevenueCat back to an anonymous ID.

We use this information only to give you the Pro features you paid for and to understand subscription numbers, such as how many people subscribe or cancel.

### 6. Reminder notifications

If you allow notifications, the app schedules streak reminders **on your device**. By default they arrive at 7 PM, are scheduled up to a week ahead, and are followed by a couple of "we miss you" reminders if you haven't played for a while. Your device's operating system creates and delivers them. The app doesn't use a push-notification server and doesn't send a notification token anywhere. If you open the app from a reminder, that's recorded as an analytics event, unless you've turned analytics off.

### 7. Other things the app does

- **Sharing.** When you tap Share, your device's share sheet opens with a short message and an App Store link. You choose whether to send it and to whom, and we don't see who receives it.
- **Ratings.** The "rate this app" prompt comes from Apple, and any rating or review you leave goes to Apple.
- **Links.** This policy, the Terms of Use and subscription management open in a browser, on websites run by GitHub and Apple. Those companies have their own privacy policies.

### Connection information

Whenever the app talks to Supabase or RevenueCat, those services receive standard connection information. This includes your IP address and, if you're signed in, your sign-in session. They may keep this information in their own logs for security and operations. It travels over encrypted (HTTPS) connections.

## What we do NOT do

- **No ads.** The app has no ad networks or advertising SDKs.
- **No third-party tracking or analytics SDKs.** Our usage analytics go only to our own database (section 2). We don't track you across other companies' apps or websites, and we don't use your advertising ID. The app never asks for App Tracking Transparency permission.
- **No selling.** We don't sell, rent or trade your information, and we don't share it with data brokers or for advertising.
- **No marketing emails.**
- **No location, contacts, photos, camera, microphone or health data.** The app doesn't access any of these.
- **No chat or messaging** between players. The only thing other players can see is your leaderboard profile (section 4).

## Service providers

We share information only with the companies below. Each one receives information only to run part of Globi for us, as described in this policy.

| Provider | What it does for Globi | What it handles |
|---|---|---|
| **Supabase** | Hosts our database, runs account sign-in, and stores analytics events | Account and leaderboard data, synced progress, anonymous analytics events, connection information |
| **RevenueCat** | Manages Globi Pro subscriptions | Anonymous purchase ID, your account ID if you're signed in, subscription details from Apple, basic device information |
| **Apple** | App Store distribution and payments, Sign in with Apple, notifications, the rating prompt | Covered by Apple's privacy policy |
| **Google** | Sign-in, only if you choose Sign in with Google | Covered by Google's privacy policy |
| **GitHub** | Hosts this website (the privacy policy, terms and support pages) | Standard visitor information, such as your IP address, when you view these pages |

Apple may also send us summary statistics about the app. If you've chosen in your device settings to share crash reports with app developers, Apple may send us those too.

We may also disclose information when the law requires it.

## How long we keep information

| Information | How long |
|---|---|
| Data on your device | Until you use Reset Progress or delete the app. Deleting your account does **not** erase progress saved on the device. |
| Anonymous analytics events | Deleted automatically **90 days** after we receive them. If you turn analytics off, events still waiting on your device are deleted right away. |
| Account, leaderboard profile and synced progress | Until you delete your account. We don't currently delete inactive accounts automatically. |
| Subscription records at RevenueCat | Kept by RevenueCat for as long as our RevenueCat account holds them. Deleting your Globi account doesn't remove them, but you can email us to ask for your RevenueCat record to be deleted. |
| Purchase records at Apple | Kept by Apple under Apple's own policies. |

When you delete your account or data, it's removed from our live database right away. If we turn on database backups in the future, deleted data could remain in those encrypted backups for up to 7 days before it's overwritten.

## Your choices and rights

- **Turn off usage analytics:** Settings → Preferences → **Share anonymous usage**.
- **Turn off reminders:** Settings → Preferences → **Daily Reminders**, or your device's Settings → Notifications → Globi.
- **Change your display name or avatar:** Settings → Account → **Edit Profile**.
- **Delete your account:** Settings → Account → **Sync Progress** → **Delete Account**.
  - This immediately and permanently deletes your sign-in record, leaderboard profile, and synced progress and settings from our database. It can't be undone.
  - It does **not** cancel a Globi Pro subscription. Cancel that in your Apple Account's subscription settings, or tap **Manage Subscription** in Settings.
- **Erase what's on your device:** Settings → Data → **Reset Progress**, or delete the app. If you're signed in, Reset Progress also resets the progress saved with your account, but the account itself stays.
- **Ask us:** email **ejbarness@icloud.com** to ask for a copy of the information connected to your account, to correct it, to delete it, or to have your RevenueCat record removed. Analytics events aren't linked to you or your account, so we usually can't tell which ones came from you. They're deleted automatically after 90 days.

Depending on where you live, you may have other rights, such as the right to object to how we use your information or to complain to your local data-protection authority.

### If you're in the EU, UK or Switzerland

The person responsible for your information (the "controller") is Eugene Barnes, contactable at the email address below. We rely on these legal bases:

- **To run your account, sync your progress and provide Globi Pro:** performing our agreement with you.
- **Anonymous usage analytics, security and preventing abuse:** our legitimate interest in keeping the app working and improving it. You can object at any time by turning off **Share anonymous usage**.
- **Keeping records the law requires:** legal obligation.

You can ask us to access, correct, delete, restrict or export your information, or object to how we use it, by emailing us. You can also complain to your local data-protection authority.

## Children

Globi is rated **4+** on the App Store and is meant for players of all ages, including children. It isn't part of the App Store's Kids category.

**The app doesn't ask anyone's age.** We don't know whether a particular player is a child, and the app works the same way for everyone. In practice, that means:

- **Anonymous usage analytics** (section 2) are on by default for every player, including children. A parent can turn them off in **Settings → Preferences → Share anonymous usage**.
- **RevenueCat** creates an anonymous ID for every player when the app starts (section 5). Purchases themselves go through Apple, and parents can control them with Family Sharing's Ask to Buy and Screen Time.
- **Accounts** are optional and are meant for people aged 13 or older, or the minimum age for consent in your country. The app doesn't currently check age. A child who creates an account would give us an email address, and other signed-in players could see their leaderboard profile (section 4).

If you're a parent or guardian and believe your child under 13 has created an account or given us personal information, email **ejbarness@icloud.com** and we'll delete it. You can also delete the account yourself in the app (see "Your choices and rights").

## International transfers

Our database is hosted by Supabase in the United States (Virginia). RevenueCat is also based in the United States. Your information may be stored and processed in the United States and in other countries where these providers or their own providers operate. Those countries may have different data-protection laws from the country where you live.

## Changes to this policy

If we change this policy, we'll update this page and the effective date at the top. If a change is significant, such as collecting a new kind of information, we'll also mention it in the app's release notes.

**What changed on October 19, 2026:** this version describes two features the previous policy left out:

- the anonymous usage analytics added in Globi 1.2;
- the Globi Pro subscription, managed by RevenueCat, added in Globi 1.1.

The previous version, dated July 4, 2026, said the app had no analytics and didn't mention RevenueCat. It was out of date.

## Contact

Questions or requests: **ejbarness@icloud.com**
