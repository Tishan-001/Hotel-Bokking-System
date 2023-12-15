## Laravel Hotel Booking System

Laravel Hotel is an open-source web application built with laravel 9.0, enchanced with laravel websockets features to have realtime notification experience.

## TODO:
Customer's Room:

Asks for room to be cleaned
Update room status
Auth id must be == room->customer->id
Send realtime notification to Admin, and food
Room Facility:

Create
Read
Pagination
Search
Update
Delete
User Profile

View
User Activity Log
View:
Paginate
see all
User Settings
Edit Profile
Edit Password
Dashboard

Guests Chart
Get total customer / month
Income Chart for Super only
Get total income / month
Modul
Dashboard

Guests Chart
Guests on this day
Transaction

Payment
Create & Store Payment
Payment History
Room Reservation


Step:
Choose Customer:
Create New Customer / Pick from existing Customer
Input Form:
How many people
Date for Check In
Date for Check Out
Pick Available Room:
Check unoccupied room between date Check in and Check out.
Room Capacity must be > than input how many people.
Confirmation & Down Payment
Down Payment: 15% of total price
Payment must be equal or higher than Down Payment

If the transaction Success:
Update all dashboard view
CUSTOMER Management

Create Customer
Read Customer
Paginate
Search
Update Customer
Delete Customer
Cannot be deleted if the customer has transaction
Customer Detail
USER Management

Create User
Read User (Super, Admin)
Paginate
Search
Read User (Customer)
Paginate
Search
Update User
Delete User
Cannot be deleted if the User has transaction
User Detail
ROOM Management

Create Room
Read Room
Paginate
Search
Update Room
Delete Room
Cannot be deleted if the Room already connected in transaction
Room Detail
CRUD ROOM TYPE

Create Room Type
Read Room Type
Paginate
Search
Update Room Type
Delete Room Type
CRUD ROOM STATUS

Create Room Status
Read Room Status
Paginate
Search
Update Room Status
Delete Room Status

And also auto reply chatbot implement