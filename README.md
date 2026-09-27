# Deutsch C1 Plan

A web application designed to help me reach German C1 through a flexible and measurable long-term study plan.

The application tracks progress toward a configurable study-hour goal and target date. By default, the plan is set to 600 study hours by December 31, 2027.

Instead of requiring a fixed amount of study time every day, the application dynamically calculates a recommended daily study time based on:

- Remaining study hours
- Remaining days until the target date
- Previous study progress

Studying more than the daily recommendation reduces future recommendations, while days without study are automatically redistributed across the remaining time.

## Features

- Dynamic daily study recommendations
- Study progress tracking
- Integrated study timer
- Manual study-time entries
- Weekly study summary
- Study history
- Individual history entry deletion
- Configurable study goal and target date
- Google authentication
- Cloud synchronization across devices
- Responsive design for desktop and mobile

## Technologies

- HTML
- CSS
- JavaScript
- Firebase Authentication
- Cloud Firestore
- Firebase App Check
- Firebase Hosting
- GitHub

## Security & Data

User study data is stored in Cloud Firestore and associated with each authenticated Google account.

The project uses:

- Firestore Security Rules for user-level data isolation
- Firebase App Check
- Restricted Google API configuration
- Per-user local storage
- Google Authentication

## Development

I designed the application requirements, study-tracking logic, user experience, and interface, and implemented the project using AI-assisted development.

I configured and manage the Firebase infrastructure, including authentication, Firestore, security rules, App Check, hosting, and deployment.

AI tools were used as part of the development process for code generation, debugging, and implementation assistance.
