# Online-Pizza-Ordering-System
The Online Pizza Ordering System is a comprehensive and user-friendly platform designed to simplify the process of ordering pizzas for home delivery. The system provides a seamless experience for customers, from browsing the menu to placing orders and making payments. This project leverages Java programming, advanced data structures, and efficient algorithms to ensure a robust and efficient solution.

Key Features
View Menu: Customers can easily explore various pizza options by browsing through an interactive menu card.

Place Order: Customers can select their desired pizzas and proceed to place orders for home delivery with a few simple clicks.

Enter Personal Details and Delivery Location: During the ordering process, customers need to provide their personal details and delivery location for order fulfillment.

Automatic Retrieval of Registered Customer Details: If a customer's mobile number is already registered with the shop, their details are automatically fetched. Customers can choose to use the registered address or enter a new one, adding to the convenience.

Shortest Path Calculation: The system calculates the shortest path to the customer’s location using Dijkstra's Shortest Path Algorithm. This distance is saved for efficient delivery planning.

Estimated Delivery Time and Charges: Based on the calculated shortest distance, the system provides an estimated delivery time and charges, which are then displayed to the customer.

Total Bill Amount Calculation: The system dynamically calculates the total bill amount by adding delivery charges to the cost of the ordered pizzas, providing transparency to the customer.

Order Confirmation and Payment: Customers can confirm their orders and proceed with the payment. There is also an option to cancel the order if needed.

Technical Details
Programming Language: Java
Data Structures: Graph, HashMap, Set, ArrayList
Algorithms Used: Dijkstra's Shortest Path Algorithm

How It Works
Menu Browsing: Users can view the pizza menu, which is dynamically loaded from the database.
Order Placement: Users select pizzas and enter delivery details. The system checks if the user's mobile number is registered and retrieves their details if available.
Path Calculation: The shortest delivery path is calculated using Dijkstra's Algorithm to optimize delivery routes.
Cost Calculation: The system calculates delivery charges based on distance and combines them with the pizza cost to provide a total bill amount.
Order Processing: Users confirm their order and proceed to payment. The system handles order confirmation and updates the database accordingly.

Advantages
User-Friendly Interface: Intuitive and easy-to-navigate interface for a better user experience.
Efficient Delivery Planning: Optimized delivery routes ensure faster and more efficient deliveries.
Automatic Customer Detail Retrieval: Simplifies the ordering process for returning customers.
Accurate Cost Calculation: Provides customers with a transparent breakdown of costs.

Conclusion
The Online Pizza Ordering System is designed to enhance the customer experience by providing a convenient and efficient way to order pizzas for home delivery. By leveraging advanced algorithms and data structures, the system ensures optimal performance and reliability.

This project can be further extended to include features such as real-time order tracking, customer feedback integration, and promotional offers to enhance the functionality and user experience.
