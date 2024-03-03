# Database-design-AWS
Design a database schema for a specific business scenario and populate your database with sample data in AWS.

Our business scenario is: Online Bookstore. For this project, we'll design a database for an online bookstore. This bookstore will manage information about books, authors, customers, and orders.

To design the schema, we'll use BrModelo. This software, BrModelo, is designed primarily for creating and managing database models.

Once the schema is created, we have to create the database in AWS. We'll use Amazon RDS with PostgreSQL by following these steps:
- Log in to your AWS Management Console.
- Navigate to RDS and click "Create database".
- Choose a standard create method, select PostgreSQL as the engine type.
- Configure the DB instance size, storage, and availability & durability according to your needs.
- Set the DB instance identifier, master username, and password.
- Choose the VPC, security group, and database name.
- Launch the instance.

After that, we have to connect to our instance:
- After your instance is available, connect to it using a SQL client like pgAdmin or through the command line.

And finally, create our schema:
- Use SQL commands to create tables based on the schema designed in BrModelo.
