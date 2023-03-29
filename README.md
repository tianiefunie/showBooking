# Show Booking Spring Boot Application

To start the application, an environment variable has to be include -> start.enabled=true

Commands for the application is as follows:

- Admin
  - Setup [show number] [number of rows] [number of seats per row] [cancellation window period]
  - View [show number]
  - Add [show number] [number of rows] [number of seats per row]
- Buyer
  - Availability [show number]
  - Book [show number] [phone number] [seats desired separated by comma]
  - Cancel [ticket number] [phone number]
  
Please note to start every command with capital as they are case sensitive, and ensure spaces between each argument passed in. 
 
Assumptions:
Phone number does not have to be a valid one.
Seats desired are only having 2 characters max, where first character with alphabets and second one is an integer from 0-9.
Ticket numbers generated will always be unique using UUID
There will be no removal of rows/seats once the show has been configured at the start. You can only add but not remove. 

