# 🏢 Sam's HRMS : A Completely Free, Browser Based HRMS & Payroll Suite

A complete, self-contained **Human Resource Management System (HRMS) & Statutory Payroll Suite** that runs entirely inside your web browser. 
And the best thing, its Completely free 
Built with zero external dependencies, no server backends, and no cloud databases—everything is stored directly on your local hard drive as readable, unencrypted files using the native **File System Access API**.

---

## 🌟 Key Highlights

- **100% Local & Offline:** No internet connection or remote servers needed. Operates purely on client-side web standards.
- **True File-System Persistence:** Data is saved directly to your local `./data` file, and uploaded files (resumes, ID scans) live natively in `./documents/` on your computer.
- **Single-File Architecture:** The entire app runs from a single `index.html` file—no `npm install`, Node.js runtimes, or database configuration required.
- **Zero Lock-In:** Unencrypted data structure allows instant inspection, backups, or edits via any text editor or spreadsheet tool.
- **Portable:** Drop the directory onto a USB drive and run it across machines via Chromium-based browsers (Chrome, Edge, Brave).

---

## 🚀 Features

### 📊 Executive Summary & Visual Analytics
- Real-time KPI metric tiles: Headcount, Active Workforce, Monthly Outflow, and Attendance Health.
- Interactive SVG donut charts for **Payroll CTC Composition**, **Departmental Budget Allocation**, **Today's Attendance Status**, and **Workforce Diversity**.
- Upcoming company holidays and employee birthday reminders.
  
  <img width="1919" height="963" alt="Executive Summary" src="https://github.com/user-attachments/assets/aa320fc5-e112-4354-9637-8f411d8aa6b7" />


### 📋 Employee Management & Local Vault
- Complete employee master records: Personal info, emergency contacts, banking (IFSC, UAN, ESIC), salary structure, and education.
- **Local Document Vault:** Upload and organize contracts, resumes, and ID proofs directly into dedicated subfolders (`./documents/EMP_<ID>/`).
- **HR Document & ID Card Generator:** One-click generation and printing for:
  - Offer & Appointment Letters
  - Experience & Relieving Certificates
  - Salary Revision / Increment Letters
  - Employee ID Cards
    
    <img width="1916" height="956" alt="Employee Management" src="https://github.com/user-attachments/assets/0c124ced-c673-44d9-8b95-44655d463112" />


### ⏱️ Attendance & Shift Roster
- Daily attendance logger with Check-In/Check-Out times and auto-calculated work hours.
- **Temporary Shift Override:** Override an employee's default shift for specific operational days.
- **Mark All Present:** Fast-track daily logging for your entire active workforce.
- **Monthly Matrix View:** Full calendar grid (Days 1–31) showing status (`P`, `A`, `HD`, `L`) at a glance.
  
  <img width="1907" height="959" alt="Attendance & Shift Roster" src="https://github.com/user-attachments/assets/f7b60e67-687e-4a13-af3e-b5e99dee65d5" />


### 🏖️ Leave Management & Quota Enforcement
- Tracks Casual Leave (CL), Sick Leave (SL), Earned Leave (EL), and Loss of Pay (LOP).
- Real-time tracking of annual leave balances vs. configured quotas.
- Extra unpaid absences automatically sync to the payroll engine as Loss of Pay deductions.
  
  <img width="1919" height="957" alt="Leave Management & Quota Enforcement" src="https://github.com/user-attachments/assets/63092020-fd4e-4234-b9a7-951b4cf47ce5" />


### 💳 Loans, Salary Advances & Expenses
- **Loans & Advance EMI:** Issue advances and specify monthly EMI deductions that auto-deduct during payroll.
- **Expense Reimbursements:** Log out-of-pocket claims (travel, fuel, supplies) that feed directly into monthly payouts as non-taxable additions.
  
  <img width="1906" height="956" alt="Loans, Salary Advances & Expenses" src="https://github.com/user-attachments/assets/c729ec6d-d014-44b9-81dc-77ce7bb75929" />


### 💻 Company Asset & Inventory Tracker
- Assign hardware (laptops, phones, monitors) and track serial numbers.
- Check-in/check-out workflow with asset return statuses.
  
  <img width="1913" height="958" alt="Company Asset & Inventory Tracker" src="https://github.com/user-attachments/assets/2c998761-2daf-4e40-bd1d-4efc61bd816f" />


### 💵 Statutory Payroll Engine & Disbursals
- Computes pro-rata pay, EPF (12%), ESI (0.75% / 3.25%), Professional Tax (PT), TDS, overtime, and loan EMIs.
- Executive payslip generator formatted with company branding, ready for print or PDF export.
- **Export Formats:**
  - **Bank NEFT/RTGS CSV:** Batch payout file for direct banking portal upload.
  - **EPFO ECR (.txt):** Standard `#~#` delimiter text file ready for the EPFO unified portal.
  - **ESIC Contribution CSV:** Formatted monthly contribution statement.
  - **Full Payroll Register:** Comprehensive audit CSV.
    
    <img width="1919" height="955" alt="Statutory Payroll Engine & Disbursals" src="https://github.com/user-attachments/assets/bdfd68a9-90bc-4e6b-8800-3a4e3a319e8d" />


### 🤝 Full and Final (FnF) Settlement Calculator
- Automated calculation for exiting employees: unpaid salary days, Earned Leave encashment, statutory Gratuity (15/26 formula for $\ge 5$ years tenure), minus outstanding loans or asset recoveries.
- Printable FnF settlement statement.

### ⚙️ Settings, Theming & Backup
- Complete company profile configuration (branding, logos, branches, tax registrations).
- Adjustable statutory rates and leave quotas.
- One-click JSON database backup and restore utility.
- Native Light & Dark mode support.
  
  <img width="1919" height="963" alt="Settings, Theming & Backup" src="https://github.com/user-attachments/assets/ebf1b62b-25d6-4429-960f-06674c0d0ed4" />


---

## 🛠️ Getting Started

### Prerequisites
A modern Chromium-based desktop browser:
- Google Chrome
- Microsoft Edge
- Brave
- Opera

*(Note: The W3C File System Access API is supported natively in Chromium browsers).*

### Installation & Run

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Athul690/Sam-s-HRMS.git

2. Open the index.html using any chromium based browser.
3. Allow Files Access, If not prompted click on "Allow Files Access"

And before anyone goes sherlock Homes on the code. The code is 90 % AI, I only added some tweaks to the code. I tried to add all things i wanted when i started work.


