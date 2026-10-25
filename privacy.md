---
title: Privacy Policy
permalink: /privacy/
---

# Globi Privacy Policy

**Effective date: October 26, 2026**

Globi ("the app") is a geography learning game. This policy explains what information the app collects, why, who receives it, how long it's kept, and the choices you have.

**The short version:**

- You can play the whole game without an account, and your progress stays on your device.
- The app asks for your **birth month and year**. The answer stays on your device and is never sent anywhere. If you're under 13, the app turns off accounts and the leaderboard on that device (see "Children").
- By default, the app sends **anonymous usage events** (for example, "a lesson was completed") to our own database so we can see how the app is used and improve it. These events aren't tied to your name, email or account. You can turn this off in **Settings → Preferences → Share anonymous usage**.
- If you choose to create an account, we store your email address, the display name and avatar you pick, and your game progress. We use these to back up and sync your progress and to show you on the leaderboard.
- Globi Pro subscriptions are paid through Apple and managed with a service called **RevenueCat**. On iPhone, for players 13 and older who leave **Share anonymous usage** on, RevenueCat also checks whether the app was installed from one of our Apple Ads (section 5).
- App updates are delivered by **Expo**, which receives a random install ID and basic technical details each time the app starts (section 8).
- Globi has no ads, no advertising SDKs and no third-party tracking, and we don't sell your information.

In this policy, **Settings** means the screen you open by tapping the gear icon on the **Profile** tab.

## Who we are

Globi is developed and run by Eugene Barnes, an independent developer ("we", "us").

Questions, requests, or concerns: **ejbarness@icloud.com**

## What we collect and why

### 1. On your device (no account needed)

The whole game works without signing in. The app saves the following **only on your device**:

- **Your progress:** XP, level, streaks, hearts, completed lessons, quiz statistics (by region, topic and country), recent lesson history, the last 30 days of daily XP, your Review Mistakes deck, badges, streak freezes, reward chests, your best Survival run, your Flag and Capitals drill scores, your progress in dated challenges (such as GeoWeek), and a quiz you left part-way through.
- **Your settings:** the display name (or, in under-13 mode, the generated nickname) and avatar chosen during setup, your language, sound, haptics and reminder settings, your reminder time, and your preferred regions.
- **Your age answer:** the birth month and year you entered, and the age group worked out from them (under 13, 13 to 17, or 18 and over). See "Children".
- **Small extras:** which cosmetics Globi is wearing, when the app last asked you for an App Store rating, whether the app has already shown you its first Globi Pro offer, and whether you've answered "Where did you hear about Globi?".

Apart from the few details included in anonymous usage events (section 2), none of this leaves your device unless you create an account (section 3). **Your age answer never leaves your device**, even with an account. **Settings → Data → Reset Progress** erases your progress, settings, cosmetics, drill scores and challenge progress. It keeps your age answer and a few small flags, such as whether you've answered "Where did you hear about Globi?" and whether the first Globi Pro offer has been shown, so the app doesn't ask or offer again. Deleting the app erases everything stored on the device.

The app also stores a few technical items on your device:

- the random ID used for usage analytics, plus any analytics events not yet sent (section 2);
- an anonymous ID created by RevenueCat (section 5);
- a random install ID used for app updates, plus the update files themselves (section 8);
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
| App version | For example, 1.3.0. |
| Platform | iOS or Android. |
| Time | When the event happened, according to your device's clock, and the calendar date on your device. Our database also records when it received the event. |

**The events, and the details sent with each:**

