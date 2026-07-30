# awscasestudy- https://youtu.be/-8WUxNZJdxs
1. Create a technical solution for a case study application to schedule an appointment for Vehicle Services and Repairs with local Dealership
   a) Customers can use a web app to find the nearest Dealership based on ZIP Code and select from an available list of Dealers
   b) Customers can choose to create an account or can choose to schedule an Appointment without login
   c) Regardless of login or not customers can choose to enter VIN # to select specific services for that Vehicle
   d) Customers can choose to schedule an Appointment without entering a VIN also
   e) If the Customers have entered a VIN or have previously saved a VIN with their Customer Account the web app should allow them to select services specific to that Vehicle
   f) Customers should be allowed to select an appointment date/time based on what is available for the selected Dealership
   g) The system should send the Customer an appointment confirmation and a reminder via email and/or SMS based on Customer preferences

2. Following non-functional requirements must be considered for the solution architecture
   a) Assume an existing on-prem API is available for looking up Vehicle details given a VIN
   b) Assume Vehicle repair history needs to be obtained via a brand new integration with a mainframe system
   c) Assume customer history from one Dealership can not be made visible for personnel from other Dealerships
   d) Any solution created for finding out available time slots at a given Dealership needs to work across all 2500+ dealer locations across North America
   e) Assume each Dealership will own their backend system for maintaining available time slots at their local dealerships
   c) Assume all dealerships are open in their local time zone 6 days a week and 10 hours per day and assume can schedule an appointment 24/7 from wherever
   d) Assume millions of customers and millions of Vehicle records and millions of appointments per year
   e) Any solution created for the Customer facing user interface has to work in all the major browsers including browsers running on mobile devices
