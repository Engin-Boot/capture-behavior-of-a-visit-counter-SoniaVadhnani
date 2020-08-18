# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

Given - Entry-card issuer as Sensor

When - Issue a new patient card to the patient

Then - Increment the patient count that day

## Scenario: Compute parking slots to reserve for visiting specialists

Given - Entry-card issuer as Sensor

When - Issue a new Specialist card to the specialist

Then - Increment the specialist count that day
