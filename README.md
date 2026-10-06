# RideRent — React prototype

A 7-page functional prototype for the DAM2 0492 Projecte intermodular Challenge 1. It implements the supplied RideRent requirements with localStorage-backed demo data so it works without a backend.

## Pages (7 core screens)
1. Home / dashboard
2. Login
3. Register
4. Rent a car / search & filters
5. Car details / reservation
6. My reservations
7. Shared rides (search & join)

Additional workflow routes: `/create-ride` for RF-07 and `/admin` for RF-10. They reuse the same navigation and do not change the 7 core screens.

## Demo accounts
- Customer: `demo@riderent.app` / `demo123`
- Administrator: `admin@riderent.app` / `admin123`

## Requirements covered
RF-01 registration, RF-02 login/session, RF-03 car search/filter, RF-04 car details, RF-05 reservation, RF-06 reservation management/cancellation, RF-07 create shared ride, RF-08 search rides, RF-09 join rides, RF-10 administrator vehicle management.

The UI is responsive, keyboard-friendly, uses labelled forms and validation, and keeps protected pages behind authentication. This is a front-end prototype: real production password hashing, server-side sessions, HTTPS, database persistence and payment processing require a backend and are intentionally not simulated as secure production mechanisms.

## Run
```bash
npm install
npm run dev
```
Then open the Vite URL shown in the terminal.

## Notes for submission
The assignment asks for React, GitHub, Penpot, UML/ER diagrams, Scrum planning and documentation in addition to the working app. This package focuses on the requested working website and maps the UI to the supplied functional requirements.
