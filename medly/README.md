# Medly — Privacy Policy & Terms

**App:** Medly — Pill Reminder & Tracker (`com.umeshghimire.medly`)
**Publisher:** Umesh Ghimire
**Last updated:** 16 August 2026

---

## Privacy Policy

Medly handles health information, which deserves a policy written plainly rather
than defensively. This describes what the app actually does, checked against the
source code rather than against intentions.

### The short version

- **Your medication data stays on your phone by default.** Medly works fully
  without an account, without a network connection, and without sending anything
  anywhere.
- **Nothing medical is ever sent to crash reporting or advertising.**
- Three things do leave the device, each described below: an optional cloud
  backup you turn on by signing in, anonymous crash reports, and advertising.
- One thing surprises people, so it is stated first: **when you type a
  medication name, that name is sent to two US government services** to look up
  spellings and label information.

---

### 1. What stays on your device

All of this is held locally and is not transmitted unless you sign in:

- Medications: name, dose, unit, form, schedule, start and end dates, notes,
  supply counts
- Doses: when each was due, whether it was taken, skipped, missed or snoozed,
  and when you acted
- Health measurements: blood pressure, weight, blood glucose, heart rate,
  temperature, oxygen saturation, mood, pain
- Symptoms and side effects you record, and any medication you associate them
  with
- Profiles: the names you give the people you track medication for
- Your name and email, if you entered them during setup
- App settings: language, theme, reminder preferences

Uninstalling the app deletes all of it. **Medly cannot recover it for you** —
this is why the app offers a backup export.

---

### 2. Medication names, when you search for them

When you type a medication name while adding or viewing a medication, that text
is sent to:

- **`clinicaltables.nlm.nih.gov`** — the US National Library of Medicine, to
  suggest spellings and strengths
- **`api.fda.gov`** — the US Food and Drug Administration, to retrieve that
  medication's official label

These requests contain **only the medication name**. They do not include your
name, your email, your device identifier, your doses, or anything else about
you. Both are public US government APIs and are used without an account or key.

If you never type a medication name, neither service is contacted. The app is
fully usable if these requests fail or are blocked.

---

### 3. Cloud sync — only if you sign in

Medly can sync to Google Firebase so your data survives losing your phone.
**This is off until you sign in**, and reminders never depend on it.

When enabled, these are stored under your account:

- Medications, dose records, health measurements, and profile names

Sync is one-directional today: the app uploads, and does not yet download.

**Signing out or deleting your account** stops sync and removes the server-side
copy. Settings → Your data → Delete cloud account does this in-app. Your local
data is deliberately left untouched — deleting a cloud account is a request to
stop syncing, not to destroy the history on the phone in front of you.

---

### 4. Crash reports

Medly uses Firebase Crashlytics to learn about crashes on devices we cannot
test. Reports contain stack traces, the device model, the OS version, and the
app version.

**No medication name, dose, measurement, note, symptom, profile name or email is
ever attached to a crash report.** This is enforced in the code, not merely
promised: reporting only ever receives errors and fixed diagnostic strings.

Crash reporting is disabled entirely in development builds.

---

### 5. Advertising

Medly is free and shows advertisements through **Google AdMob**. Ads are what
pay for the app; there is no subscription and no purchase.

Google, acting as an independent advertising provider, may collect and process
data when an ad is requested or shown, including:

- The Android advertising identifier
- IP address and approximate, non-precise location derived from it
- Device and app information, such as model, operating system and app version
- Interactions with ads, such as views and taps

We do not receive this data in a form that identifies you. We see only aggregate
reports — impressions, clicks, revenue.

