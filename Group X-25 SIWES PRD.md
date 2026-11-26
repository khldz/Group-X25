# PROJECT TITLE: SIWES Placement Discovery Tool 

**NAME:** Oshodi Khaleed, philip chibuike divine, Special Ororo  
**MATRIC NUMBER: ** 25/1058, 25/0172, 25/0624  
**COURSE:**COS 209

## Introduction

SIWES is a mandatory requirement for a lot of us, but actually getting a placement is a huge headache. I noticed that while there are job boards online, they don’t really help students who are looking for something specific to their course. This document outlines my plan for a simple platform that fixes this discovery problem.

## The Main Problem

Based on my research, the biggest issue is discovery (finding companies that actually accept SIWES students) and relevance (finding companies that accept my specific course).

I sent out a survey and got 22 responses. The data backed up exactly what I suspected:

· **68.2%** of students said their biggest challenge is "finding companies related to my course."  
· **54.5%** said their challenge is just finding companies that accept SIWES students at all.  
· When asked what they want to know before applying, 63.6% said they want to know which "departments or courses are accepted."

The text responses were even clearer. One person wrote: "Finding companies that accept SIWES students and are relevant to their course of study, especially when information about available opportunities is difficult to access." Another person specifically mentioned needing to find "hospitals and diagnostic centres that accept SIWES students."

What is NOT the problem:  
I was advised to check if "application tracking" (like keeping a list of where you applied) is a problem. I looked through all 22 of my survey responses, and nobody mentioned losing track of applications. The focus is strictly on the struggle to find a place. So, tracking features are not part of this plan.

## Interview Findings (Real Experience)

To get more context, I interviewed my aunt, who completed her SIWES a few years ago. I asked her to walk me through her actual experience, not just if she would use an app.

She confirmed the exact problem my survey found. She said a lot of companies didn't offer SIWES for her specific course, and looking for companies was a major stress. Because the majority of companies don't even accept SIWES students (or prefer other courses), she couldn't find a normal placement. To avoid failing the course, she had to fall back on a personal connection. She ended up working for my mum just to get her SIWES form signed.

This proves that when students can't find a relevant company, they are forced to abandon the real purpose of SIWES and rely on family favors just to pass.

## Who is this for?

· **Main Users:** 200, 300, and 400 level students who need to find SIWES. (My survey showed 45.5% of respondents need to do SIWES within the next 6 months, so there is an urgent need).  
· **Special case students:** People in courses like Microbiology or Forensic Science who get rejected because companies only want Medical Lab Science students.

## The Proposed Solution 

A simple website where students can search for SIWES placements based on their exact course and location.

· **Filter by Course:** Instead of just "Science" or "Engineering," you pick your exact course (e.g., Biochemistry).  
· **Filter by Location:** Since transport is a problem, students can search by their area.  
· **Company Details:** Every company listed will show the info students actually care about (according to my survey):Location, Courses Accepted, Application Requirements, and if they pay a stipend.

**What we are NOT building right now:**

· No in-app application tracking.  
· No messaging system.  
· No CV builders.

## User Stories (How a student would use it)

· "As a Microbiology student, I want to see a list of labs that actually take Microbiology students, so I don't waste my time walking to hospitals that only want MLS students."  
· "As a student in Lagos, I want to filter by my LGA so I don't spend all my stipend on transport."  
· "As a student, I want to see the requirements (like if I need to bring a physical letter) before I leave my house."

## Other Existing Apps

I know apps like I-Tapp and general job boards exist. But they mostly just list companies. The difference with my idea is the specific course matching. It’s about telling a student exactly where they are wanted, not just showing them a generic list of 100 companies.

## Challenges / Risks

· **Outdated info:** What if a company stops accepting students? Fix: I will add a button for users to report outdated info.  
· **Starting out:** How do we get companies on the site at first? Fix: Start small. I will manually add 50 companies for just one faculty (like Faculty of Science) before launching it to everyone.

##  Next Steps

Before I start designing the UI, I want to gather one or two more stories from people who have already done SIWES to see if they also struggled with finding a company related to their course.  

