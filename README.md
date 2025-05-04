# 🚀 Automated API Testing with Rest Assured

## 📘 Project Description
This project demonstrates end-to-end API testing for the application hosted at **Daily Finance**. The testing includes core features such as **user management** and **item management**. The APIs were first inspected using the browser's Network tab and automated using **Rest Assured**, a popular library for API testing in Java.

The automation covers both ✅ positive and ❌ negative test scenarios to ensure the reliability and robustness of the APIs. The process was divided into two phases:

- 📬 **Postman Collection**: Creating and testing API requests for the required features.
- 🤖 **Automation with Rest Assured**: Automating the same requests and validating responses programmatically.

## ⚙️ Prerequisites
Ensure the following tools and libraries are installed:

- ☕ Java JDK (version 8 or later)
- 🧰 Maven (for dependency management)
- 💻 IntelliJ IDEA or any Java IDE of your choice
- 📫 Postman (to inspect and test API requests)
- 🌐 Browser Developer Tools (to capture API details)

## 🎯 Objectives

- 🔗 Visit the application at [https://dailyfinance.roadtocareer.net/](https://dailyfinance.roadtocareer.net/)
- 🛠️ Create a Postman collection by inspecting API requests using the browser's Network tab for the following features:
  - 📝 Register a new user
  - 🔐 Login by admin
  - 📋 Get the user list
  - 🔍 Search the newly registered user by user ID
  - 🛠️ Edit user information (e.g., first name, phone number)
  - 👥 Login as any user
  - 📦 Get the item list
  - ➕ Add a new item
  - ✏️ Edit the name of an item
  - ❌ Delete an item from the list
- 🤖 Automate the full API collection using **Rest Assured**
  - ⚠️ Implement negative test cases where necessary to ensure API robustness


## ✅ What I Have Done
### 🔍 Step 1: Inspecting APIs Using Postman
Created a Postman collection for the following API endpoints:

- 👤 **User Registration APIs**
  - 📝 Register a new user

- 🔐 **User Management APIs**
  - 🔑 Login as admin
  - 📃 Fetch the user list
  - 🔎 Search for a user by ID
  - 🛠️ Edit user information (e.g., first name, phone number)
  - 👥 Login as any user

- 📦 **Item Management APIs**
  - 📄 Fetch the item list
  - ➕ Add a new item
  - ✏️ Edit an item name
  - ❌ Delete an item

### 🤖 Step 2: Automation Using Rest Assured

- ✅ Automated the above API requests with necessary assertions.
- 🔄 Handled **positive cases** to validate core functionality.
- ⚠️ Added **negative cases** to verify error handling, including:
  - ❌ Invalid input formats (e.g., missing fields during registration)
  - 🔐 Unauthorized access (e.g., admin-only actions attempted by regular users)
  - 🛑 Attempting to edit or delete non-existent items or users

---

## 🧪 How to Run the Tests

**🔹 Step 1: Clone the Repository**  
Clone this project using:  
```bash
git clone <repository-url>
```

**🔹 Step 2: Open the Project**  
Open the project in **IntelliJ IDEA** or any Java IDE of your choice.

**🔹 Step 3: Run the Tests**  
Execute the tests using **TestNG**:
- Right-click on the `src/test/java` folder
- Select **Run All Tests**

**🔹 Step 4: Analyze the Results**  
Test results will display detailed logs and validations for each API request and response.

---

## 📬 Postman Collection Documentation  
🔗 [View Documentation](https://documenter.getpostman.com/view/42431548/2sB2j68pWZ)

---

## 📄 Test Case Sheet  
🧾 [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1Gf4uuzBKkS1U8dsZudsb0_05mlbXAX7kP6rUdAgL-yI/edit?usp=sharing)

---

## 📸 Allure Report Screenshot  
![Image (3)](https://github.com/user-attachments/assets/a3502731-5aa9-4fcb-96c4-bd3d43770297)
![Image (2)](https://github.com/user-attachments/assets/882dc83c-4a36-420b-a66f-9b1e704d7506)
![Image (1)](https://github.com/user-attachments/assets/e6211a7c-13f7-46f5-8f8a-a9e1bfcc5ed0)

---

## 🎥 Sample Video of Automation Process


https://github.com/user-attachments/assets/a25b72f6-bb97-4658-9934-ecba63ddeee2


---
