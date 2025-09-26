# 🏢 Automated Employee Leave Tracker

This project automates the leave approval workflow using **Airtable** and **Zapier**, ensuring a seamless process for employees and managers.

## 🚀 Features
- Employees can easily submit leave request via Airtable form  and this updates automatically on the leave tracker table
- Email approval links sent to managers (**Approve / Reject**)  
- Leave status updates instantly on Airtable when managers respond
- Tracks each employee’s total leave requests and remaining leave days
- **Employees automatically get notified once their leave is approved or rejected** ✅

## 🛠️ Tech Stack
- **Airtable** – database for employee leave records  
- **Zapier** – automation (email + webhook)
- **Email** - Notification channel

## ⚙️ Workflow
1. Employee submits leave request via Airtable form.  
2. Manager receives email with **Approve** / **Reject** links.  
3. Link triggers Zapier webhook.  
4. Zapier updates the **Status** field in Airtable (Pending → Approved/Rejected).  
5. Airtable automatically calculates:  
   - Total number of leave requests  
   - Remaining leave days  
6. Employee automatically receives an email update once the leave is approved or rejected.  
