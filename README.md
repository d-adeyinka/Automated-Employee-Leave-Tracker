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


## 📸 Screenshots
![Leave Request Form](<img width="297" height="491" alt="Screenshot 2025-11-06 041136" src="https://github.com/user-attachments/assets/00d81abe-1ef3-4034-8772-5fb63ec84ab0" />)

![Employee Record on Airtable](<img width="1228" height="554" alt="Screenshot 2025-10-24 144058" src="https://github.com/user-attachments/assets/21654a84-b54d-4990-b310-e1ee61517770" />)

![Leave Request Table](<img width="1313" height="239" alt="Screenshot 2025-10-24 144120" src="https://github.com/user-attachments/assets/ae3905e2-0ccb-49c2-bb49-1194c10771a3" />)

![Manager Record](<img width="1326" height="414" alt="Screenshot 2025-10-24 144140" src="https://github.com/user-attachments/assets/9801e96d-dedf-4416-b130-89434b4efc63" />)

![Zapier Workflow 1](<img width="16384" height="6754" alt="Leave Request Automation - v4" src="https://github.com/user-attachments/assets/54003d50-ec7a-4da8-948a-5912d9295707" />)

![Zapier Workflow with Webhook](<img width="16384" height="6754" alt="Leave Approval - v1 (1)" src="https://github.com/user-attachments/assets/17475173-e239-44bc-ad38-7e3040222eef" />)

![Email Notification once a leave request is sent](https://github.com/user-attachments/assets/c4c5714a-529e-414c-915e-0ec507313cc6)

## 🔮 Future
 Improvements
- Auto reminders for managers to approve pending requests  
- Slack/MS Teams integration for approvals  
- Custom leave allocations per employee  
