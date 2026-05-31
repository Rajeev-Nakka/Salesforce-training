**Salesforce Summer Program – Day_9**
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1) **Component Communication**
 
 Types of Communication

a) Parent → Child

Uses @api decorator

Parent passes data via attributes

b) Child → Parent

Uses Custom Events

Child dispatches event → parent listens

c) Unrelated Components

Use Pub-Sub Model or Lightning Message Service (LMS)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2) **Dashboard Architecture**

a) **Student Dashboard**

Components:

StudentProfile

CourseList

AttendanceView

b) **Faculty Dashboard**

Components:

FacultyProfile

StudentList

AttendanceUpdater

c) **Admin Dashboard**

Components:

UserManagement

CourseManagement

Reports

d) Component Communication

. StudentProfile ↔ CourseList (data display)

. Faculty → AttendanceUpdater (updates data)

. Admin → All components (control & monitoring)

. Components communicate using:

. Props (@api)

. Events

. Shared services (Apex/LMS)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3) **Data Flow Explanation (Student Registration)**

Flow:

UI → Validation → Flow → Apex → Database → Notification

Step-by-Step:

a) UI

 User fills registration form

b) Validation

Check required fields

Email format validation

c) Flow (LWC Logic)

Data prepared and structured

d) Apex

Apex class processes request

Business logic applied

e) Database

Record stored in Salesforce (Object)

f) Notification

Success message / Email confirmation

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
4) **Aura vs LWC – Why Salesforce moved to LWC?**


--> Performance

Aura: Slower due to framework overhead

LWC: Faster because it uses native JavaScript and browser APIs

--> Architecture

Aura: Framework-heavy and proprietary

LWC: Based on modern web standards (HTML, CSS, JS)

--> Learning Curve

Aura: Complex and harder to learn

LWC: Easier, uses standard web development skills

--> Debugging

Aura: Difficult to debug

LWC: Easier debugging with standard browser tools



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5) **Reflection: Modular Architecture**

--> Why do enterprise apps need modular design?

Reusability of components

Easy maintenance

Scalability

Independent development

Faster debugging

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
