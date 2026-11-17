# ClinicQ – Appointments and daily care

ClinicQ is a single-page health care web app. It helps a person book clinic visits and look after their daily health in one place. It was built as a college assignment on the topic of health care.

**Live site:** `https://YOUR-USERNAME.github.io/clinicq/`

## Features

- **Home** – a daily dashboard with a water tracker (tap a glass for each one you drink), a health tip, and your emergency details.
- **Book visit** – choose a doctor, see their speciality, experience and availability, then pick a free time slot and confirm.
- **My visits** – see your booked appointments and cancel any of them.
- **Medicines** – add your medicines with dose and time, and mark each one as taken for the day.
- **Vitals** – log blood pressure, blood sugar and pulse, and view a systolic blood pressure trend chart.
- **Profile** – save your name, age, blood group, allergies and an emergency contact.
- **BMI check** – enter height and weight to calculate your BMI.
- **Ask AI** – a care helper that gives general health information. It only works inside Claude (see the note below).
- Light and dark themes, and a layout that works on phones and desktops.

## Doctors in the demo

| Doctor | Speciality | Available |
|---|---|---|
| Dr. Priya Nair | General physician | Mon–Sat |
| Dr. Arun Kumar | Pediatrician | Mon–Fri |
| Dr. Fatima Sheikh | Dermatologist | Tue, Thu, Sat |
| Dr. Suresh Babu | Orthopedic | Mon, Wed, Fri |

These doctors and all the data in the app are made up for demonstration.

## Tech used

- HTML, CSS and plain JavaScript in one file (`index.html`), with no framework and no build step
- Google Fonts: Sora and Figtree
- Browser `localStorage` to save your data on your own device

## How to run it

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

You can also host it for free with GitHub Pages: **Settings → Pages → Deploy from a branch → main → / (root)**.

## Notes and limits

- **Your data stays on your device.** Everything is saved in your browser, so it is not shared between devices. Clearing your browser data removes it.
- **The Ask AI tab does not work on GitHub Pages.** It depends on Claude's built-in helper, which is only available when the page is opened on claude.ai. On GitHub Pages it will show a message that the helper couldn't answer. All the other features work normally.
- **This is a demo, not a medical service.** The bookings are not sent to a real clinic. The BMI result and the AI helper give general information only and are not medical advice. In an emergency, call your local emergency number.

## Project structure

```
clinicq/
├── index.html   # the whole app
└── README.md    # this file
```

## Author

Made by YOUR NAME for a college assignment.
