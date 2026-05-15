**SalesForce-Summer-Training-Day-5**

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.	What is Apex?

Apex is a strongly typed, object-oriented programming language developed by Salesforce that runs on its cloud platform.

It is used to add custom business logic, perform complex operations, and handle backend processing.

In simple terms, Apex is a Java-like language used when clicks are not enough in Salesforce.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. Difference

   **Flow vs Apex**

👉🏻 **Flow (Declarative)**

a) Type: No-code / Low-code

b) Complexity: Simple to moderate

c) Flexibility: Limited

d) Use Case: Automation (e.g., emails, updates, approvals)

👉🏻 **Apex (Programmatic)**

a) Type: Code-based

b)Complexity: Handles complex logic

c)Flexibility: Highly flexible

d)Use Case: Advanced logic and integrations

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. Real Examples Where Apex Is Needed

--> **Complex Fee Calculation**

Handles multiple conditions like courses, scholarships, discounts, and late fees.

Flow struggles with deeply nested logic, while Apex handles it efficiently.

--> **External Payment Integration**

Used to connect with APIs like Razorpay or Stripe, verify transactions, and store payment data.

Flow has limitations in API handling, while Apex supports HTTP callouts.

--> **Advanced Eligibility Logic**

Example conditions include marks, attendance, dues, and exam scores.

Too complex for Flow, but clean and optimized in Apex.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. Integrated System Design            ?        Explain your complete College Management System using: 
•	CRM  •	Objects   •	Relationships  •	Validation  •	Flow    •	Apex 

➡️ CRM Concept

Manages complete student lifecycle: Lead → Admission → Student → Alumni.

👉🏻 Objects

Student, Course, Faculty.

➡️ Relationships

Student ↔ Course (Many-to-Many).

Faculty → Course (One-to-Many).

👉🏻 Validation

Email must be filled.

Age must be greater than or equal to 17.

Fee cannot be negative.

➡️ Formula Fields

Remaining Seats = Total Seats – Filled Seats.

👉🏻 Flow

Auto email on admission.

Notify when course is full.

Update student status automatically.

➡️ Apex (Custom Logic)

Handles complex fee calculation.

Performs eligibility verification.

Integrates payment systems.

Processes bulk data efficiently.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

5. Pseudocode Examples

**Attendance Rule**

IF attendance < 75%

THEN send warning notification

**Fee Payment Check**

IF fee_status != "Paid"

THEN restrict exam access

--------------------------------------------------------------------------------------------------------------------------------------------------


6. Reflection 

Why enterprise systems eventually need programming  ?

Because business logic becomes complex and difficult to manage using only declarative tools.

Flows have limitations in handling advanced calculations, integrations, and large data processing.

Programming provides scalability, flexibility, and better performance.

--------------------------------------------------------------------------------------------------------------------------------------------------------

**Reflective Questions**

1. Why is Apex needed if Salesforce already has Flows?

Flows handle simple automation, but Apex is required for complex logic, integrations, and high-performance processing.

2. When should developers prefer no-code solutions?

When building simple workflows, notifications, field updates, and approval processes.

3. What problems require custom programming?

Payment gateway integration, complex calculations, decision-based logic, and real-time API communication.

4. Why is business logic important?

It defines how the system behaves, enforces rules, and drives decision-making processes.

5. Why should developers avoid unnecessary coding?

Because it increases maintenance effort, introduces bugs, and slows down development.

6. How does programming increase flexibility?

It allows unlimited logic implementation, external integrations, custom workflows, and better performance handling.

--------------------------------------------------------------------------------------------------------------------------------------------------------



