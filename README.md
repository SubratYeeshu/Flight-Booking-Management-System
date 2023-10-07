# Flight-Booking-Management-System

This parent repo contains link to all the microservices(sub-modules) for this project and describes the overall idea of the project.

## Objective - 

We need to build a backend system that can support different features for an airline company. Our end user is going to be someone who wants to book flights and query about flights so we needf a robust system to actually help them give the best experience possible.We want to prepare the whole backend keeping the fact in mind that the code base should be as maintainable as possible. 

## Features - 

* A user should be able to search for flights from one place to another.
    * User should be able to mention the source and destination
    * User should be able to select the date of the journey
    * User should be able to select the no of seats they want to book [Non Mandatory]
    * Now based on the above data, we will list down the flights
    * We should show our users the best available flights at the top based on time period of flight and then based on the price.
    * We need to support pagination so that we can list chunk of flights at one point of time. 
    * We should support filters of flights based on Price, Departure time, Duration, Airline, Stops.
* A user should be able to book a flight considering that user is registered on the platform.
* User should be able to list their previous and upcoming flights
* Notifications via email for completing online check-in before 3 hours of departure.
* User should be able to authenticate to our system using email and password
* While making a booking a person can reserve more than one seats with one login id


