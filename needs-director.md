# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

Given - Entry-card issuer as Sensor is working efficiently

When - A new patient enters in the hospital

Then - Issue a patient entry-card to the patient and
increment patient-count for that day

## Scenario: Compute parking slots to reserve for visiting specialists

Given - A schedule for specialists visiting

When - we know a specialist is visiting on
that day

Then - Reserve a parking slot for the specialist
