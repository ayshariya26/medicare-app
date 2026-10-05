# MediCare 🩺

A mobile app that helps patients stay on top of their medicine schedule, and keeps family members instantly informed if something's wrong — built as a real-world extension of my "AI-Powered Health Monitoring System Using IoT" seminar project.

## Features
- **Patient/Family pairing** — link two phones with a simple 6-digit code, no accounts or logins needed
- **Medicine reminders** — set name, time, meal-timing (before/after meal); real system notifications with sound, even when the app is closed
- **Auto-retry & escalation** — if a reminder isn't marked "taken," it retries twice (10 min apart), then automatically alerts the family member
- **Emergency SOS button** — instant one-tap alert to family, live
- **Live family dashboard** — see medicine taken/missed history and emergency alerts in real time, no refresh needed

## Tech stack
- **Frontend:** HTML, CSS, JavaScript, wrapped into a native Android app with [Capacitor](https://capacitorjs.com/)
- **Backend:** [Firebase Realtime Database](https://firebase.google.com/products/realtime-database) for live data sync between Patient and Family devices
- **Notifications:** Capacitor Local Notifications plugin

## Related project
This app follows the concept from my seminar report and companion website, [VitalWatch](https://ayshariya26.github.io/vitalwatch) ([repo](https://github.com/ayshariya26/vitalwatch)).

## Status
Fully working end-to-end on Android, tested on a real device. iOS build planned once Mac hardware is available.