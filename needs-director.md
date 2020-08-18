# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: A system issuing Entry card for all visitors
  When : Patient arrives in the hospital
  Then : Compute daily count and display dashboard

Scenario: Compute parking slots to reserve for visiting specialists

  Given : Hospital staff has preplanned and scheduled the visit  
  When  : Specialist doctor arrives
  Then  : Facility guides doctor allocated free slot
