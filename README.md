# Tourism-Management-System
Java Core Project using Swing and AWT.

This project focus on automating travel and tourism management for customers. It manages the details of customers, booking packages, booking hotels and payment. A new customer has to first register oneself with the application by entering personal details and by choosing a username and password. Changes to these details can be made by the user at any time. The customers can then check and book packages from a list of available options by entering  details like the number of people traveling. The total cost of the booked package will be displayed post booking. The next important functionality offered is booking hotels. Similar to booking packages, customers can check different hotels, add options and check the total amount the hotel booking sums upto before confirming the booking. Once the package and hotels are booked, the customer proceeds to payment using PayPal.


Tools and Frameworks Used: 
a) Framework used - Java Swing and AWT
b) IDE - Netbeans 
c) Language - Java Core
d) Database used - Mysql


Design Principles and Design Patterns Applied:
	SOLID principles are a set of design principles that reduces the coupling between classes. This project strictly follows the Single Class, Single Responsibility principle of the SOLID principles. For example, the DeleteCustomer.java class is responsible only for deleting customer’s details from database. Open closed principle has also been used. Here, Login extends JFrame. Login class inherits properties from java.awt.Frame class.  
