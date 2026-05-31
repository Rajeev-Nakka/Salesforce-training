## Salesforce Summer Training-Day-13

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1)	What is CI/CD? 

CI/CD is a modern software practice that automates the process of:

. Continuous Integration (CI) → Automatically testing and validating code

. Continuous Deployment (CD) → Automatically deploying code to environments

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2)	Why deployment workflow matters 


Directly editing production is dangerous because:

. Bugs can break the entire system

. Downtime affects thousands of users

. Workflows may fail

. Data loss or corruption may occur

. No proper testing before release

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3)	Problems without version control

If 10 developers work without proper tools:

Code conflicts

Overwriting each other's work

No version history

Difficult debugging

No rollback capability

Deployment failures

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
4)	GitHub + DX + DevOps explanation

Modern Salesforce development uses:

GitHub → Version control


Salesforce DX → Source-driven development

CI/CD Pipelines → Automated testing & deployment

--> Workflow:


Developer writes code →

GitHub commit →

Automated testing →

Validation →

Deployment →

Production release

--> CI/CD Workflow Explanation

a. Developer Writes Code

Implements features or fixes bugs

b. GitHub Commit

Code stored and tracked

c. Automated Testing

Ensures code works correctly

d. Validation

Checks deployment readiness

e. Deployment

Moves code to staging/production

f. Production Release

System updated safely

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
5)	Enterprise deployment risks

. System Downtime

Application may become unavailable for users

Affects thousands of users at once

. Data Loss

Records may be deleted or not saved properly

Critical business data can be lost

. Data Inconsistency

Partial updates may occur

Different parts of system show different data

. Broken Workflows

Automation (Flows/Triggers) may fail

Business processes get interrupted

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
6)	Reflection 

## Writing Code vs Engineering Enterprise Software

. Focus

Writing Code → Focus on logic

Enterprise Engineering → Focus on system reliability

. Work Style

Writing Code → Individual work

Enterprise Engineering → Team collaboration

. Testing

Writing Code → Minimal testing

Enterprise Engineering → Extensive testing

. Deployment

Writing Code → Simple deployment

Enterprise Engineering → Structured deployment pipelines

. Recovery

Writing Code → No rollback

Enterprise Engineering → Rollback mechanisms available
