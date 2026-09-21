# MediNexus
AI-based vaccination tracking and medicine management system

MediNexus is an AI-assisted healthcare management system designed to help individuals and families manage vaccination records and prescription-based medicines through a centralized digital platform.The system supports age-based vaccination schedule tracking, OCR-based vaccine card digitization, AI-assisted identification of potentially due or missed vaccinations, and medicine schedule management based on valid prescriptions.
## Problem Statement

Individuals and families often struggle to maintain vaccination records, remember age-specific vaccine schedules, and identify missed doses. Managing paper vaccination cards and prescribed medicines manually can cause errors and missed timings. This creates a need for an organized digital healthcare management system for vaccination and prescription-based medicine tracking.
## Objectives

- Maintain digital vaccination records.
- Track age-based vaccination schedules.
- Digitize vaccination cards using OCR technology.
- Identify potentially due or missed vaccine doses.
- Provide AI-assisted vaccination information.
- Manage prescription-based medicine schedules.
- Send vaccination and medicine reminders.
- Support vaccination and medicine tracking for family members.
- Provide a user-friendly healthcare dashboard.
## Key Features

### Vaccination Management
- User registration and login.
- Age/DOB-based vaccination schedule.
- Vaccine information and purpose.
- Vaccination history.
- Upcoming and potentially missed vaccine tracking.
- Family member vaccination records.

### OCR Vaccine Card
- Upload vaccination card images.
- Extract text using OCR technology.
- Extract vaccine names and vaccination dates where readable.
- Allow users to verify and edit extracted information.
- Store verified records in the database.

### AI-Assisted Vaccination Analysis
- Compare vaccination history with the configured vaccination schedule.
- Identify potentially due or missed doses.
- Provide vaccination information and catch-up discussion prompts.
- Use healthcare professional guidance for medical decisions.

### Prescription-Based Medicine Management
- Upload or enter prescription details.
- Maintain prescribed medicine information.
- Record dosage, frequency, and duration.
- Create medicine schedules.
- Track medicine history.
- Provide medicine reminders.

### Reminder System
- Vaccination reminders.
- Medicine schedule reminders.
- Upcoming task notifications.

### Dashboard
- Completed vaccinations.
- Upcoming vaccinations.
- Potentially missed vaccinations.
- Active medicines.
- Family health records.

## 🛠️ Technology Stack
Technology                      -      Purpose

React.js                        -       Frontend development
Node.js                         -      Backend runtime
Express.js                      -      Backend API development
Firebase Authentication         -      User authentication
Firebase Firestore              -      Database
Firebase Storage                -      Document and image storage
Python                          -      OCR and AI services
EasyOCR / Tesseract             -      Text extraction
Google Maps API (Optional)      -      Healthcare center location
Git & GitHub                    -      0 Version control
