Admin
 - Id : Unique identity of the admin
 - Name : Name of the admin
 - PhoneNumber : Phone number of the admin
 - Password : Password for admin login
 - Location : Location of the admin

Inventory
 - Id : Unique identity of the inventory
 - QuantityAvailable : Total quantity of milk available
 - QuantityLeft : Total quantity of milk sold

Milk
 - Id : Unique Identity of the milk
 - Price : Price of the milk
 - CreatedAt : The created date and time 
 - Type : Type of the milk
 - adminId : Unique identity of the admin who created

Order
 - Id : Unique Identity of the order
 - UserId : Unique identity of the user who ordered
 - AdminId : Unique identity of the admin for whom the order assigned
 - Location : Location of the order
 - Price : Total price for the milk ordered
 - Quantity : Quantity of milk ordered
 - Remarks : Remarks given by the user
 - OrderedAt : The date and time of the order

User
 - Id : Unique identity of the user
 - Name : Name of the user
 - Location : Location of the user
 - PhoneNumber : Phone number of the user
 - Password : Password for the user login

	