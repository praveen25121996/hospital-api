# Hospital Backend API
A Server-side API built on NodeJS and MongoDB for hospital doctors to keep track of their patients with Covid19 test reports.

Live

Documentation

Features
An API for the doctors of a Hospital which has been allocated by the govt for testing and quarantine + well being of COVID-19 patients
There can be 2 types of Users
Doctors
Patients
Doctors can log in
Each time a patient visits, the doctor will follow 2 steps
Register the patient in the app (using phone number, if the patient already exists, just return the patient info in the API)
After the checkup, create a Report
Patient Report will have the following fields
Created by doctor
Status [Negative, Travelled-Quarantine, Symptoms-Quarantine, Positive-Admit]
Date
Folder Structure
.
└── src/
    ├── config/
    │   ├── mongoose.js
    │   └── passport-jwt.js
    ├── controllers/
    │   ├── doctor-controller
    │   ├── patient-controller
    │   └── report-controller
    ├── models/
    │   ├── doctor/
    │   ├── patient/
    │   └── report/
    ├── routes/
    │   ├── index
    │   └── api/
    │       └── v1/
    │           ├── index
    │           ├── doctor
    │           ├── patient
    │           └── report
    └── index.js

Screenshots:

image

image

image

image
