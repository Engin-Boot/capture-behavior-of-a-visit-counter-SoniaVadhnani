# Visit-counter for a Facilities Manager

## Scenario: Report visitor trends during a week of operation

Given - The data of the visitor-count per day
  
When - The week ends or any request is made
regarding weekly data of visitors
  
Then - Compute the average of visitor
count that week and display it.

## Scenario: Alert when seating capacity is full

Given - The number of seats available and
number of visitors entered in the hospital

When - The number of visitors equals the seating capacity

Then - An alert is send tu the facility
manager that seating capacity is full.
