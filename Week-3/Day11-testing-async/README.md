**Salesforce Summer Training-Day-11**

------------------------------------------------------------------------------------------------------------------------------

1)	Why testing matters 

.Prevents bugs before deployment

.Ensures business logic works correctly

.Improves system reliability

.Mandatory in Salesforce (minimum test coverage required)

.Helps handle edge cases

------------------------------------------------------------------------------------------------------------------------------


2) What is asynchronous processing 

Asynchronous processing means executing tasks in the background instead of immediately.

Types in Salesforce:

.Future Methods

.Queueable Apex

.Batch Apex

--------->  Benefits:

.Handles long-running operations

.Improves performance

.Avoids blocking user actions

.Supports scalability

------------------------------------------------------------------------------------------------------------------------------

3) Important test cases

a) Invalid Email Format

Prevents incorrect user data

b) Duplicate Student Registration

Avoids duplicate records

c) Course Seat Limit Exceeded

Ensures capacity rules

d) Attendance Below Threshold

Triggers warning notifications

e) Missing Required Fields

Ensures data completeness

f) Invalid Course Assignment

Prevents wrong relationships

g) Bulk Student Insert

Tests system under load

h) Notification Failure Handling

Ensures alerts are reliable

i) Apex Logic Validation

Verifies business logic correctness

j) Flow Execution Failure

Ensures automation reliability

------------------------------------------------------------------------------------------------------------------------------
4)	Async use cases 

a) Bulk Email Sending

Send thousands of emails in background

b) Report Generation

Large reports without UI delay

c) Large Data Import

Process records asynchronously

d) Notification Processing

Handle multiple alerts efficiently

e) External System Integration

Sync with APIs without blocking

------------------------------------------------------------------------------------------------------------------------------

5)	Reliability discussion

 **System Crash Scenarios**
 
--> During Student Registration

Data may not be saved

Partial record creation

--> During Payment Update

Incorrect transaction state

Data inconsistency

-->During Attendance Update

Wrong attendance records

Missed alerts

==> How Testing Helps

Identifies failure points early

Ensures rollback mechanisms

Validates all edge cases

Improves system stability

------------------------------------------------------------------------------------------------------------------------------

6) Reflection 

Enterprise systems require:

a) Testing
 
 To ensure correctness and reliability

b) Scalability

To handle thousands of users

c) Async Processing

To avoid blocking operations

To improve performance

------------------------------------------------------------------------------------------------------------------------------
