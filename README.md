# PawTrack Malaysia

Mobile-first installable prototype for pet health and care tracking.

## Run locally

```bash
python3 -m http.server 8080 --directory pawtrack
```

Open `http://localhost:8080`.

## Included in prototype

- Add and switch between pets
- Add, change, or remove a compressed pet profile photo (stored locally in the browser)
- Upcoming flea prevention, vaccination, and weight records
- Add vaccination, flea prevention, deworming, medication, vet, weight, and symptom records
- Optional next-due dates with automatic due labels
- Local persistence using `localStorage`
- Chinese, English, and Bahasa Malaysia UI
- Offline cache and installable PWA manifest
- Edit/delete health records, reminders, nearby-vet search, daily tips, dark mode, and printable vet summary
- Four-tab mobile navigation with a health dashboard and weight trend chart
- Repeating medication schedules with calendar reminders
- Local medical file storage for vaccine cards, lab results, prescriptions, and PDFs
- Full local backup and restore, including pet photos and medical files

## Roadmap

### Next: testing and reliability

- Test photo storage, reminders, and health records with early users
- Improve backup/export so users can move their data to another device
- Prepare the product and privacy flow for pilot veterinary partners

### Later: PawTrack community

- Optional user accounts and pet posts
- Photo feed with likes and comments
- Report, block, privacy, moderation, and community-safety controls
- Cloud database and image storage, with costs reviewed before enabling any paid service

The community feature is intentionally deferred until the core health tracker is stable and the privacy, moderation, and operating-cost requirements are ready.

### Future exploration: pet location

- Explore AirTag / Apple Find My-compatible pet location experiences
- Evaluate Android-compatible trackers and cross-platform alternatives
- Confirm platform permissions, owner consent, location privacy, battery expectations, and technical feasibility before development

Location tracking is a long-term research item, not a committed feature. No paid hardware or service will be selected without reviewing the cost first.
