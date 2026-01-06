# MongoDB Checkpoint – CRUD Operations

## 📌 Project Overview
This project demonstrates basic **MongoDB CRUD operations** using the MongoDB shell (`mongosh`).  
The objective is to create a database, manipulate documents, and perform queries based on given conditions.

---

## 🗄️ Database Details
- **Database Name:** `contact`
- **Collection Name:** `contactlist`

---

## 📝 Documents Inserted
The following documents were inserted into the `contactlist` collection:

- Ben Moris – age 26 – ben@gmail.com  
- Kefi Seif – age 15 – kefi@gmail.com  
- Emilie brouge – age 40 – emilie.b@gmail.com  
- Alex brown – age 4  
- Denzel Washington – age 3  

---

## ⚙️ Operations Performed

### ✅ Create
- Created a database named `contact`
- Created a collection named `contactlist`
- Inserted multiple documents into the collection

### ✅ Read
- Displayed all contacts
- Displayed one contact using `_id`
- Displayed contacts with age greater than 18
- Displayed contacts with age greater than 18 and first name containing `"ah"`

### ✅ Update
- Updated the first name of **Kefi Seif** to **Kefi Anis**

### ✅ Delete
- Deleted contacts with age less than 5

---

## 🖼️ Screenshots
All required screenshots showing each step and MongoDB command execution are included in the **`screenshots/`** folder as proof of work.

---

## 🛠️ Tools Used
- MongoDB Community Edition
- MongoDB Shell (`mongosh`)
- Ubuntu Linux
- Git & GitHub

---

## 📂 Project Structure
checkpoint-mongodb/
├── screenshots/
│ ├── 01-mongosh.png
│ ├── 02-use-db.png
│ ├── 03-create-collection.png
│ ├── 04-insert.png
│ ├── 05-find-all.png
│ ├── 06-find-id.png
│ ├── 07-age-gt-18.png
│ ├── 08-age-gt-18-ah.png
│ ├── 09-update.png
│ ├── 10-delete.png
│ └── 11-final.png
└── README.md

## 🚀 Author
**Nelson Ngumo**

MongoDB Checkpoint Submission
