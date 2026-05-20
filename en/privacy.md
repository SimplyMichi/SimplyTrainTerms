---
title: Privacy Policy
layout: default
---

# ProgliQ - Privacy Policy

Effective date: [INKRAFTTRETENSDATUM]

> This Privacy Policy is a project-specific draft for `ProgliQ` based on the current code and feature set. Before publication, all placeholders must be completed and the final version should be reviewed by qualified legal counsel.

## 1. Controller

- Controller: `[VOLLSTAENDIGER NAME ODER FIRMA]`
- Legal form: `[RECHTSFORM, FALLS VORHANDEN]`
- Address: `[LADUNGSFAEHIGE ANSCHRIFT]`
- Email: `[KONTAKT-E-MAIL]`
- Support: `[SUPPORT-URL]`

If legally required or applicable:

- Privacy contact / Data Protection Officer: `[DATENSCHUTZ-KONTAKT ODER DSB, FALLS VORHANDEN]`

## 2. What this Privacy Policy covers

This Privacy Policy explains which personal data is processed when you use the `ProgliQ` app, for what purposes, on which legal basis, which recipients may be involved, and which rights data subjects may have.

`ProgliQ` is an offline-first iOS app for workout planning, workout tracking, and progress documentation. Based on the current implementation, the app processes data primarily on the device. Optional Apple services such as `Sign in with Apple`, `CloudKit`, `HealthKit`, and local iOS notifications are only used where required for specific features or where the user activates them.

## 3. Categories of personal data

Depending on how you use the app, we may process in particular:

- Account and identity data:
  - Apple user ID from `Sign in with Apple`
  - email address provided by Apple, if shared
  - display name provided by Apple, if shared
- Contract and purchase-related data:
  - start timestamp of the 60-day trial (`firstSignedInAt`, immutable in your private iCloud database)
  - purchase or unlock status (`Lifetime`, `6-Month`, `Yearly`)
  - active entitlement information from Apple StoreKit (original transaction ID, expiration date for subscriptions, revocation timestamp)
- Workout and usage data:
  - workout plan
  - completed sessions, exercises, sets, repetitions, loads, and RIR values
  - exercise notes
  - progress and history data
  - preferences such as split, training frequency, session duration, focus muscles, equipment, and deload settings
- Body and health-related data:
  - age, sex, height, body weight
  - optional body measurements and body fat information
  - joint or movement limitations
- Progress photos:
  - optionally captured or stored progress photos
  - preview images of such photos
  - metadata such as capture date and context
- HealthKit data:
  - data optionally read from Apple Health, especially body weight
  - workout and body weight data optionally written to Apple Health
- Device and permission data:
  - status of camera, notification, and HealthKit permissions
  - status of cloud backup and photo storage settings

## 4. Purposes of processing

We process personal data only to the extent necessary to operate the app and the features you use. In particular for the following purposes:

- providing and operating the app
- signing in and recognizing the user account via `Sign in with Apple`
- storing and synchronizing workout, profile, and settings data
- creating, adapting, and progressing your workout plan
- documenting and visualizing your training progress
- storing and displaying optional progress photos
- synchronizing with Apple Health where enabled by you
- restoring an optionally purchased unlock status
- sending purely local device notifications where enabled by you
- preventing errors, ensuring data security, and preventing misuse

## 5. Legal bases

Where the GDPR applies, we rely in particular on the following legal bases:

- Art. 6(1)(b) GDPR:
  - for providing the app,
  - for login, app operation, data storage, workout planning, and purchase status handling,
  - where the respective processing is necessary for performing the usage agreement
- Art. 6(1)(a) GDPR:
  - for optional features you voluntarily activate, such as camera usage, local notifications, or iCloud backup, where consent or voluntary activation is the relevant basis
- Art. 9(2)(a) GDPR:
  - for processing special categories of personal data, in particular health-related information, body data, progress photos with health relevance, and optional HealthKit use, where you voluntarily enter such data or explicitly activate the relevant feature
- Art. 6(1)(c) GDPR:
  - where processing is necessary to comply with legal obligations
- Art. 6(1)(f) GDPR:
  - where necessary to ensure IT security, integrity, misuse prevention, or legal defense, unless your interests or fundamental rights override such interests

## 6. Local processing on your device

Based on the current implementation, `ProgliQ` is designed as an offline-first app. This means:

- workout and profile data are generally stored locally on your iPhone,
- local storage is the primary source of truth,
- without optional features enabled, core usage data is not transmitted to a separate server operated by the Provider.

