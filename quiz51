
**QUIZ 050** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

50. Create a class for a flight:


　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
**python code**

```.py
from quiz50 import Airline

class Aircraft:
    def __init__(self, model: str, capacity: int):
        self.model = model
        self.capacity = capacity

    def get_info(self):
        return f"{self.model} (Capacity: {self.capacity})"

class Flight(Airline):
    def __init__(self, flight_number: str, origin: str, destination: str, departure_time: str, duration: list[int], aircraft: Aircraft):
        super().__init__(flight_number, origin, destination, departure_time, duration)
        self.aircraft = aircraft

    def get_flight_info(self):
        return f"{super().get_flight_info()} with {self.aircraft.get_info()}"

aircraft = Aircraft("Boeing 777", 550)
print(aircraft.get_info())
flight = Flight("AA123", "JFK", "LAX", "12:00", [5, 30, 0], aircraft)
print(flight.get_flight_info())
```
**proof of work**　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/unit3/blob/main/images/Screenshot%202024-02-19%20at%2008.38.22.png)
