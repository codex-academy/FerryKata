---
layout: default
---

# Part 1

In an island country far far away there are lots of Ferries that allow people to travel by car between all the different islands of this country.

This country's government would like to control the number of cars and people that can get onto a Ferry.

To help them they need you to:

* Create a `Car` class: the constructor should specify the **colour** and  the **number of passengers** in the car.

* Create a `Ferry` class: the constructor should specify the **number of cars** allowed on the ferry and also **how many people** are allowed on the ferry.

Cars are allowed onto the Ferry using the `board` method. If the ferry is not full yet the `board` method returns 'accepted'. If there are enough people or cars on the Ferry already, the `board` method should return 'rejected'.

The Ferry class instance should keep track of the number of people and cars on the Ferry using the `people_count` and `car_count` properties.
