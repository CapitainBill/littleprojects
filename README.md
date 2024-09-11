# 
**GERMAN BELOW**

# Audio Participation Project


Welcome to the Audio Participation Project! This is a web-based application I designed to facilitate citizen participation in urban planning by allowing users to submit voice opinions through audio recordings on various development plans.

## Project Overview

This application allows users to:

- View urban planning projects and submit their voice opinions.
- Admins can manage these projects and respond to the submitted opinions.
- Users can also check the status of their submitted opinions.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Django REST Framework
- **Database**: SQLite (for development)
- **Testing Frameworks**: Cypress
## Testing Focus

### Goal

My primary goal with this project is to carry out simple end-to-end (E2E) tests using different technologies, such as Cypress and Playwright. I have also written API tests for user authentication using Postman and integrated them into the project.

### 1. Cypress E2E Tests (POM Model)

I have implemented Cypress E2E tests using the Page Object Model (POM) to ensure clean, maintainable, and reusable test code. These tests cover essential user flows, including:

- User login, logout, and registration.
- Navigating the dashboard.
- Submitting and managing opinions.
- Admin actions like replying to opinions.

### 2. Playwright Tests

In addition to Cypress, I use Playwright for cross-browser testing. Playwright ensures that the application functions correctly across different browsers, adding robustness to the testing process and ensuring a consistent user experience.

### 3. API Tests with Postman

I have also written two API tests for user authentication using Postman. These tests verify that the authentication endpoints work correctly, and I have exported the Postman collection into the project repository for easy integration and reuse.



## Project Structure

- **`audio-participation-frontend/`**: Contains the React frontend code.
- **`audio_participation_backend/`**: Contains the Django backend code.
- **`cypress/`**: Contains Cypress tests and configuration files (POM model).




Willkommen zum Audio-Teilnahme-Projekt! Dies ist eine webbasierte Anwendung, die ich entwickelt habe, um die Bürgerbeteiligung an der Stadtplanung zu erleichtern, indem Nutzer ihre Meinungen durch Audioaufnahmen zu verschiedenen Entwicklungsplänen einreichen können.

Projektübersicht
Diese Anwendung ermöglicht es den Nutzern:

Stadtplanungsprojekte anzusehen und ihre Meinungen als Sprachnachrichten einzureichen.
Administratoren können diese Projekte verwalten und auf die eingereichten Meinungen antworten.
Nutzer können auch den Status ihrer eingereichten Meinungen überprüfen.
Verwendete Technologien
Frontend: React.js
Backend: Django REST Framework
Datenbank: SQLite (für die Entwicklung)
Testframeworks: Cypress, Playwright, Postman
CI/CD: GitHub Actions
Testfokus
Ziel
Mein Hauptziel bei diesem Projekt ist es, einfache End-to-End-Tests (E2E) mit verschiedenen Technologien wie Cypress und Playwright durchzuführen. Ich habe außerdem API-Tests für die Benutzerauthentifizierung mit Postman erstellt und diese in das Projekt integriert.

1. Cypress E2E-Tests (POM-Modell)
Ich habe Cypress E2E-Tests unter Verwendung des Page Object Models (POM) implementiert, um sauberen, wartbaren und wiederverwendbaren Testcode zu gewährleisten. Diese Tests decken wichtige Nutzerabläufe ab, darunter:

Benutzeranmeldung, -abmeldung und -registrierung.
Navigation im Dashboard.
Einreichen und Verwalten von Meinungen.
Administratoraktionen wie das Beantworten von Meinungen.


Projektstruktur
audio-participation-frontend/: Enthält den React-Frontend-Code.
audio_participation_backend/: Enthält den Django-Backend-Code.
cypress/: Enthält Cypress-Tests und Konfigurationsdateien (POM-Modell).


