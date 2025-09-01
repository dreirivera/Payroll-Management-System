# 🇵🇭 Payroll Management System (Microsoft Access)

A **Payroll Management System** developed in **Microsoft Access** tailored for the Philippine payroll process.  
This project simplifies employee management, salary computation, government-mandated deductions, and payroll generation.

---

## ✨ Features
- 👤 **Employee Management** – Store personal, job, and government information.  
- 💰 **Salary & Allowances** – Track base salary, allowances, and gross pay.  
- 📅 **Attendance Tracking** – Monitor daily attendance, absences, and overtime.  
- 🧾 **Deductions & Contributions** – Automatically handle SSS, PhilHealth, Pag-IBIG, and loan deductions.  
- 🏦 **Payroll Processing** – Calculate gross, deductions, and net pay per pay period.  
- 📊 **Reports & Payslips** – Generate employee payslips and reports for compliance with BIR, SSS, PhilHealth, and Pag-IBIG.  

---

## 🗄 Database Schema (Key Tables)

### 1. Employees
- Personal and job details (ID, name, contact, hire date, job title, department, salary ID, SSS, PhilHealth, Pag-IBIG, TIN, status).

### 2. Departments
- Department ID, name, and manager reference.

### 3. Salary
- Base salary, allowances, and gross salary per employee.

### 4. Attendance
- Daily attendance, hours worked, and overtime.

### 5. Deductions
- Records of mandatory and optional deductions (SSS, PhilHealth, Pag-IBIG, loans).

### 6. Government Contributions
- Monthly contributions to SSS, PhilHealth, and Pag-IBIG.

### 7. Tax
- Tax brackets and rates for payroll tax computation.

### 8. Payroll
- Payroll records including pay period, gross salary, total deductions, net salary, and pay date.

### 9. Overtime
- Overtime hours, rates, and pay.

---

## 🔗 Relationships
- **Employees ↔ Department**  
- **Employees ↔ Salary**  
- **Employees ↔ Attendance**  
- **Employees ↔ Deductions**  
- **Employees ↔ Payroll**  
- **Employees ↔ Government Contributions**  

---

## ⚙️ Requirements
- Microsoft Access 2016 or later
- Windows OS (for best compatibility)

---

## 🚀 Usage
1. Open the `.accdb` file in Microsoft Access.  
2. Import the provided tables and relationships.  
3. Use built-in queries and reports to generate payrolls and payslips.  

---

## 📌 Author
Developed for **commissioned projects** and academic purposes.  
For inquiries and customization, feel free to contact Edrei Reigne Rivera.

---

## 📜 License
This project is licensed under a **Proprietary License**.  
All rights reserved © 2025 [Edrei Reigne Rivera].

---

