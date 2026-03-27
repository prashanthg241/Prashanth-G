# Prashanth-G
MongoDB is a popular, open-source NoSQL database designed for flexibility and scalability, storing data in JSON-like documents rather than rigid tables. It is ideal for modern applications requiring rapid development, high-volume data, and horizontal scaling via sharding. MongoDB Database Project

This repository contains sample documents and operations for a MongoDB database created using MongoDB.

 Project Structure
/project-folder
│── README.md
│── database/
│   ├── sample_documents.json
│   ├── queries.txt
│── scripts/
│   ├── insert.js
│   ├── update.js
│   ├── delete.js
 Description

This project demonstrates basic CRUD operations in MongoDB:

Create (Insert documents):<img width="1189" height="766" alt="Screenshot 2026-03-27 130752" src="https://github.com/user-attachments/assets/fdb3150e-c831-4392-bb8f-9f4964bd5cb7" />

Read (Fetch documents):<img width="1189" height="766" alt="Screenshot 2026-03-27 130752" src="https://github.com/user-attachments/assets/e21a0173-3e85-490e-8527-c70efb2953d9" />

Update (Modify documents):<img width="742" height="858" alt="Screenshot 2026-03-27 130833" src="https://github.com/user-attachments/assets/f3a0e322-5918-49fa-bad0-fa9f7a0f0b38" />

Delete (Remove documents):<img width="742" height="858" alt="Screenshot 2026-03-27 130833" src="https://github.com/user-attachments/assets/a439d600-ab84-4bf4-b7e5-84f2659ae88c" />
drop :<img width="564" height="207" alt="Screenshot 2026-03-27 130846" src="https://github.com/user-attachments/assets/a938c8cd-3b9b-4cce-93bb-5ab63d3126d2" />

 Sample Document
{
  "name": "John Doe",
  "age": 25,
  "department": "Computer Science",
  "booksIssued": ["DBMS", "OS"]
}
 How to Use
Start MongoDB server:
mongod
Open MongoDB shell:
mongo
Create or switch database:
use libraryDB
Insert document:
db.users.insertOne({
  name: "John Doe",
  age: 25,
  department: "CSE"
})
View documents:
db.users.find()
 CRUD Operations
➤ Insert
db.collection.insertOne({})
➤ Find
db.collection.find()
➤ Update
db.collection.updateOne({}, {$set: {}})
➤ Delete
db.collection.deleteOne({})
 Notes
This project is for learning purposes.
You can modify the schema based on your use case.
Works with MongoDB Compass and Mongo Shell.
 Author:
 -your name:Prashanth G

Your Name

If you want, I can make it more professional (with badges, screenshots, deployment, API explanation) or customize it specifically for your hotel grocery project.
