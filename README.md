# Nexora Health

An individual MVP project for a clinic staff workflow, focused on the patient → appointment → clinical encounter journey.

## Status

In progress. This repository currently contains the project README; application features will be added in milestone commits.

## MVP scope

- Staff sign-in with administrator, receptionist, and clinician roles
- Minimal patient registration and search
- Appointment creation, rescheduling, and cancellation with clinician-overlap prevention
- Clinical encounter notes and basic vitals linked to appointments

## Role access

- **Administrator:** manages staff accounts and roles; no default patient, appointment, or encounter access
- **Receptionist:** manages clinic appointments; cannot access clinical notes or vitals
- **Clinician:** views assigned appointments and accesses encounters for those appointments

## Technology

- Database: PostgreSQL
- Application and authentication: [enter the approved stack from the proposal]

## Setup and testing

Setup, environment configuration, migrations, synthetic seed data, run instructions, and test commands will be documented here when the application code is added. Never commit secrets or real patient information.

## Security and data

Use synthetic data only. Planned safeguards include role and record-level checks, protected sessions, database constraints, and append-only audit metadata. Do not add real health information to this repository.

## Repository

https://github.com/Robinadev/Nexora-Health-Rihobot
