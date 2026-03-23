Day 1 — BA Role Clarity & Gap Analysis

 What Does a BA Do?
A Business Analyst is the bridge between business teams and IT. They gather requirements from stakeholders, document them clearly, and make sure developers build the right thing. They analyze data, map processes, and present findings to decision-makers. The role requires both technical skills like SQL and Power BI, and soft skills like communication and stakeholder management.

JD Comparison Table
After reading 3 BA job descriptions, the skills that appeared most frequently were requirements gathering, BRD writing, process mapping, data analysis, and stakeholder communication. Tools mentioned included Power BI, SQL, Excel, and Agile/JIRA. My strongest existing skills are Power BI and Excel. My biggest gaps are BRD writing, process mapping, Agile, and JIRA.

My Personal Gap Analysis

Skills I Already Have:
Power BI — Intermediate level (used in Retail Sales Dashboard project)
Excel / Word / PowerPoint — Intermediate (have Microsoft certification)
Data Analysis — Academic level (used in projects)
AI Tools — Active user (using Claude for learning)

🔴 Critical Gaps — Must Learn First:
BRD Writing — Never written one → Learning Day 2–3
Process / Workflow Mapping — No experience → Learning Day 4
Requirements Gathering — No experience → Learning Day 5
Stakeholder Communication — No experience → Learning Day 12
Agile / Scrum — Never used → Learning Day 8
JIRA — Never used → Learning Day 9

🟡 Secondary Gaps — Learn After Week 1:
SQL — Beginner level → Improving Day 10–11
SOP Writing — No experience → Learning Day 15
UAT / QA Testing — No experience → Learning Day 17
Use Case Development — No experience → Learning Day 5
My Day 1 Reflection
Today I read 3 real BA job descriptions and identified my skill gaps. My biggest strengths are Power BI and Excel. My biggest gaps are BRD writing and Agile which I will start fixing from tomorrow.

Day 2 — BRD Structure & Annotations
What is BRD? 

A Business Requirements Document (BRD) is a formal document written by a Business Analyst that describes exactly what a business needs from a project or system. It is created after gathering requirements from stakeholders. Developers, project managers and testers all use the BRD to understand what needs to be built. Without a clear BRD projects fail because teams build the wrong thing.


Why is a BRD Important?

It creates a single source of truth for the entire project
It prevents miscommunication between business and IT teams
It sets clear scope boundaries — what is in and out
It protects the BA if something goes wrong later
It is the number 1 document every BA is expected to produce


BRD Structure — Section by Section

Section 1 — Executive Summary This is the first thing stakeholders read. It explains what the project is and why the company is doing it. It should be short, clear and jargon-free. Example: "This project will automate the customer returns portal to reduce manual processing time from 3 days to 4 hours."
Section 2 — Project Scope Defines exactly what IS and IS NOT included in the project. This prevents scope creep — when people keep adding new requirements mid-project. IN Scope: Online returns, refund processing, email notifications OUT of Scope: In-store returns, international orders, exchanges
Section 3 — Stakeholders A list of everyone involved in or affected by the project. Missing a key stakeholder means missing requirements. The BA must talk to ALL stakeholders before writing requirements. Examples: Operations Manager, IT Developer, Customer Service, Finance Team
Section 4 — Functional Requirements What the system MUST do. Always written as "The system shall..." This is the most important section of the BRD. Example: The system shall allow customers to submit returns in 3 clicks Example: The system shall send confirmation emails within 5 minutes
Section 5 — Non-Functional Requirements How well the system must perform — speed, security, reliability. Often forgotten by new BAs but just as important as functional requirements. Example: The portal shall load within 2 seconds Example: The system shall be available 99.9% of the time
Section 6 — Constraints Non-negotiable limitations the project must work within — budget, time, technology. Example: Must integrate with existing SAP system Example: Budget capped at $50,000, must go live in 3 months
Section 7 — Assumptions Things you are assuming to be true that could affect the project. Assumptions protect the BA if something goes wrong later. Example: All customers have internet access Example: IT team has capacity to support development
Section 8 — Success Metrics How will we know the project succeeded? Every project needs measurable goals. Example: Processing time reduced from 3 days to 4 hours Example: Customer satisfaction increases by 15%


My Day 2 Reflection
Today I learned the full structure of a BRD and annotated all 8 sections. The most important sections are Functional Requirements and Scope. I learned that functional requirements describe WHAT the system does and non-functional requirements describe HOW WELL it performs. Tomorrow I will write my first complete BRD from scratch for a real business scenario. I feel confident because I now understand every section.

Day 3 — My First BRD

Business Requirements Document 
Project: Automated Customer Returns Portal 
Written by: Laxmi Rushaali Kuravi 
Date: March 2026 
Version: 1.0


🎯 The Scenario:
"An e-commerce company wants to build an automated customer returns portal to replace their current manual process."

 Section 1 — Executive Summary
The e-commerce company currently processes customer returns manually through email and phone calls. This process takes 3–5 business days and results in frequent errors and customer complaints. This project aims to build an automated online returns portal that allows customers to submit, track, and resolve return requests digitally. The expected outcome is to reduce processing time from 3 days to 4 hours and improve customer satisfaction by 20%.

Section 2 — Project Scope
✅ IN Scope:
Online return request submission
Automated refund processing
Email notifications to customers
Manager approval dashboard
Daily returns report generation
❌ OUT of Scope:
In-store returns
International order returns
Product exchanges
Mobile app version

Section 3 — Stakeholders
Operations Manager — Project Sponsor — wants to reduce manual workload
IT Developer — System Builder — needs clear technical requirements
Customer Service Team — End Users — needs easy to use interface
Finance Team — Reviewer — tracks accurate refund processing
Customer — External User — wants fast and easy returns process

Section 4 — Functional Requirements
FR1: The system shall allow customers to submit a return request online in 3 clicks or less
FR2: The system shall send an automated confirmation email within 5 minutes of submission
FR3: The system shall allow customers to track their return status in real time
FR4: The system shall allow managers to approve or reject return requests within the portal
FR5: The system shall generate a daily report of all pending and completed returns
FR6: The system shall automatically process refunds within 24 hours of approval
FR7: The system shall send a refund confirmation email to the customer

Section 5 — Non-Functional Requirements
NFR1: The portal shall load within 2 seconds on standard internet connection
NFR2: The system shall be available 99.9% of the time
NFR3: All customer data shall be encrypted using industry standard security
NFR4: The interface shall work on both desktop and mobile devices
NFR5: The system shall support up to 10,000 concurrent users

Section 6 — Constraints
The portal must integrate with the existing SAP order management system
Total project budget is capped at $75,000
Project must go live within 4 months
Must comply with GDPR data privacy regulations
Must use the company's existing cloud infrastructure

Section 7 — Assumptions
All customers have internet access and a valid email address
The IT team has sufficient capacity to support development
Stakeholders will be available for weekly review meetings
The existing SAP system can support the new portal integration
Customers are comfortable using online self-service tools

Section 8 — Success Metrics
Return processing time reduced from 3 days to 4 hours
Customer satisfaction score increases by 20%
Manual processing errors reduced by 90%
Portal adoption rate reaches 80% of customers within 60 days
Customer service team spends 50% less time on returns calls

My Day 3 Reflection
Today I wrote my first complete BRD from scratch for an automated returns portal project. I now understand how all 8 sections connect to each other. The scope defines the boundaries, the functional requirements describe what to build within those boundaries, and the success metrics prove whether we built the right thing. Writing functional requirements as "The system shall..." made them feel professional and testable. Tomorrow I will learn process mapping using BPMN diagrams.








