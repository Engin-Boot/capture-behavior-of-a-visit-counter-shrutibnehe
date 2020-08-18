# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given : System(sensor) is running 
  When  : Server restarts
  Then  : Alert the technical team and store last visit count

Scenario: Reconcile counts if the sensor is offline for a while

  Given :Footfall sensor is up and running
  When  :Sensor goes offline
  Then  :Store last count,issue cards when offline and take sum of both   
