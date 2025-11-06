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

<h2>⚙️ Workflow Architecture</h2>

<div align="center" style="font-family: Arial, sans-serif;">

  <div style="border: 2px solid #ccc; border-radius: 10px; padding: 20px; width: 600px; background: #fafafa; text-align: left;">
    <ol style="line-height: 1.8;">
      <li>👩‍💼 Employee submits <strong>Leave Request</strong> via <strong>Airtable Form</strong>.</li>
      <li>📩 Manager receives email with <strong>Approve</strong> / <strong>Reject</strong> links.</li>
      <li>🔗 Link triggers a <strong>Zapier Webhook</strong>.</li>
      <li>⚡ Zapier updates the <strong>Status</strong> field in Airtable (<em>Pending → Approved/Rejected</em>).</li>
      <li>📊 Airtable automatically calculates:
        <ul>
          <li>Total number of leave requests</li>
          <li>Remaining leave days</li>
        </ul>
      </li>
      <li>📧 Employee receives an <strong>automated email</strong> update once the leave is approved or rejected.</li>
    </ol>
  </div>

  <br>
  <svg width="600" height="250" xmlns="http://www.w3.org/2000/svg">
    <rect x="20" y="20" width="120" height="50" fill="#a8dadc" stroke="#333" rx="10"/>
    <text x="40" y="50" font-size="14" font-family="Arial">Employee</text>

    <rect x="180" y="20" width="120" height="50" fill="#fcbf49" stroke="#333" rx="10"/>
    <text x="205" y="50" font-size="14" font-family="Arial">Airtable Form</text>

    <rect x="340" y="20" width="120" height="50" fill="#90be6d" stroke="#333" rx="10"/>
    <text x="370" y="50" font-size="14" font-family="Arial">Zapier</text>

    <rect x="500" y="20" width="120" height="50" fill="#f77f00" stroke="#333" rx="10"/>
    <text x="520" y="50" font-size="14" font-family="Arial">Manager</text>

    <line x1="140" y1="45" x2="180" y2="45" stroke="#555" marker-end="url(#arrow)" />
    <line x1="300" y1="45" x2="340" y2="45" stroke="#555" marker-end="url(#arrow)" />
    <line x1="460" y1="45" x2="500" y2="45" stroke="#555" marker-end="url(#arrow)" />

    <defs>
      <marker id="arrow" markerWidth="10" markerHeight="10" refX="5" refY="3" orient="auto">
        <path d="M0,0 L0,6 L9,3 z" fill="#555" />
      </marker>
    </defs>
  </svg>

</div>


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
