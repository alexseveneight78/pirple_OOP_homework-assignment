# pirple_OOP_homework-assignment

OOP is a programming that works with real objects in a real world and pretends to reflect them and its relations using object oriented method. OOP pattern is the best choice when it is intended to describe a system of hierarchical relationships with all complexity of restrictions and levels of access.
A good example of project an application for a car repair. We can have different services depending on the type of car (regular, sport, bysiness class).

```
class Car{
  make,
  model,
  color,
  year,
  plate,
  deadline,
  getServices()
}

class RegularCar extends Car {
  services [
    "RegularRepair",
    "UrgentRepair",
    "SuperUrgentRepair"
  ]
}

class SportCar extends Car {
    "RegularRepairSport",
    "UrgentRepairSport",
    "SuperUrgentRepairSport"
}

class BusinessCar extends Car {
    "RegularRepairBusiness",
    "UrgentRepairBusiness",
    "SuperUrgentRepairBusiness"
}

class Repair {
  car,
  selectedServices [],
  addCar(make, model, color, year, plate. deadline)
  addService(serviceType)
}
