# Cab-Booking-Application
This is a basic, fully functional Cab Booking Application made using the Java Swing API.

## Contributors
1. Pranith S Kallakuri (Username: [pranithkallakuri](https://github.com/pranithkallakuri))
2. Nitin Gopala Krishna Sontineni (Username: [nitin-sontineni](https://github.com/nitin-sontineni))
3. Dantuluri Sairaju (Username: [sairaju2001](https://github.com/sairaju2001))
4. Maneesh Babu Jasti (Username: [Maneesh28](https://github.com/Maneesh28))<br /><br />
   -- students of BITS Pilani, Hyderabad Campus


#### Note: This software was not developed using github or git, therefore everyone's contributions and commits are not recorded. This repo serves only as a host for the code of our project.

## How to run the program
1. Make sure your PC has jdk 8 or higher.
2. Download this Repository, and extract.
3. Now open your extracted directory in the Command Prompt or your OS's respective terminal.
4. In the terminal, run the following commands in the specified order.
   1. `javac *.java`
   2. `cd cabops`
   3. `javac *.java`
   4. `cd ..`
   5. `cd database`
   6. `javac *.java`
   7. `cd ..`
   8. `java Driver`
5. You will see the login screen pop up. Follow the instructions present on the screen.
<br />

## Brief Description of the Application
This Online Cab Booking project deals with an online application designed for booking cabs as
per the requirements of the customers at their convenience. The customer side of the application
should have the ability to:

* Register as a new user with information such as user name, a user id (unique across the
system), phone number, and email id.
* An existing customer should log in into the system with user id and password.
* A customer has options to book a cab by entering details like pick-up point and drop-off
point.
* After the customer has requested a cab, the cab driver located nearest to the customer
will be assigned to him/her and a booking confirmation containing the details of the driver
like name, phone number and rating will be shown to the customer. Also, the estimated
fare and an approximate duration of the trip will be displayed to the customer.
* If more than one driver gets matched with a customer, then the driver with the maximum
rating will be assigned to the customer.
* A request timed out message will be shown to the customer if there are no drivers
available.
* Once the trip is complete the necessary money will be deducted from the customer’s
wallet. A wallet is associated with a customer that contains money that the customer can
use to pay for his/her ride. Here, it is assumed that a customer’s digital wallet associated
with the cab booking portal is the only acceptable mode of payment.
* There should also be an option to add more money to the digital wallet.
* A customer will have to maintain a minimum of 300 INR for making a booking request. If
the balance in the wallet is not sufficient, then the customer will have to first add money to
the wallet and then proceed with the booking.

Assume a set of location points which can be either a pickup point or a drop-off point for a
customer. Every location point may contain a set of customers C and a set of cab drivers D. The
set C and/or D can be empty for a location. Customers and drivers can be located only at these
pre-defined location points. Once a trip is booked both the driver and the user will be busy for the
duration of the trip and will not participate in any booking. The application should be able to
support multiple customers simultaneously.
