# Global-Super-Store-Database1
Global Super Store mainly stores data about the orders which have been made by customers. There's information about the order itself such as the customer who made the order, the product requested by the customer and its quantity, the cost which the customer have to pay, and information about shipping. Also, there's information about the customer himself, his name and a detailed address of him. Besides the order and customer information, there's information about the product, its name, category, sub-category, and price.

All those information is stored in ONLY ONE dataset. Th![Physical Data Model](https://github.com/johantbueno/Global-Super-Store-Database1/assets/109690188/c7c48992-880a-44dc-bb03-7bc183686f1b)
is makes the data difficult to monitor, analyze, and extract insights! Therefore we need a structured database to store all those information in a simple and easy-to-monitor format.

Data Modeling
To well-design the database, we start with the Entity Rel![Uploading Physical Data Model.png…]()
ationship Diagram. This methodology requires dividing the information in the dataset into entities, and defining the relationship between them.![Conceptual Data Model](https://github.com/johantbueno/Global-Super-Store-Database1/assets/109690188/8f05ed16-ff0b-4fe2-af24-fd4550c130e8)
![Logical Data Model](https://github.com/johantbueno/Global-Super-Store-Database1/assets/109690188/ee856f20-238c-460e-9788-963d7331eade)


![Uploading Physical Data Model.png…]()



The dataset contains the following entities:

Orders
Customers
Products
Sales
Addresses
Shipping
