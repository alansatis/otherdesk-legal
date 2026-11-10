# Version history

Every change to a published page gets a new version here and a git tag (`vMAJOR.MINOR`).

- **Major** (2.0): a change in what data is collected, why, or who receives it.
- **Minor** (1.1): the same practices, described more precisely.

Each version is published with the app build whose behaviour it describes, never before it.

## v2.0 — 10 November 2026 on Android; iOS with its App Store release (Privacy Policy and Terms)

Terms of Service:
- the app is free and funded by ads (Google AdMob); third-party ad content and links;
- the 72-hour access and Pro are no longer sold; existing Pro subscriptions keep renewing until cancelled;
- check-ins are accepted only from within 100 metres of the venue.

Privacy Policy:

Ads in the app (Google AdMob), so this is a major version:
- two legal bases: consent to store or read information on the device (and, on Android, for personalised ads); legitimate interest for limited ads shown without consent, with the right to object;
- Google AdMob described as an independent controller, outside the list of providers acting on our behalf; other ad technology providers managed in the consent form; links to Google's partner-sites and ads pages; retention by Google;
- new data: the device's advertising ID and basic device and usage information, collected by Google AdMob;
- new recipient: Google AdMob (United States);
- location: a check-in sends the device position to our server once, to confirm it is within 100 metres of the venue; the position is not stored. Checking in now needs location access;
- new section 5, Advertising: where ads appear and which are marked "Ad"; Google's consent form before any ad where the law requires it (EEA, UK, Switzerland); limited ads without consent; Profile › Privacy and ads to change the choice;
- sections 6–13 renumbered;
- iOS: the app never shows Apple's tracking prompt, so no IDFA and no ads personalised from activity elsewhere;
- iOS: the App Store has never sold a plan, so the iOS pages no longer describe App Store purchases, cancelling in App Store settings or Apple as a payment processor; a plan bought on another platform is managed where it was bought;
- Android: in the EEA, UK and Switzerland, personalised ads and the advertising ID only with consent; elsewhere Google may use the advertising ID under its own policies;
- usage analytics (PostHog, opt-in) are linked to the account ID once signed in, including the venues viewed, checked in at and saved; they are deleted from PostHog when the account is deleted (also on the Delete account page, now v2.0);
- RevenueCat receives the account ID at sign-in;
- location: asked when the app first opens; the map opens on the area you are in; distances show "—" without location.

## v1.1 — 6 October 2026

One version of each page per store, so each only names the store it is published on:
- `ios/` (App Store) and `android/` (Google Play) for the Privacy Policy, Terms of Service and account-deletion page;
- payments, cancellation, refunds and purchase records now name only that store (Apple on iOS, Google on Android);
- on Android, sign-in names only Google, the only provider the Android app offers; on iOS, Apple and Google, both offered there;
- the old addresses (`/privacy/`, `/terms/`, `/delete-account/`) link to both versions.

Same practices: what is collected, why and who receives it are unchanged.

## v1.0 — 29 September 2026

First published version of the Privacy Policy, Terms of Service and account-deletion page.

Adjusted before launch, while no user had accepted it:
- check-ins are kept permanently and anonymised when an account is deleted, instead of expiring after 3 hours;
- added the legal bases, international transfers, security, children, subscriptions, governing law and dispute resolution;
- corrected the effective date from 30 to 29 September.

From launch on, every change follows the versioning rules above.
