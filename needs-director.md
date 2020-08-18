# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

Given - Sensor as Entry-card issuer is working efficiently

When - A new patient enters in the hospital

Then - Issue a patient entry-card to the patient and
increment patient-count for that day

## Scenario: Compute parking slots to reserve for visiting specialists

Given - A schedule of specialists visiting

When - we know a specialist is visiting on
that day and a parking slot is free

Then - Reserve the parking slot for the specialist