| Event | When it's recorded | Details sent |
|---|---|---|
| App opened | The app starts or comes back to the foreground | None |
| Setup step | You move through first-time setup | Which step (introduction, age question, "Where did you hear about Globi?", regions, or name and avatar); how many regions you picked; whether you skipped the "Where did you hear" question; whether you entered a name (yes or no). **Your age answer and the name itself are not sent.** |
| Setup completed | You finish first-time setup | Whether you skipped picking regions; whether you kept the region the app suggested from your device's region setting (yes or no); the app language (English, Spanish or French) |
| Where you heard about Globi | You answer "Where did you hear about Globi?" during first-time setup (skipping sends nothing) | The option you picked: TikTok, Instagram, YouTube, Reddit, App Store or Google Play search, friend or family, teacher or school, or something else |
| Lesson started | A quiz screen opens | The game mode (such as a lesson, Daily Challenge, Review, Survival, Map Mode or a drill); the region and topic; whether you resumed a quiz; whether it's the first quiz straight after setup |
| Lesson, Daily Challenge or Survival completed | You finish a quiz | The game mode; your score; the number of questions; whether it was perfect; whether you levelled up; your total number of lessons completed |
| Challenge viewed / challenge round completed | You open a dated challenge (such as GeoWeek), or finish one of its rounds | Which challenge; whether it's upcoming, live or over; which round; how many rounds you've finished; whether you've finished them all |
| Pro screen viewed or closed | You open or close the Globi Pro screen | Which part of the app sent you there (such as Settings, the shop, or a locked topic); on open, whether you already have Pro |
| Purchase started, succeeded or failed | You tap subscribe, a purchase or free trial starts, or a purchase fails (cancelling isn't recorded) | The plan (monthly, yearly or lifetime); whether a free trial was offered; which part of the app sent you there; for failures, whether the payment is still pending |
| Sign-in completed | You sign in or create an account | How: email, new email account, Apple or Google. Not your email address or account ID. |
| Share tapped / share finished | You tap Share on a results screen, and the share sheet closes | Which results screen (quiz or Survival); whether you shared or cancelled; if you shared, the kind of share target your device reports (for example Messages, or another app's share extension), never who you shared with |
| Rating prompt shown | Apple's "rate this app" prompt appears | What led to it (such as a perfect lesson or a streak milestone) |
| Notification permission | The app asks for permission to send reminders | Whether you allowed notifications; what the permission was before you were asked |
| Reminder opened | You open the app by tapping a notification | Which kind (streak, "we miss you", or the trial-ending reminder) |
| App error | The app shows its "Something went wrong" screen | The screen's general location in the app (for example "/event/[id]", never the ID itself) and the type of error (for example "TypeError"). **No error message and no technical trace**, since those could contain personal details. The same error on the same screen is recorded once per app session, and at most 10 per session. |

**What the events don't contain:** your account ID, email address, display name, age answer, or any text you type. They also don't include your advertising ID, your location, or your contacts, photos or other content. The table that stores the events has no column for your account or your IP address.

**"Where did you hear about Globi?"** New installs see this question once, during first-time setup. It's optional: you can skip it, and skipping sends nothing. Your answer is sent once as a usage event (above), so it's covered by the same switch: with **Share anonymous usage** off, nothing is sent. We use the answers only to see which ways of finding Globi work.

**App errors.** The "App error" event is how we find out a screen is crashing, so we can fix it. It's a usage event like the others: it has the same random install ID, and it isn't sent when **Share anonymous usage** is off. (Separately, the app-update service can receive the message of an error that stopped the app from starting: see section 8.)

**How they're sent.** Events wait on your device, which holds up to the 200 most recent. The app sends them in small batches: when it starts, every 30 seconds or so while you're using it, and when you leave it. Like any internet request, sending them shows your device's IP address to our hosting provider. If you're signed in, the request also carries your normal sign-in session. Neither of these is saved in the analytics table (see "Connection information" below).

**Why we collect them.** We use the events to fix confusing setup steps, see which lessons people finish, and decide which features to build. We don't use them to profile you, to target ads, or to make decisions about you.

**Turning it off.** Go to **Settings → Preferences → Share anonymous usage** and switch it off. The app stops recording and sending events, and deletes any events still waiting on your device. It also stops Apple Ads attribution (section 5) from the next time the app starts. Events already sent stay in our database until they're deleted automatically (see "How long we keep information"). **Reset Progress** also gives you a new random install ID, so a fresh start can't be linked to the old one.

### 3. If you create an account (optional)

You don't need an account to play. An account lets you back up your progress, sync it between devices, and appear on the global leaderboard. Accounts are only available on a device whose age answer is 13 or older (see "Children"). You can sign up with an email address and password, **Sign in with Apple**, or **Sign in with Google**.

**What we store for your account:**

- **Email address.** We use it to sign you in. If email confirmation is switched on, we also use it to send you a confirmation link when you sign up. Other players never see it, and we don't use it for marketing.
- **Password** (email sign-up only). It goes to our sign-in provider, Supabase, which stores it in hashed form. It isn't stored in Globi's own database tables or saved on your device.
- **Account ID.** Supabase gives your account a random ID.
- **Sign in with Apple.** Apple gives us your email address. If you choose **Hide My Email**, it gives us a private relay address that forwards to you instead. Apple may also offer to share your name, but the app doesn't send or store it.
- **Sign in with Google.** You sign in on Google's own page. Google shares your email address, your name and a link to your profile photo with Supabase, which stores them with your sign-in record. Globi doesn't display or use your Google name or photo. Your leaderboard name is always the one you choose in the app.
- **Your synced progress and settings.** These are the same progress and settings listed in section 1, except your age answer, which is never synced. They're stored so you can restore them on your other devices. Other players can't see them.
- **Your leaderboard profile.** See section 4.

Supabase also keeps standard records about your account, such as when you created it and when you last signed in.

### 4. The leaderboard

Every account has a leaderboard profile. It contains your **display name, avatar, level, all-time XP, this week's XP and current streak**, along with your random account ID and the time the profile was last updated.

- **Any signed-in Globi player can read these profiles.** The leaderboard screen shows the display names, avatars, levels and XP of the top 50 players. Players who aren't signed in can't see the leaderboard.
- Your email address is never part of your profile.
- You choose your display name, and it doesn't need to be your real name. Please don't use your full real name. Names can be up to 20 characters, and the app checks them against a basic list of offensive words.
- There's currently no setting to hide your account from the leaderboard. If you don't want to appear on it, you can play without an account, use a name that doesn't identify you, or delete your account. (An account ended by an under-13 answer is renamed to a generated nickname and reset to zero XP straight away, and then deleted: see "Children".)

### 5. Purchases (Globi Pro)

Globi Pro is optional. It's sold through Apple's App Store as a subscription (monthly or yearly) or a one-time lifetime purchase.

- **Apple** handles the payment. We never see your payment card, your billing address or your Apple Account details.
- **RevenueCat** is a service we use to check whether you have an active subscription and to handle purchases, restores and free trials.
  - When the app starts, RevenueCat's software creates an **anonymous ID** for this install and checks whether it has Pro. This happens for every player, even if you never buy anything.
  - If you buy or restore Globi Pro, RevenueCat receives your subscription details from Apple, such as the plan, purchase and renewal dates, price and currency, free-trial status, and transaction IDs.
  - Like most such services, RevenueCat also receives basic technical information, such as your device platform, operating system and app version, and your App Store country.
- **If you're signed in,** the app gives RevenueCat your random Globi **account ID** (not your email or name) so your subscription follows you to your other devices. This happens whenever you're signed in, whether or not you've bought anything. When you sign out, the app switches RevenueCat back to an anonymous ID, except after an under-13 answer (see "Children").

We use this information only to give you the Pro features you paid for and to understand subscription numbers, such as how many people subscribe or cancel.

**Apple Ads attribution (iPhone only, 13 and older, with Share anonymous usage on).** We may advertise Globi in the App Store with Apple Ads. To see which ads lead to installs and subscriptions, the app asks RevenueCat to collect Apple's ad attribution token.

- **When it happens:** only on iPhone, only when the age answer on the device is 13 or older, only after first-time setup is finished, and only while **Share anonymous usage** is on. It never happens in under-13 mode or before the age question has been answered.
- **What the token is:** a short-lived token from Apple's AdServices framework. It is not your advertising ID (IDFA), and the app doesn't ask for App Tracking Transparency permission.
- **What RevenueCat does with it:** RevenueCat sends the token to Apple and gets back whether the install came from an Apple Ads campaign and, if it did, details of that ad, such as the campaign, ad group and keyword. RevenueCat stores this with your RevenueCat ID. If you're signed in, or sign in later, that ID is your Globi account ID, so the attribution is linked to your account at RevenueCat.
- **What we use it for:** only to measure how well our own App Store ads work, for example how many installs and subscriptions a campaign brought in. We don't use it to show you ads, and we don't share it with anyone else.
- **Turning it off:** switch off **Settings → Preferences → Share anonymous usage**. The app stops asking for the token from the next time it starts. Attribution RevenueCat has already received stays with your RevenueCat record; email us if you want that record deleted.

### 6. Reminder notifications

If you allow notifications, the app schedules streak reminders **on your device**. By default they arrive at 7 PM, are scheduled up to a week ahead, and are followed by a couple of "we miss you" reminders if you haven't played for a while. Your device's operating system creates and delivers them. The app doesn't use a push-notification server and doesn't send a notification token anywhere. If you open the app from a reminder, that's recorded as an analytics event, unless you've turned analytics off.

If you start a Globi Pro free trial and have already allowed notifications, the app also schedules one reminder on your device two days before the trial ends, saying how to cancel. The **Daily Reminders** switch doesn't cover this one; your device's notification settings do. The app never sends notifications advertising offers or sales.

### 7. Other things the app does

- **Sharing.** When you tap Share, your device's share sheet opens with a short message and an App Store link. You choose whether to send it and to whom, and we don't see who receives it. Unless you've turned off **Share anonymous usage**, the link carries a campaign tag naming the screen it was shared from (for example, a quiz result), so Apple's App Store statistics can show us how many installs came from shared links. The tag is the same for everyone and doesn't identify you.
- **Ratings.** The "rate this app" prompt comes from Apple, and any rating or review you leave goes to Apple.
- **Links.** This policy, the Terms of Use and subscription management open in a browser, on websites run by GitHub and Apple. Those companies have their own privacy policies.

### 8. App updates (Expo)

Small fixes and content updates can reach the app without a new App Store version. They're delivered by **Expo** (EAS Update), a service run by 650 Industries, Inc.

- **When:** every time the app starts from closed, for every player, including in under-13 mode and with **Share anonymous usage** off. The check happens in the background while you play, and a new update is used the next time the app starts.
- **What Expo receives:** your IP address (as with any internet request); a random install ID that the update software creates on your device (it's not your advertising ID, Apple's per-vendor ID, your account ID, or the analytics ID in section 2); your platform (iOS or Android); the app's build version and release channel; the ID of the update you're running; and the IDs of updates that recently failed to start. If an error crashed the app while it was starting up, the next check also carries that error's message, cut to about 1,000 characters. It doesn't include your name, email, account, age answer or progress.
- **What it's used for:** only to send the right update to your device and to show us how many times each update was launched and how many launches crashed, so we can stop a broken update. It's never used to contact you, to build a profile of you, or for advertising.

### Connection information

Whenever the app talks to Supabase, RevenueCat or Expo, those services receive standard connection information. This includes your IP address and, for Supabase when you're signed in, your sign-in session. They may keep this information in their own logs for security and operations. It travels over encrypted (HTTPS) connections.

## What we do NOT do

- **No ads.** The app has no ad networks or advertising SDKs.
- **No third-party tracking or analytics SDKs.** Our usage analytics go only to our own database (section 2). We don't track you across other companies' apps or websites, and we don't use your advertising ID (IDFA). The app never asks for App Tracking Transparency permission. The one ad-related feature is Apple Ads attribution for players 13 and older (section 5): it uses Apple's own attribution token, only measures our own App Store ads, and is never used to show you ads.
- **No selling.** We don't sell, rent or trade your information, and we don't share it with data brokers or advertisers. (Apple Ads attribution, section 5, only sends Apple's own token back to Apple, through RevenueCat, to find out whether one of our ads led to the install.)
- **No marketing emails.**
- **No location, contacts, photos, camera, microphone or health data.** The app doesn't access any of these.
- **No chat or messaging** between players. The only thing other players can see is your leaderboard profile (section 4).

## Service providers

We share information only with the companies below. Each one receives information only to run part of Globi for us, as described in this policy.

| Provider | What it does for Globi | What it handles |
|---|---|---|
| **Supabase** | Hosts our database, runs account sign-in, and stores analytics events | Account and leaderboard data, synced progress, anonymous analytics events, connection information |
| **RevenueCat** | Manages Globi Pro subscriptions; Apple Ads attribution (13 and older, iPhone only) | Anonymous purchase ID, your account ID if you're signed in, subscription details from Apple, basic device information, Apple's ad attribution token and the attribution details Apple returns, connection information |
| **Expo** (650 Industries, Inc.) | Delivers app updates (EAS Update) | Random update install ID, platform, build and update versions, the message of an error that crashed the app at startup, connection information |
| **Apple** | App Store distribution and payments, Sign in with Apple, notifications, the rating prompt, Apple Ads attribution and App Store campaign statistics | Covered by Apple's privacy policy |
| **Google** | Sign-in, only if you choose Sign in with Google | Covered by Google's privacy policy |
| **GitHub** | Hosts this website (the privacy policy, terms and support pages) | Standard visitor information, such as your IP address, when you view these pages |

Apple may also send us summary statistics about the app. If you've chosen in your device settings to share crash reports with app developers, Apple may send us those too.

We may also disclose information when the law requires it.

## How long we keep information

| Information | How long |
|---|---|
| Data on your device | Until you use Reset Progress or delete the app (Reset Progress keeps your age answer: see section 1). Deleting your account does **not** erase progress saved on the device. |
| Anonymous analytics events | Deleted automatically **90 days** after we receive them. If you turn analytics off, events still waiting on your device are deleted right away. |
| Account, leaderboard profile and synced progress | Until you delete your account. If someone answers under 13 on a device where the account was signed in, it's deleted at once if they choose, otherwise 30 days later unless the account is signed in to again before then (see "Children"). While it waits, we keep a record of the account ID and the date it was queued. We don't otherwise delete inactive accounts automatically. |
| Expo update records | Kept by Expo under its own policies. We see only totals, such as launches and crashes per update. |
| Subscription records at RevenueCat | Kept by RevenueCat for as long as our RevenueCat account holds them. Deleting your Globi account doesn't remove them, but you can email us to ask for your RevenueCat record to be deleted. |
| Purchase records at Apple | Kept by Apple under Apple's own policies. |

When you delete your account or data, it's removed from our live database right away. If we turn on database backups in the future, deleted data could remain in those encrypted backups for up to 7 days before it's overwritten.

## Your choices and rights

- **Turn off usage analytics:** Settings → Preferences → **Share anonymous usage**. This also turns off Apple Ads attribution from the next app start.
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
- **Apple Ads attribution:** our legitimate interest in measuring our own App Store ads. It only runs while **Share anonymous usage** is on, so turning that off is how you object.
- **App update checks (Expo):** our legitimate interest in delivering fixes and stopping broken updates.
- **Keeping records the law requires:** legal obligation.

You can ask us to access, correct, delete, restrict or export your information, or object to how we use it, by emailing us. You can also complain to your local data-protection authority.

## Children

Globi is rated **4+** on the App Store and is meant for players of all ages, including children. It isn't part of the App Store's Kids category.

### The age question

The app asks every player for their **birth month and year**: during first-time setup, or, for people who set up an earlier version, once when they first open the updated app. Nothing is preselected, and the game itself plays the same whatever the answer.

- **The answer stays on the device.** It isn't sent in usage events, it isn't saved with an account or synced, and it isn't sent anywhere else.
- **It's kept until the app is deleted.** Reset Progress keeps it, and the app doesn't ask again. If an answer is ever given again, it can only make the player younger, never older.
- The app works out an age group from it (under 13, 13 to 17, or 18 and over) and updates it as time passes, so a player who turns 13 leaves under-13 mode without being asked again.
- Until the question is answered, the app treats the player as under 13.

### Under-13 mode

When the answer is under 13, the app switches to under-13 mode on that device:

- **No accounts.** Email, Apple and Google sign-in are turned off, so there's no cloud sync and no leaderboard.
- **A generated nickname** instead of a name the child types.
- **No Globi Pro offers the child didn't ask for.** The app doesn't open the Globi Pro screen by itself. A child who taps a Pro or locked item still sees it, and any purchase goes through Apple, where parents can use Ask to Buy and Screen Time.
- **No Apple Ads attribution** (section 5).

These still happen in under-13 mode, and none of them includes a name, email address, contact details or the age answer:

- **Anonymous usage events** (section 2), on by default, including the "Where did you hear about Globi?" answer if one is given and the "App error" event. A parent can turn them off in **Settings → Preferences → Share anonymous usage**.
- **RevenueCat's anonymous ID** (section 5), created for every player when the app starts, so Globi Pro works.
- **The app-update check to Expo** (section 8). Expo receives the IP address, a random install ID created by the update software and, after a crash at startup, that error's message. These are used only to deliver updates and to count launches and crashes for each update, which is support for the app's internal operations. They're never used to contact a child, to build a profile, or for advertising.

### If an account was signed in on the device

If someone answers under 13 on a device where a Globi account is signed in:

1. Straight away, the app replaces the account's leaderboard name with a generated nickname and resets its leaderboard XP and streak to zero, so it drops down the leaderboard. The private synced copy of the account's settings gets the nickname too, so the typed name isn't kept in either of those places.
2. The account is queued for deletion. The app offers to delete it now. Otherwise, **we delete it automatically 30 days later**, unless someone signs in to that account again before then, which they can only do on a device where accounts are allowed. Deleting removes the sign-in record, leaderboard profile and synced progress.
3. The app signs out on that device. **The progress saved on the device stays**, so the child can keep playing.

If the device is offline, the app finishes these steps the next time it's online.

If that account was linked to RevenueCat, the device keeps the same RevenueCat ID (the random account ID, not an email or name) so a Globi Pro purchase keeps working. Deleting the account doesn't delete the RevenueCat record; a parent can ask us to (below).

### Parents

If you're a parent or guardian and want your child's account deleted sooner, or your child made an account on an older version of the app, email **ejbarness@icloud.com** with the email address the account signs in with. For Sign in with Apple this may be an address ending in privaterelay.appleid.com, which your child's Apple Account settings show under Sign in with Apple. We'll delete the account, its leaderboard profile and synced progress, and, if you ask, its RevenueCat purchase record, and reply when it's done. We can't cancel a subscription for you: do that in your Apple Account's subscription settings.

## International transfers

Our database is hosted by Supabase in the United States (Virginia). RevenueCat and Expo (650 Industries, Inc.) are also based in the United States. Your information may be stored and processed in the United States and in other countries where these providers or their own providers operate. Those countries may have different data-protection laws from the country where you live.

## Changes to this policy

If we change this policy, we'll update this page and the effective date at the top. If a change is significant, such as collecting a new kind of information, we'll also mention it in the app's release notes.

**What changed on October 26, 2026 (Globi 1.3):**

- **The age question and under-13 mode** ("Children"). The previous version said the app doesn't ask anyone's age.
- **Account deletion after an under-13 answer**, with a 30-day window, and how parents can ask us to delete an account.
- **Apple Ads attribution** through RevenueCat, for players 13 and older on iPhone with **Share anonymous usage** on (section 5).
- **App updates delivered by Expo** (650 Industries, Inc.) (section 8).
- New usage events: "Where did you hear about Globi?", the "App error" event, and the full, current list of events and details (section 2).
- The trial-ending reminder (section 6) and the campaign tag on shared App Store links (section 7).

**What changed on October 19, 2026:** this version describes two features the previous policy left out:

- the anonymous usage analytics added in Globi 1.2;
- the Globi Pro subscription, managed by RevenueCat, added in Globi 1.1.

The previous version, dated July 4, 2026, said the app had no analytics and didn't mention RevenueCat. It was out of date.

## Contact

Questions or requests: **ejbarness@icloud.com**
