# Privacy Policy for WordigoBee

**Last updated: 14 October 2026**

WordigoBee ("the App", "we", "us") is an English-learning app. This policy explains what
information the App collects, how it's used, and the choices you have. It applies to the App
on Android and iOS.

## The short version

WordigoBee does not require an account, login, or email address. There is no sign-up. A
local profile (a display name and a chosen emoji avatar) and your learning progress are
stored **only on your device** — we do not operate user accounts or a server-side user
database. The App does use a small number of third-party services (listed below) for lesson
content delivery, product analytics, and ads, each of which may collect limited technical
data as described in this policy.

## Information stored only on your device

The App uses local on-device storage (via the Hive database) for:

- **Local profile** — a display name and an avatar you pick from a fixed set of emoji. No
  email address, phone number, or photo is collected.
- **Learning progress** — experience points (XP), coins, streak count, unlocked levels,
  earned badges, and which lessons/quizzes you've completed.
- **App preferences** — language, English accent variant, speech rate, sound and
  notification settings, dark mode, and whether you've completed the onboarding tutorial.

This data never leaves your device and is not transmitted to us or any third party. It is
removed if you uninstall the App or clear its app data. There is no mechanism to recover
this data if you switch devices, since it is never backed up to a server under our control.

## Information collected by third-party services

The App uses the following third-party services, each of which may independently collect
technical data under its own privacy policy:

### Firebase (Google)

- **Cloud Firestore** is used to *deliver lesson and quiz content* to the App (e.g. fetching
  a lesson's text). This is one-way content delivery — no personal information about you is
  written to Firestore. Standard network/device metadata (e.g. IP address) may be visible to
  Google as the service operator, as with any network request.
- **Firebase Analytics** is used to understand product usage in aggregate: which screens are
  viewed, which games are started, level-completion and score events, and coarse user
  properties (e.g. current level). This data is associated with a Firebase-generated
  install/device identifier, not with any name or email, since the App has no accounts.
  See [Google's Firebase privacy documentation](https://firebase.google.com/support/privacy).

### Google AdMob

The App shows banner ads via Google AdMob, which may collect device identifiers (such as an
advertising ID) to serve and measure ads, and may use them for ad personalization subject to
your consent choice. Before ads are requested, the App runs Google's User Messaging Platform (UMP)
consent flow and asks for your consent where required by your region (e.g. the EEA/UK).
You can review or change your ad consent choice at any time from the App's Settings screen
under "Ad Privacy Options."
See [Google's AdMob data use policy](https://support.google.com/admob/answer/6128543).

### Speech recognition and text-to-speech

Pronunciation-practice lessons use your device's microphone and the operating system's
built-in speech-to-text service to transcribe what you say, so the App can compare it to the
target phrase. The App does not record or store audio itself, and does not send audio to our
own servers — recognition is handled by the OS-level speech service (Android/iOS system
speech recognition), which may process audio on-device or via that platform's own servers
depending on your device and settings; see your device manufacturer's privacy policy for
details on how it handles speech recognition. Text-to-speech (the App reading phrases aloud
to you) happens entirely on-device and involves no data transmission.

Microphone access is requested only when you tap the microphone button during a lesson, and
only for that recognition attempt.

## Children's privacy

WordigoBee is a general-audience learning app and does not knowingly collect personal
information such as names, email addresses, or photos from anyone, including children —
there are no accounts, and the local profile only stores a display name and emoji avatar you
choose yourself, kept solely on your device. The App does not ask for your age, so it does not apply
age-specific ad treatment; ads are capped to General-audience content
(`MaxAdContentRating.g`). If you believe a child has provided us information through means other than
the App's normal on-device functionality, contact us at the address below and we will address
it. This policy is intended to support compliance with COPPA (US) and equivalent regional
child-privacy rules, but does not itself constitute legal advice.

## Permissions the App requests

| Permission | Why |
|---|---|
| Microphone | Speech recognition during pronunciation practice lessons |
| Internet / network state | Fetching lesson content, analytics, and ads |
| Bluetooth | Routing audio (text-to-speech / recognition) through connected Bluetooth audio devices |

The App does not request location, contacts, camera, storage, or any other permission beyond
the above.

## Data retention and deletion

Because your profile and progress are stored only on your device, you can delete all of it at
any time by uninstalling the App, or by clearing the App's storage/data from your device's
system settings. There is no server-side account for us to delete on your behalf, since none
exists. Data collected by the third-party services above (Firebase Analytics, AdMob) is
retained and deleted according to those services' own policies, linked above.

## Changes to this policy

We may update this policy as the App changes. Material changes will be reflected by updating
the "Last updated" date at the top of this page.

## Contact us

Questions about this policy or the App's data practices: **contact@rahtech.in**