Data stored locally may include in particular:

- workout plan and workout history
- profile and preference data
- exercise and load configuration data
- optional locally stored progress photos
- local preview images of progress photos
- status information regarding permissions and optional Apple integrations
- locally cached purchase status

## 7. Sign in with Apple

Certain features, or even initial use of the app, may require `Sign in with Apple`. In this context we may process:

- your Apple user ID,
- your email address provided by Apple, if shared,
- your name provided by Apple, if shared.

These data are used in particular to:

- associate your account within the app,
- assign local usage data to your account,
- separate optional cloud-based features by account,
- support purchase status handling and restoration on a new device.

Based on the current implementation, these data are stored locally in the iOS Keychain and app-related local storage. Apple's privacy terms also apply to `Sign in with Apple`.

## 8. In-app purchase, subscriptions, and StoreKit

`ProgliQ` offers a 60-day trial through the Apple App Store, as well as the following paid products:

- an auto-renewing 6-month subscription,
- an auto-renewing annual subscription,
- a one-time `Lifetime` purchase.

If you use, restore, or auto-renew any of these products, the related entitlement information is processed through Apple StoreKit. We do not receive your full payment details; we only process the information required for unlocking, restoring, and correctly displaying your premium status (product ID, original transaction ID, expiration date, revocation timestamp).

Payment processing as well as subscription management and cancellation are handled exclusively through Apple and your Apple ID settings. Apple's privacy and contractual terms also apply.

## 9. CloudKit and iCloud

`ProgliQ` uses `CloudKit` (your private iCloud database) for two distinct purposes:

### 9.1 Trial and entitlement status (essential)

On first `Sign in with Apple`, a record containing the start timestamp of your 60-day trial (`firstSignedInAt`) is created in your private iCloud database. This timestamp is immutable and bound to your Apple ID. It is required to correctly continue the trial across device changes, app re-installation, or sign-out.

The same record may store the most recently reported entitlement information from Apple StoreKit (Lifetime status or active subscription, expiration date, original transaction ID).

This function cannot be disabled because it is required for the correct handling of trial and entitlement status.

### 9.2 Database and photo backup (optional)

In addition, a full cloud backup can be enabled in the app settings. If enabled, the following data is stored in a separate record in your private iCloud database:

- the local app database containing workout and profile data,
- platform and app preferences,
- optionally the original files of your progress photos (see Section 10).

The backup is used solely to restore your app data on a new or reset device. It is optional and can be disabled at any time.

### 9.3 General notes on iCloud / CloudKit

- Both records reside in your private iCloud database — the Provider has no direct access to them.
- Processing takes place within Apple's infrastructure.
- Our influence over further processing by Apple is limited to what Apple provides.
- Apple's own privacy information also applies to these services.

## 10. Progress photos and camera

The camera is only used if you actively use the progress photo feature.

Depending on the storage option you choose, photos are:

- stored locally inside the app, or
- stored as private originals in your iCloud / CloudKit environment, while only a preview remains locally.

Progress photos are used solely for your personal documentation inside the app. Based on the current implementation, they are not used by us for advertising, tracking, or profiling.

## 11. HealthKit / Apple Health

The app may optionally use `HealthKit`. This only happens if you grant the relevant iOS-level HealthKit permissions and enable the feature in the app.

Based on the current project implementation, the app may in particular:

- write strength workouts to Apple Health,
- write body weight to Apple Health,
- read certain Health data such as body weight from Apple Health.

HealthKit data is processed solely to support your workout documentation and in-app context.

Important notes:

- HealthKit data constitutes health-related data under the GDPR.
- HealthKit use is voluntary.
- If you do not enable HealthKit, this integration is not used.
- Data already written to Apple Health may remain stored within Apple's ecosystem. Where such data has already been written to Apple Health, full removal may additionally require deletion in Apple Health or via Apple settings.

## 12. Local notifications

The app may use local notifications on your device, especially for:

- rest timers during workouts,
- reminders to log body weight.

Based on the current implementation, these are local iOS notifications and not server-side push notifications sent from a backend operated by the Provider.

In this context the device may process in particular:

- notification permission status,
- timer and reminder status,
- title or reference to the current exercise,
- scheduled times for local notifications.

## 13. No advertising, no app tracking, no third-party analytics

Based on the current project status, `ProgliQ` uses:

