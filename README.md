# Healthcare-Dataset-Analysis
Performed Data Analysis in SQL on Healthcare Dataset using MySQL Workbench

# 🏥 Healthcare Data Analysis using SQL

This project demonstrates SQL-based analysis on a **Healthcare Management System** involving patients, doctors, appointments, billing, and prescriptions. The database is designed to extract insights for hospital management, billing optimization, and medical record analytics.

---

## 📂 Database Name

**`healthcare`**

---

## 📊 Tables Used

- **`patients`** – Patient personal details  
- **`appointments`** – Records of patient-doctor appointments  
- **`billing`** – Payment status and billing info for appointments  
- **`doctors`** – Doctor profiles and specialties  
- **`prescriptions`** – Medications prescribed during appointments  

---

## 🔍 Analysis and Queries Overview

### 1. 📅 Appointments & Patient History
- Appointments by patient
- Appointments by doctor
- Appointments in the last 30 days
- Appointments without billing
- Appointments by specialty
- Appointments by reason (most common)
- Appointments trend (monthly & yearly)
- Day-wise appointment counts

### 2. 👩‍⚕️ Doctor Insights
- Appointments per doctor
- Doctor performance metrics
- Doctor-wise revenue generated
- Doctor appointments in August (filtered by date)

### 3. 🧾 Billing & Payments
- Total billed vs. total paid
- Pending bills and unpaid analysis
- Average billing per patient
- Payment trends over months
- Billing status with appointment linking

### 4. 💊 Prescriptions
- Prescriptions by appointment
- Most frequently prescribed medications
- Prescriptions linked to pending payments
- All prescriptions with payment status

### 5. 👤 Patient Demographics & Metrics
- Patient appointment history
- Gender distribution
- Patients without appointments
- Latest appointment per patient
- Patient billing and appointment summary

---

## 🧠 Advanced Insights

- **Appointment Frequency vs Billing Correlation**
- **Unpaid Bills by Patient**
- **Top 10 Patients by Total Billing**
- **Missed Appointments or Gaps**
- **Appointment patterns by specialty**

---

## 🧰 Technologies Used

- **MySQL** – Querying and managing relational data  
- **SQL Workbench** – IDE for running and visualizing queries  
- **GitHub** – Version control and code hosting

---

## ✅ How to Use

1. Clone the repository
2. Create the `healthcare` database and import relevant tables
3. Run the SQL queries step-by-step to explore insights
4. Modify queries to suit real-time analysis needs

---

## 📌 Example Use Cases

- Hospital management can track doctor performance and load  
- Billing department can identify unpaid bills and patient history  
- Healthcare analysts can evaluate patient trends and prescription patterns  
- Admins can forecast appointment trends and operational demands

---

## 🙌 Acknowledgements

This project is built for learning and exploring **real-world SQL applications** in the **healthcare domain**.

---

> 💡 *For dataset structure or sample data, see the `sql` and `csv` files in this repository.*

