**Salesforce-Summer-Training-Day-4**
-----------------------------------------------------------------------------------------------------------------------------
1. What is Flow Builder?

Flow Builder is a declarative (no-code/low-code) automation tool in Salesforce that allows users to automate business processes without writing code.

It helps in:

Automating repetitive tasks

Creating guided user interactions

Updating records automatically

Integrating logic into business workflows

**In simple terms, Flow Builder replaces manual work with automated processes.**

---------------------------------------------------------------------------------------------------------------------

2. Types of Flows

👉🏻  **Screen Flow**

Screen Flow is used when user interaction is required.

Displays screens to users (like forms)

Takes input from users

Performs actions based on input

-->Example:

A form to collect customer details and create a record.

👉🏻 **Record Triggered Flow**

Record Triggered Flow runs automatically when a record is created, updated, or deleted.

No user interaction required

Works in the background

Used for automation on database changes

--> Example:

When a new Lead is created → automatically assign it to a sales representative.

-------------------------------------------------------------------------------------------------------------------------

3. Your Automation Ideas (5 Examples)

--> Lead Assignment Automation

Automatically assign leads to sales reps based on region.

--> Email Notification System

Send an email when a new customer record is created.

--> Task Creation Flow

Create a follow-up task when an opportunity is updated.

--> Student Registration Form

Use Screen Flow to collect student details and store them.

--> Case Escalation Process

Automatically escalate cases if not resolved within 2 days.

--------------------------------------------------------------------------------------------------------------------------

4. Your Flow Diagram


Start

  ↓

Record Created (Lead)

  ↓

Check Condition (Region)

  ↓

Assign Owner

  ↓

Send Email Notification

  ↓

End

**Explanation**

a) Start → Flow begins automatically

b) Record Created (Lead) → Trigger happens when a new Lead is created

c) Check Condition (Region) → Determines which region the lead belongs to

d) Assign Owner → Assigns the lead to the appropriate sales representative

e) Send Email Notification → Notifies the assigned owner

f) End

------------------------------------------------------------------------------------------------------------------------

5. Manual vs Automated Process

**Manual Process**

.Requires human effort

.Time-consuming

.Prone to errors

.Not scalable

**Automated Process**

.Runs automatically

.Saves time

.Reduces errors

.Improves efficiency

------------------------------------------------------------------------------------------------------------------------------

6. Reflection: Why Automation Matters in Enterprise Systems

Automation is essential because enterprise systems deal with large volumes of data and processes.

**Without automation:**

.Work becomes slow

.Errors increase

.Productivity decreases

With automation:

.Processes become faster

.Accuracy improves

.Employees focus on important tasks instead of repetitive work

-------------------------------------------------------------------------------------------------------------------

➡️**Reflective Questions**

1. Why do companies automate workflows?

--> Companies automate workflows to save time, reduce human effort, and improve efficiency.

2. What problems happen with manual processes?

--> Human errors

--> Delays

--> Inconsistency

--> Difficulty in tracking work

3. Difference between Screen Flow and Record Triggered Flow?

Screen Flow → Requires user interaction

--> Record Triggered Flow → Runs automatically in the background

4. Why is no-code automation powerful?

--> Because even non-developers can build automation, making it faster and more accessible.

5. When should automation be avoided?

--> Automation should be avoided when:

--> Process is not clearly defined
--> Requires human judgment
--> Changes frequently

6. How does automation improve consistency and productivity?

**Automation ensures:**

Same process is followed every time (consistency)

Tasks are completed faster (productivity)
