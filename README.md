📚 Library Management System (MongoDB)
This project is a simple Library Management System created for learning MongoDB.
It includes collections for managing books, members, and issue records with basic CRUD operations.
✨ Features
Add new books
Add new members
Issue books
Return books
Update book or member data
Delete records
View all books / members / issued books
🗂️ Collections Used
1. books
Fields:
bookId
title
author
category
availableCopies
2. members
Fields:
memberId
name
class (optional)
phone
3. issuedBooks
Fields:
issueId
bookId
memberId
issueDate
returnDate
🛠️ MongoDB Operations Used
insertOne()
insertMany()
find()
projection
updateOne()
$set
deleteOne()
sort()
limit()
skip()
📌 Purpose
This project was created to understand:
How MongoDB collections work
How to connect different collections
How to perform CRUD operations
How to design a small real-life database.

Shruti Sharma
Learning Databases & MongoDB
