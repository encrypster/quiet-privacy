# Quiet: privacy policy

English · [Oʻzbekcha](https://encrypster.github.io/quiet-privacy/uz/) · [Русский](https://encrypster.github.io/quiet-privacy/ru/) · [Deutsch](https://encrypster.github.io/quiet-privacy/de/)

Last updated: 20 November 2026

Quiet is a home screen app for Android with tools for using the phone less: app limits and
blocks, a notification filter, screen-time statistics, focus sessions and grayscale.

## In short

Quiet collects nothing for itself. It has no account, no server, no advertising and no analytics.
Everything it stores stays on your phone and is removed when you uninstall it.

The one exception is a choice a parent makes: if a parent connects their own Telegram bot to the
parent lock, a short note goes to that bot when Quiet closes adult content (see "Telling the
parent" below). Without a connected bot nothing is sent. The phone shows a notification for as
long as a bot is connected.

## What Quiet stores on your phone

- Your settings, favorites, rules, schedules and focus profiles.
- A usage log: which apps were in front and for how long, and how often the phone was unlocked.
  It is kept for the number of days set in Quiet (shown on the About page) and then deleted.
- Notifications you asked Quiet to hold: the app, title and text, until you open or clear them,
  and for no longer than the number of days set in Quiet.
- Whether Quiet Pro is active (Google Play build only).
- If you set a parent lock: a salted digest of its PIN, never the PIN itself.
- If a parent connected a Telegram bot: its token and chat, and the closings not yet sent.

None of this leaves the phone, except the notes to a parent's bot described below. A backup file
is written only when you ask for one, to the place you choose, and contains settings only: no
usage history and no notifications.

## What each access is used for

- **Accessibility service (Accessibility API).** Quiet reads which app is on screen so that it
  can show the limits, waits and blocks you set. With the Shorts and Reels switch on, it also
  reads the names of screen parts in YouTube, Instagram and Facebook to tell a short video from
  the rest. During a strict session, or while the parent lock is on, it reads the text of system
  settings pages: the pages about Quiet, the date and time page and, under the parent lock,
  Developer options, so that they can be kept closed. It runs the lock-screen and notification
  gestures you choose. With closing adult content switched on (parent lock), it reads the words
  on screen in messengers, browsers and social apps to look for words that mark adult content,
  and in Telegram the line that tells a bot from a person, a group or a channel, so that bots the
  parent did not allow can be closed. With the picture check also switched on (Quiet Pro), it
  takes a picture of the screen every few seconds while one of those apps is in front and has it
  judged on the phone by a built-in model; the picture is thrown away at once and never stored or
  sent. All of this is checked on the phone. Otherwise it does not read what you type, passwords
  or the content of your apps. Nothing it reads or sees is stored beyond the usage log above, and
  nothing from the screen is ever sent.
- **Usage access.** Screen-time numbers and daily limits.
- **Notification access.** Holding or muting the notifications of the apps you choose.
- **Calendar (optional).** Showing your next event on the home screen. Events are read when
  shown and are not stored.
- **Device administrator (optional).** Keeping Quiet installed during a strict session you
  started, and while a parent lock has a PIN. It is used for nothing else and can be switched
  off in Quiet when no strict session is running and the parent lock is open.
- **Device owner (optional, set up by a parent from a computer).** On a phone a parent made Quiet
  the device owner of, the phone itself refuses Safe Mode, a factory reset from Settings,
  changing the date and time, and new users while the parent lock is locked. It reads nothing.
- **Network (only for a parent's Telegram bot).** Used for nothing else.
- **Contacts (optional).** Finding a contact by name in the app search, when you switch that on.
  Names are read while you search and are not stored.
- **List of installed apps.** A home screen has to show the apps that can be opened.

## Telling the parent

A parent can create a Telegram bot of their own and connect it on the parent lock page. From then
on, when Quiet closes adult content, it sends that bot a short message for the parent: the time,
the name of the app, and whether words or a picture were the reason. No words, pictures or other
content from the screen are ever sent. Messages go directly from the phone to Telegram's servers
(api.telegram.org) and are handled under Telegram's privacy policy; Quiet has no server and keeps
no copy elsewhere. The bot can be disconnected on the same page; while the parent lock is locked
only the parent can do that. A notification on the phone says that the parent is told for as long
as a bot is connected.

## Purchases

In the Google Play build, Quiet Pro is bought through Google Play. The payment is handled by
Google under Google's own privacy policy. Quiet learns only whether the purchase exists; it does
not receive your name, e-mail address or payment details, and it has no server.

## Children

Quiet is not directed at children. A parent may set it up on a child's phone with the parent
lock; the child then sees the same disclosures and, if a bot is connected, the notification
saying that the parent is told. Quiet collects no data for itself from anyone.

## If you live in the EU, the EEA or the UK

The General Data Protection Regulation (GDPR) and the UK GDPR give you rights over personal data.
This is how they apply to Quiet.

**Who is responsible.** Quiet is made by Test Developer, Test Street 1, 00000 Test City, test@example.com.

**What the developer receives.** Nothing. Quiet has no server, no account, no analytics and no
advertising, so the developer never receives or holds personal data about you or your child.
What Quiet keeps (listed above) stays on your phone and under your control: you can delete all of
it with "Delete everything" in Quiet, or by uninstalling the app.

**Why Quiet works with this data on your phone.** To do what you switched on (Art. 6(1)(b) GDPR).
Closing adult content, the picture check and telling the parent are switched on by a parent under
the parent lock, to protect a child (Art. 6(1)(f), the legitimate interest in protecting a minor).
Screen pictures are judged on the phone and thrown away at once.

**Telling the parent.** If a parent connects their own Telegram bot, the time, the app's name and
the reason of each closing go from the phone to Telegram, which may handle them outside the EEA
under its own privacy policy. The parent chooses this and can stop it at any time by disconnecting
the bot; the child's phone shows a notification for as long as a bot is connected.

**Purchases.** Google Play handles purchases as a separate controller, under Google's privacy
policy.

**Your rights.** You may ask for access to your personal data, its correction or erasure, to
restrict or object to its processing, and for data portability. As the developer holds no data,
you exercise most of these on the phone itself, as described above; questions go to the contact
address below. You may also complain to the data protection authority of your country.

**Children.** In the EU a child can agree to online services alone from an age between 13 and 16,
depending on the country; below that age a parent decides. Quiet's parental features are meant
to be set up by a parent on a child's phone.

## Changes

If this policy changes, the new text is published at this address with a new date.

## Contact

test@example.com
