# SpringBootProject
Railway Ticket booking 1
A developer is building a Railway Ticket booking system, and you are tasked to assist him in completing the project.

He has shared the project files with you, which contain the prewritten Controller and Service classes. Based on the given template complete the project.

Tasks:-


1. Complete the Ticket entity class with the following attributes and with the required getter and setters method:

    a. long pnr

    b. String name

    c. long age

    d. String birth

2. In the controller class complete the methods to handle HTTP requests with the required annotation for the following APIs:
 
    a. POST "/railway/ticket": It saves a railway ticket.

    b. GET "/railway/ticket/{pnr}": It retrieves a specific ticket through the pnr number.

    c. GET "/railway/tickets": It fetches the list of all tickets.

3. Complete the following method in RailwayService class as mentioned below:

       1. getTicketByPnr(long pnr): This method retrieves a ticket based on its unique PNR from ticketmap.

       2. addTicket(Ticket ticket): This function adds a ticket to a list and associates it with a PNR in a ticket map for efficient retrieval.

       3. getAllTickets(): This function returns a list of all tickets stored in the class.

4. Test the application using Postman.
