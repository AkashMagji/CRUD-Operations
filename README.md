# 🚀 ASP.NET MVC CRUD Application using Entity Framework (ZesTec)

## 📌 Project Overview
This project is a **CRUD (Create, Read, Update, Delete)** web application built using **ASP.NET MVC** and **Entity Framework (EF)** with a **Database-First approach**. It manages employee data including name, designation, and salary.

This application was developed as part of the **ZesTec recruitment process** to demonstrate practical skills in ASP.NET MVC and database operations using Entity Framework.

---

## 🧰 Technologies Used
- ASP.NET MVC 5
- Entity Framework 6 (Database First)
- Microsoft SQL Server
- Razor View Engine
- HTML, CSS, Bootstrap
- Visual Studio 2022

---

## 📂 Features
- ✅ View list of employees
- ➕ Add new employee
- ✏️ Edit employee details
- ❌ Delete employee
- 🔍 View employee details

---

## 📚 Database Structure
Table: **EmployeeMaster**

| Column Name | Data Type | Description            |
|-------------|------------|------------------------|
| ID          | int        | Primary Key            |
| Name        | string     | Employee Full Name     |
| Designation | string     | Job Title              |
| Salary      | decimal    | Yearly Salary          |

Entity Framework's `.edmx` file (`CRUD_with_EF.edmx`) is used to auto-generate the context class `CRUD_with_EFEntities` and the entity model `EmployeeMaster`.

---

## 🚀 How to Run This Project
1. **Clone the repository** to your local machine.
2. **Open** the solution in **Visual Studio 2022**.
3. **Update the connection string** in `Web.config` to point to your SQL Server database.
4. **Build and run** the project (Ctrl + F5).

---

## 🤝 Contribution
This project is part of a coding round for ZesTec and not actively maintained. However, feel free to fork and experiment for your learning purposes!

---

## 📬 Contact
For any queries related to this project or hiring process, feel free to reach out via Email (akashmagaji1213@gmail.com) or LinkedIn.
