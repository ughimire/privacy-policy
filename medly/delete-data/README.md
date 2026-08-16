# Medly — Delete your data

**App:** Medly — Pill Reminder & Tracker (`com.umeshghimire.medly`)
**Publisher:** Umesh Ghimire
**Last updated:** 16 August 2026

This page explains how to delete data held by Medly, and what each option
removes. See the [privacy policy](../) for what is collected in the first place.

---

## The short version

Medly creates an **anonymous account for you on first launch** and backs your
medications, doses and health measurements up to it automatically, so a lost
phone does not take your history with it. There is no sign-in step, so most
people have an account without having chosen one.

Deleting your data therefore has two parts: the copy on your phone, and the
backup copy. Both are covered below.

---

## 1. Delete everything on your phone

Uninstall Medly.

Medications, doses, health measurements, symptoms, profiles, your name and email
if you entered them, and all settings are stored in the app's private storage
and are removed with it.

This cannot be undone and we cannot recover it for you. If you want to keep a
copy first, use **Settings → Your data → Export a backup**, which produces a
readable JSON file.

---

## 2. Delete your cloud account and its data

This applies to everyone, not only people who signed in — see above.

In the app: **Settings → Your data → Delete cloud account**

This deletes the account and everything stored under it on the server —
medications, dose records, health measurements and profile names — and stops
syncing.

From version 1.2.0 onward this is permanent: Medly will not create a
replacement account for you the next time you open it. (Earlier versions did,
which meant the deletion silently undid itself. That was a bug and it is
fixed.) Signing in deliberately afterwards starts the backup again.

Data already on your phone is deliberately left alone. Deleting a cloud account
is a request to stop syncing, not an instruction to destroy the medication
history on the device in front of you. To remove that too, uninstall the app as
described above.

---

## 3. Request deletion by email

If you cannot open the app — for example you have lost or replaced the phone —
email:

**me.umeshuser@gmail.com**

Please send it from the address you signed in with, and put **"Delete my Medly
data"** in the subject. We will delete the account and confirm within 30 days.

Because accounts are anonymous by default and hold no identifying details beyond
what you entered, we may not be able to locate an account if you cannot tell us
the email it was created with.

---

## What is kept, and for how long

| Data | Where | Retention |
|---|---|---|
| Medications, doses, measurements, symptoms, profiles | Your phone | Until you delete it or uninstall |
| The same data, backed up automatically | Your anonymous account | Until you delete the account |
| Crash reports | Firebase Crashlytics | Retained by Google per their schedule; contains **no** medical data, only stack traces and device model |
| Advertising identifiers | Google AdMob | Governed by the [Google Privacy Policy](https://policies.google.com/privacy) |

Medly does not sell data, and does not share health data with advertisers, data
brokers, insurers or employers.

---

## Contact

**Umesh Ghimire** — me.umeshuser@gmail.com
