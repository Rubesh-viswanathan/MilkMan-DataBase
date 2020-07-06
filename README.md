Admin
 - Id : (int) Unique identity of the admin
 - Name : (varchar) Name of the admin
 - PhoneNumber : (varchar) Phone number of the admin
 - Password : (varchar) Password for admin login
 - Location : (varchar) Location of the admin

Inventory
 - Id : (int) Unique identity of the inventory
 - QuantityAvailable : (float) Total quantity of milk available
 - QuantityLeft : (float) Total quantity of milk sold

Milk
 - Id : (int) Unique Identity of the milk
 - Price : (float) Price of the milk
 - CreatedAt : (timestamp) The created date and time 
 - Type : (varchar) Type of the milk
 - adminId : (int) Unique identity of the admin who created

Order
 - Id : (int) Unique Identity of the order
 - UserId : (int) Unique identity of the user who ordered
 - AdminId : (int) Unique identity of the admin for whom the order assigned
 - Location : (varchar) Location of the order
 - Price : (float) Total price for the milk ordered
 - Quantity : (float) Quantity of milk ordered
 - Remarks : (varchar) Remarks given by the user
 - OrderedAt : (timestamp) The date and time of the order

User
 - Id : (int) Unique identity of the user
 - Name : (varchar) Name of the user
 - Location : (varchar) Location of the user
 - PhoneNumber : (varchar) Phone number of the user
 - Password : (varchar) Password for the user login

	