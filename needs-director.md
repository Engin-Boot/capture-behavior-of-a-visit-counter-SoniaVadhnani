# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

Given - Entry-card issuer as Sensor

When - Any new patient card is issued

Then - Increment the patient count that day

## Scenario: Compute parking slots to reserve for visiting specialists

Given - Entry-card issuer as Sensor

When - Any new specialist card is issued

Then - Increment the specialist count that day
