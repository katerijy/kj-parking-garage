Welcome to KJ Garage by Kateri and John

In this project, we conceptualized by addressing what sort of needs a visitor may have and related it back to a "KJGarage" class that would actuate the various needs of a user such as to enter, pay and exit our garage.

Kateri built out a framework, John fleshed out many of the bugs and the formatting with Kateri's input, and we finalized the project together! 

As the user enters the garage, they are greeted with a home screen (the "home" method) that gives 3 options: Take a ticket, pay or leave. The system will relate the response and move on to one of three methods: "takeTicket", "payForTicket", and "leaveGarage".

The "takeTicket" method assigns entering cars with a ticket number and updates the "current_ticket" dictionary--which allows the system to track 1) whether a parking space is in use and, 2) whether a ticket has been paid for--from “free” to “taken” for the ticket number, as well as reduces the ticket_count by one. If the parking garage has reached maximum capacity (10 cars), the "takeTicket" method prints a message indicating the garage is full.

We needed to include a payment system for the tickets which also tracked whether a ticket in use had been paid for. The "payForTicket" method initiates with two user inputs, which results in updating the "current_ticket" dictionary to indicate that a specified ticket has been paid for. We added some user error messages for scenarios such as not paying a sufficient amount, or entering a ticket number that does not exist/is not in use.

User input to “leave” initiates the "leaveGarage" method, which checks whether the ticket has been paid for. Once it has been paid, it prints confirmation of completing the visit and updates the ticket number in the "current_ticket" dictionary to make the parking space/ticket available for the next visitor.

Happy parking!
