# MongoDB Checkpoint – CRUD Operations

## 📌 Project Overview
This project demonstrates **MongoDB installation** and **CRUD (Create, Read, Update, Delete) operations** using the MongoDB Shell (`mongosh`).  
The goal is to create a database, manipulate documents, and perform queries based on given conditions.

---

## 🖥️ Environment
- OS: Ubuntu Linux
- Database: MongoDB Community Edition
- Tool: MongoDB Shell (`mongosh`)
- Version: MongoDB 7.0

---

## ⚙️ MongoDB Installation (Step-by-Step)

### Step 1: Update system packages
sudo apt update
Step 2: Install required dependencies
sudo apt install -y gnupg curl

Step 3: Import MongoDB GPG key
curl -fsSL https://pgp.mongodb.com/server-7.0.asc | \
sudo gpg -o /usr/share/keyrings/mongodb-server-7.0.gpg --dearmor

Step 4: Add MongoDB repository
echo "deb [ arch=amd64 signed-by=/usr/share/keyrings/mongodb-server-7.0.gpg ] \
https://repo.mongodb.org/apt/ubuntu jammy/mongodb-org/7.0 multiverse" | \
sudo tee /etc/apt/sources.list.d/mongodb-org-7.0.list


jammy is used for Ubuntu 22.04 and above.

Step 5: Update package list
sudo apt update

Step 6: Install MongoDB

sudo apt install -y mongodb-org

Step 7: Start and enable MongoDB service

sudo systemctl start mongod
sudo systemctl enable mongod

Step 8: Verify MongoDB status
sudo systemctl status mongod


Step 9: Connect to MongoDB Shell
mongosh
🗄️ Database Details
Database Name: contact

Collection Name: contactlist

📝 Documents Inserted
The following documents were inserted into the contactlist collection:

Ben Moris – age 26 – ben@gmail.com

Kefi Seif – age 15 – kefi@gmail.com

Emilie brouge – age 40 – emilie.b@gmail.com

Alex brown – age 4

Denzel Washington – age 3

⚙️ CRUD Operations Performed
✅ Create
Created a database named contact

Created a collection named contactlist

Inserted multiple documents into the collection

✅ Read
Displayed all contacts

Displayed a single contact using _id

Displayed contacts with age greater than 18

Displayed contacts with age greater than 18 and first name containing "ah"

✅ Update
Updated first name from Kefi Seif to Kefi Anis

✅ Delete
Deleted contacts with age less than 5

🖼️ Screenshots
All required screenshots showing:

MongoDB installation

MongoDB service running

CRUD operations execution

are available in the screenshots/ folder.

📂 Project Structure
🛠️ Tools Used
MongoDB Community Edition

MongoDB Shell (mongosh)

Ubuntu Linux

Git & GitHub

🚀 Author
Nelson Ngumo

MongoDB Checkpoint Submission