🚀 n8n Airtable Automation Workflow
📌 Project Overview

This project demonstrates an automation workflow built using n8n that processes form submissions and updates records in Airtable based on conditions.

🛠️ Tools Used
n8n (Workflow Automation)
Airtable (Database)
⚙️ Workflow Explanation

The workflow consists of the following steps:

1️⃣ Form Submission Trigger
The workflow starts when a form is submitted.
This acts as the entry point of automation.
2️⃣ Create Record in Airtable
A new record is created in Airtable using the submitted data.
3️⃣ Switch Node (Decision Making)
A switch condition is applied based on a specific field (e.g., role or value).
The workflow branches into different paths.
4️⃣ Update Records Based on Condition
Depending on the condition:
Record is updated differently in Airtable
Multiple update nodes handle different scenarios
🔄 Workflow Logic

IF condition:

If value = X → Update Record Path 1
If value = Y → Update Record Path 2
Else → Default Update

📦 How to Use
Import first automation.json into n8n
Connect your Airtable credentials
Activate the workflow
Trigger using form submission

💡 What I Learned
Building automation workflows using n8n
Integrating Airtable with APIs
Using conditional logic (Switch node)
Designing real-world automation systems

🚀 Future Improvements
Add email notifications
Integrate with external APIs
Add error handling

👩‍💻 Author

Harshada