## 1. Functional Requirements (Functionalities)
Functional requirements describe the specific tasks and operations the SIWES Placement Discovery Tool must be able to perform.
1.1 Student Registration and Login
- The system shall allow students to create an account using their name, email address, password, institution, and course of study.
- The system shall allow registered students to log in and log out securely.
- The system shall allow students to update their profile information.
1.2 Search for SIWES Opportunities
- The system shall allow students to search for companies and organizations offering SIWES placements.
- The system shall allow students to search using company names, courses, industries, and locations.
- The system shall display relevant search results based on the student's search criteria.
1.3 Course-Based Filtering
- The system shall allow students to select their specific course of study.
- The system shall display only companies that accept students from the selected course.
- The system shall show the departments and courses accepted by each listed organization.
- The system shall support multiple courses where an organization accepts students from different academic departments.
1.4 Location-Based Filtering
- The system shall allow students to filter SIWES opportunities by state.
- The system shall allow students to filter opportunities by Local Government Area (LGA).
- The system shall display the physical address of each organization.
- The system shall allow students to find opportunities within their preferred locations.
1.5 Company Information and Details
- The system shall display the name of each registered organization.
- The system shall display the organization's address and contact information.
- The system shall display the courses and departments accepted.
- The system shall display the SIWES application requirements.
- The system shall indicate whether the organization provides a stipend.
- The system shall display available information about the organization's SIWES application process.
1.6 Report Outdated Information
- The system shall allow users to report incorrect or outdated company information.
- The system shall allow users to select the type of information they believe is incorrect.
- The system shall allow the administrator to review submitted reports and update company information.
1.7 Administrator Dashboard
- The system shall allow administrators to log in to an administrative dashboard.
- The administrator shall be able to add new companies and organizations.
- The administrator shall be able to edit or delete existing company information.
- The administrator shall be able to update the courses accepted by each organization.
- The administrator shall be able to manage student-submitted reports about outdated information.
- The administrator shall be able to manage the list of available courses, states, and LGAs.
1.8 Search Results and Navigation
- The system shall display search results in an organized format.
- The system shall allow students to view the full details of a selected organization.
- The system shall display a helpful message when no matching SIWES opportunities are found.
- The system shall allow students to return to their search results without starting a new search.

## 2. Non-Functional Requirements (Non-Functionalities)
Non-functional requirements describe how the system should operate, including its performance, security, reliability, usability, and accessibility.
2.1 Usability
- The system shall have a simple, user-friendly interface that students can easily understand.
- The system shall provide clear navigation between different pages.
- Students should be able to search for SIWES opportunities without requiring technical knowledge.
- Company information shall be presented in a clear and organized format.
2.2 Performance
- The system should display search results within 3–5 seconds under normal operating conditions.
- The system should load pages quickly, even when multiple companies are listed.
- The system should handle multiple students searching for opportunities simultaneously.
2.3 Security
- The system shall protect students' personal information.
- Passwords shall be stored securely using appropriate password hashing.
- Only authorized administrators shall be able to access the administrative dashboard.
- The system shall validate user inputs to prevent unauthorized or harmful data submissions.
2.4 Reliability
- The system should be available whenever students need to search for SIWES opportunities.
- The system should display accurate company information based on the latest verified updates.
- The system should handle errors without crashing.
- The system should provide appropriate error messages when an operation fails.
2.5 Maintainability
- The system should be designed in a way that allows developers to update and maintain it easily.
- New companies, courses, and locations should be added without rebuilding the entire system.
- The system should allow administrators to update existing information when organizations change their SIWES policies.
2.6 Compatibility
- The website should work on popular web browsers such as Google Chrome, Microsoft Edge, Firefox, and Safari.
- The system should be accessible on smartphones, tablets, and desktop computers.
- The interface should adjust properly to different screen sizes.
2.7 Scalability
- The system should support an increasing number of students and organizations as it grows.
- The database should accommodate additional courses, companies, states, and LGAs.
- The system should be capable of expanding from one faculty to other faculties and institutions.
2.8 Data Accuracy
- Company information should be reviewed and updated regularly.
- The system should clearly indicate when company information was last verified.
- The system should distinguish between verified information and information awaiting verification.
- Administrators should be able to investigate and correct reported inaccurate information.