Google's handling of this data is governed by the
[Google Privacy Policy](https://policies.google.com/privacy) and
[how Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites).

If you are in the EEA, UK or Switzerland, you are asked for consent before any ad
is requested, using a Google-certified consent platform. You can change that
choice at any time in **Settings → Privacy → Ad privacy settings**.

**Your health data is never used for advertising and is never shared with
advertisers.** Medly does not send AdMob anything about your medications.

---

### 6. What Medly does not do

- It does not sell your data. There is no arrangement under which anyone pays
  for it.
- It does not share health data with advertisers, data brokers, insurers or
  employers.
- It does not track your location.
- It does not read your contacts, photos, files or messages.
- It does not use your health data to train any model.

---

### 7. Permissions, and why each exists

| Permission | Why |
|---|---|
| Notifications | To show medication reminders. Without it the app cannot do its job. |
| Exact alarms | So a reminder arrives at the minute it is due rather than up to an hour late. |
| Full-screen intent | So a dose you mark critical can ring over the lock screen like an alarm. |
| Run at startup | So reminders survive restarting your phone. |
| Ignore battery optimisation | Optional. Stops the system delaying reminders to save power. |
| Internet | For drug-name lookup, optional sync, crash reports and ads. |

Medly asks for no permission it does not use.

---

### 8. Children

Medly is not directed at children under 13 and we do not knowingly collect their
data. A parent may of course use Medly to manage a child's medication — in that
case the data is the parent's own record, held under their account.

---

### 9. Your choices, retention and deletion

- **Use Medly with no account.** Everything except sync works.
- **Export your data** at any time: Settings → Your data → Export a backup. The
  file is readable JSON, not a proprietary format.
- **Delete your cloud account** in-app: Settings → Your data → Delete cloud
  account.
- **Delete everything** by uninstalling the app.
- **Request deletion by email** at me.umeshuser@gmail.com if you cannot access
  the app.

Data held on the device is kept until you delete it or uninstall. Data synced to
your account is kept until you delete the account.

---

### 10. Security

Data on the device is held in the app's private storage, which other apps cannot
read. Synced data travels over encrypted connections and is protected by
server-side rules that allow only your own account to read or write it. Health
data is excluded from Android's automatic cloud backup and from device-to-device
transfer, so it is not copied anywhere you did not choose.

No system is perfectly secure, and we cannot guarantee absolute security.

---

### 11. Changes to this policy

If this policy changes materially, the app will say so before the change takes
effect. The date at the top always reflects the current version.

---

### 12. Contact

**Developer:** Umesh Ghimire
**Email:** me.umeshuser@gmail.com

---

## Terms & Conditions

### 1. Acceptance

By installing or using Medly you agree to these terms. If you do not agree,
please do not use the app.

### 2. Licence

You are granted a personal, non-exclusive, non-transferable, revocable licence to
use Medly on devices you own or control, for personal, non-commercial purposes.

You may not sell, sublicense, or redistribute the app, nor decompile or reverse
engineer it except where that right cannot be excluded by law.

### 3. Medly is not a medical device

**Medly is a reminder and record-keeping tool. It is not a medical device and it
does not give medical advice, diagnosis or treatment.**

- Reference ranges shown next to a measurement — including blood-pressure
  categories — are for orientation only and are not a diagnosis.
- Safety information shown for a medication is reproduced from the US FDA label,
  unedited. It is the manufacturer's text, not ours, and may not reflect the
  product dispensed to you.
- **Medly does not check your medications against each other.** It performs no
  drug-interaction checking of any kind. Ask a pharmacist or doctor about
  combinations.
- Symptom patterns count what you recorded. They show co-occurrence, not cause.

**Never start, stop or change how you take a medication based on this app.** Talk
to a qualified healthcare professional.

### 4. Reminders are best effort

Medly schedules reminders using the alarm facilities Android provides, and takes
considerable care to make them survive restarts, battery saving and device
sleep. Even so, delivery depends on your device, its manufacturer's power
management, and settings outside the app's control.

**Do not rely on Medly as the sole safeguard for a medication that is critical to
your health.** You remain responsible for taking your medication.

### 5. Your content

Anything you enter — medications, doses, measurements, notes, symptoms, profile
names — remains yours. We claim no ownership of it. You are responsible for its
accuracy, and for having the right to record information about anyone other than
yourself whose medication you track.

### 6. Advertising

The app is funded by advertising. Advertisements are supplied by third parties
and their content is not endorsed by us. Advertisements are never placed in a way
that interferes with logging a dose.

### 7. Availability

The app is provided "as is" and "as available". Features may change or be
discontinued, and the app may not be available in every territory.

### 8. Limitation of liability

To the fullest extent permitted by law, Umesh Ghimire shall not be liable for any
indirect, incidental, special, or consequential damages arising from your use of
Medly, including any missed, late or duplicated dose. Nothing in these terms
limits liability that cannot be limited under applicable law, including liability
for death or personal injury caused by negligence, or for fraud.

### 9. Governing law

These terms are governed by the laws of Nepal, without regard to conflict of law
principles.

### 10. Contact

**Umesh Ghimire** — me.umeshuser@gmail.com
