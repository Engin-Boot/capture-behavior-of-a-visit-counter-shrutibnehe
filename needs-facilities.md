# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given :The card issuer system is up and running
  When  :Facility manager asks weekly report
  Then  :Compute average of patients,relatives,doctors in week and display

Scenario: Alert when seating capacity is full

  Given : A system with a footfall sensor working
  When  : When visitors present in the hospital reaches maximum
  Then  : Alert the facility manager
