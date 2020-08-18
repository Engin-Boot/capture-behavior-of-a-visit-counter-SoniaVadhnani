# Visit-counter technical needs

## Scenario: Recover across restarts of the server that runs the visit-counter

Given - Sensor is working efficiently

When - the server restarts

Then - it continues with the previous visitor-count

## Scenario: Reconcile counts if the sensor is offline for a while

Given - Sensor is working efficiently

When - the server is offline

Then - someone counts the visitor and adds
the number to previous count at server and
update the server manually.
