# HRM-System
Human Resource Management System developed in Java for organizational use

 🧩 Overview
This project is a comprehensive **Human Resource Management System** built in Java, designed to help company administrators manage employee-related operations such as leave requests, payrolls, recruitment, resignation, and internal communication.

The system includes a wide range of functionalities and interfaces for HR operations and is structured using the MVC (Model-View-Controller) design pattern.

---

 ⚙️ Features

- 📥 Recruitment management  
- 🧾 Payroll and payment slips  
- 🏖 Leave day requests and confirmations  
- 📤 Resignation and retirement forms  
- 🗂 Employee records (add/edit/remove)  
- 📋 Position and unit management  
- 📎 Attachment and file uploads  
- 🧑‍💼 Admin dashboard and personnel statistics  
- 💬 Internal messaging and communication  
- 🔒 Authentication and access control  

---

 🏗 Project Structure

- `model/` – Contains `entities`, `repositories`, `services`, and utility classes.  
- `controller/` – Includes multiple controllers like `LeaveDaysController`, `RecruitmentController`, `ResignationController`, etc., and also contains servlets, filters, websocket logic, and validation.  
- `webapp/` – Contains JSP files and front-end views such as:
  - `dashboard.jsp`
  - `dismissal.jsp`
  - `leavedaysConfirmationalList.jsp`
  - `payslips.jsp`
  - `retiredPersonals.jsp`
  - `unitAndDuty.jsp`
  - ...and many more.

---

 💻 Technologies Used

- **Java EE**
- **Servlets & JSP**
- **JDBC**
- **WebSockets**
- **HTML/CSS/JavaScript**
- **Apache Tomcat (for deployment)**

---

 📝 Notes

- The system is designed as a multi-layered enterprise-level application.  
- It supports communication between employees and HR through chat and messaging modules.  
- The application was last fully functional at the time of final testing but may need minor adjustments to run in a new environment.
- Documentation and UML diagrams are added to the repository.

---

 🧑‍💻 Author

Developed by [Negar Tavakol] – Software Engineering Graduate.
Feel free to connect via GitHub or email.

---

 📄 License

This project is licensed under the MIT License.