- no advertising SDKs,
- no cross-app tracking,
- no IDFA-based ad tracking,
- no third-party analytics or marketing SDKs.

Based on the current implementation, the app is not designed to track users across third-party apps or websites.

## 14. Recipients and categories of recipients

Personal data may, where technically required and where used by you, be transferred to or processed by the following categories of recipients:

- Apple:
  - `Sign in with Apple`
  - App Store / StoreKit
  - iCloud / CloudKit
  - Apple Health / HealthKit
  - iOS notification system services
- Other recipients only where:
  - you contact us separately,
  - we are legally obliged to do so,
  - this is necessary for the assertion, exercise, or defense of legal claims

Based on the current implementation, the Provider does not operate a separate external analytics, advertising, or tracking backend for the app.

## 15. Transfers to third countries

To the extent Apple or other integrated services process personal data in countries outside the EU or EEA, such transfers may take place on the basis of the data protection mechanisms used by Apple. The specific international processing within Apple's infrastructure is governed by Apple's own privacy information.

## 16. Retention period

We store personal data only for as long as necessary for the relevant purposes, or until you delete it or disable the relevant feature, unless statutory retention obligations require longer storage.

Typically this means:

- local app data:
  - until deleted by you,
  - until you use the account/data deletion function in the app,
  - or until the app is uninstalled, unless data additionally exists in iCloud or HealthKit
- Keychain or session data:
  - until active account/data deletion or session removal
- CloudKit backups and iCloud photos:
  - until deleted by you, removed through deactivation with deletion, or removed through the in-app account deletion flow, where technically provided
- HealthKit data:
  - once written to Apple Health, according to Apple's Health data deletion and retention rules

## 17. Your rights

Where the GDPR applies, you have the following rights subject to the applicable legal conditions:

- right of access, Art. 15 GDPR
- right to rectification, Art. 16 GDPR
- right to erasure, Art. 17 GDPR
- right to restriction of processing, Art. 18 GDPR
- right to data portability, Art. 20 GDPR
- right to object, Art. 21 GDPR
- right to withdraw consent at any time with effect for the future
- right to lodge a complaint with a data protection supervisory authority

You can already change or delete many data elements directly in the app. For privacy-related rights requests, please contact us at `[KONTAKT-E-MAIL]`.

## 18. Sign-out, account, and data deletion in the app

`ProgliQ` provides two distinct in-app actions to interrupt or end usage:

### 18.1 Sign out

Using the "Sign out" function in the profile/settings area:

- local Apple session data is removed from the iOS Keychain,
- locally stored workout, profile, and photo data remain intact,
- iCloud / CloudKit backup and the trial status record remain intact,
- all data is available again after signing back in with the same Apple ID.

### 18.2 Delete account and local data

Using the "Delete account" function in the profile/settings area, the following are deleted in particular:

- locally stored app-related user data and databases,
- locally stored progress photos and their previews,
- the app-related CloudKit backup record (database backup),
- private iCloud photo records managed by the app,
- locally stored Apple session data for the app.

### 18.3 Important limitations

- The record marking the start of the trial (`firstSignedInAt`, see Section 9.1) remains in your private iCloud database for systemic reasons and is **not** removed by in-app account deletion. The purpose is to prevent a repeated trial with the same Apple ID. Full removal of this record can be done on the Apple side via `Settings` → Apple ID → `iCloud` → `Apps using iCloud` → `ProgliQ`.
- An in-app subscription or `Lifetime` entitlement acquired through Apple remains with Apple and is not cancelled by in-app account deletion. Cancellation of a subscription must be done through the Apple ID settings.
- Data already written to Apple Health is not automatically removed from Apple Health by the app. Deletion can be done through the Apple Health app or Apple settings.

## 19. Data security

We take appropriate technical and organizational measures to protect personal data against loss, misuse, unauthorized access, or unauthorized alteration. Based on the current implementation, this includes in particular:

- local on-device storage as the default model,
- use of Apple system mechanisms such as Keychain, HealthKit, and private CloudKit databases where those features are used,
- limiting optional data transfers to Apple services actively used by you.

However, completely risk-free data processing cannot be guaranteed for digital services.

## 20. Changes to this Privacy Policy

We may update this Privacy Policy where necessary for legal, technical, or product-related reasons. The current version applies.

## 21. Contact

If you have questions about privacy, please contact us at:

- Email: `[KONTAKT-E-MAIL]`
- Support: `[SUPPORT-URL]`
