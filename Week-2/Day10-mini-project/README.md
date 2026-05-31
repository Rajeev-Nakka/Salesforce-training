**Salesforce Summer Training-Day-10**

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**College Management Mini Project**

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1)	System Overview 

A College Management System designed using Salesforce to manage:

--> Students

--> Faculty

--> Courses

--> Departments

The system integrates UI, backend logic, automation, and database operations.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2)	CRM Concepts

.Student – Stores student details

.Faculty – Stores faculty details

.Course – Course information and seat limits

.Department – Department structure

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3)	Data Model


**Objects:**

.Student__c

.Faculty__c

.Course__c

.Department__c

**Relationships:**

.Student → Course (Many-to-One)

.Course → Faculty (Many-to-One)

.Course → Department (Many-to-One)

**Fields:**

Name, Email, Phone

Course Seats

Attendance

Status

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4)	Validation Rules

Email field must not be empty

Course seats cannot exceed defined limit

Attendance cannot be negative

Mandatory fields must be filled

**Formula Fields**

. Remaining Seats = Total Seats – Enrolled Students

. Attendance % = (Attended Classes / Total Classes) × 100

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5)	Flows

. Auto confirmation email after registration

. Attendance warning when below threshold

. Automatic status updates

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

6)	Apex Logic 

. Eligibility calculation for course enrollment

. Bulk student processing

. Custom business logic implementation

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

7)	UI Screens

**Student Dashboard**

.View courses

.View attendance

**Faculty Dashboard**

. Manage attendance

. View students

**Registration Screen**

. Student registration form

. Course selection

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

8)	Complete Data Flow

Student clicks Register →

LWC Screen →

Validation →

Flow →

Trigger →

Database →

Notification

**Explanation:**

a) LWC UI

User enters details in registration form

b) Validation

Ensures required fields and rules are satisfied

c) Flow

Automates actions like sending emails

d) Apex Trigger

Executes business logic on data change

e) Database

Record stored in Salesforce objects

f) Notification

User receives confirmation or alerts

**Architecture Thinking**

Enterprise systems require:

Frontend (LWC) → User interaction

Backend (Apex) → Business logic

Database (Objects) → Data storage

Automation (Flows) → Reduce manual work

Events/Triggers → Real-time updates

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

9) Reflection

After learning Salesforce, I realized:

.Enterprise systems are highly modular

.UI, backend, and data must work together

.Automation and events are critical

.Scalability and performance must be planned

.Real-world applications are complex but structured

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------



