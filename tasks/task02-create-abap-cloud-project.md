✅ Task 02: Create ABAP Instance, Service Key & Cloud Project
💼 Business Goal:
Set up a cloud-based ABAP environment in SAP BTP and connect it with Eclipse so you can begin development.

🧭 Step-by-Step Guide
🔹 1. Log in to SAP BTP Global Account
Go to SAP BTP Cockpit

Use your SAP credentials.

🔹 2. Navigate to Your Subaccount
From your global account dashboard, select your subaccount.

Example: trial → dev subaccount

🔹 3. Check or Create an ABAP Instance
Left Panel → Instances and Subscriptions

Scroll down to Instances.

If No ABAP Instance Exists:
Click Create.

Choose Service: ABAP environment

Plan: standard

Give it a name like: S4D100

In the JSON config screen, edit as:

json
Copy
Edit
{
  "email": "your-email@example.com"
}
Click Next, then Create.

⏳ Wait a few minutes for it to be provisioned.

🔹 4. Create a Service Key (if none exists)
Click on your newly created instance.

Look for Service Keys section (below the instance info).

Click ... → Create Service Key

Name it: S4D100

Click Create

You’ll see a long JSON key appear.

🔹 5. Copy the Service Key
Under Service Key, click:
→ Actions (three dots) → View or Download
→ Click Copy JSON

🔹 6. Open Eclipse (ABAP Development Tools Installed)
Open Eclipse

Go to:

Window → Perspective → Open Perspective → Other → ABAP
🔹 7. Create ABAP Cloud Project
Go to:

File → New → ABAP Cloud Project
Choose:

✅ Use a Service Key

Click Next

In the JSON editor:

Right-click → Paste your copied service key JSON

Click Next

Click Open Logon Page in Browser

Log in using your BTP credentials

Success message should appear

Return to Eclipse

Click Finish

🧠 Key Learnings
Understood how SAP BTP provisions ABAP runtime environments.

Learned how to securely connect Eclipse to BTP using Service Keys.

First time working with JSON-based service credentials.
