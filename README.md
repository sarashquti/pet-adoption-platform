# Pet Adoption Platform

## Description
This project is developed for the Software Engineering course.
The platform helps people find available pets for adoption and contact shelters easily.

## Problem
People want to adopt pets but struggle to find available animals and contact shelters.

## Solution
A web platform where users can browse pets, view details, and connect with shelters.

## Team
Group D - Group No. 3

Members:
- Sara Shquti (sshquti23@epoka.edu.al)
- Kiara Dedaj (kdedaj23@epoka.edu.al)
- Mateo Farrici (mfarrici23@epoka.edu.al)
- Iris Lushaj (ilushaj23@epoka.edu.al)
- Sonia Selmanaj (sselmanaj23@epoka.edu.al)

## Features
- Browse available pets
- View pet details
- Contact shelters

# Phase II: User Requirements and Application Specifications  

## Chosen Development Model  

Development Model: Agile  

Justification:  
The Agile development model was selected because it supports flexibility, continuous feedback, and iterative improvement. It allows the team to adapt to changing requirements and improve the system step by step while collaborating effectively.  

## User Requirements  

### Stakeholders  

- End Users (Adopters): Browse and adopt pets  
- Animal Shelters: Upload and manage pet listings  
- Pet Owners: Offer pets for adoption  
- Admin: Manage users, listings, and system operations  

### User Stories  

1. As a user, I want to register so that I can create an account.  
2. As a user, I want to log in so that I can access my account.  
3. As a user, I want to browse pets so that I can see available animals.  
4. As a user, I want to search pets so that I can find specific ones.  
5. As a user, I want to filter pets so that I can narrow results.  
6. As a user, I want to view pet details so that I can make decisions.  
7. As a user, I want to schedule a meeting so that I can adopt a pet.  
8. As a shelter, I want to upload pets so that users can see them.  
9. As a user, I want to contact pet owners so that I can ask questions.  
10. As an admin, I want to manage users so that the system stays organized.  

## Functional Requirements   

### Description  
1. The system shall allow users to register and log in.  
2. The system shall display pet listings with images and descriptions.  
3. The system shall allow users to search and filter pets.  
4. The system shall allow users to view detailed pet information.  
5. The system shall allow users to schedule adoption meetings.  

### Acceptance Criteria  

#### User Login  
- User enters email and password  
- System verifies credentials  
- User is redirected to dashboard  
- Error message is shown for invalid login  

#### Pet Listings  
- Pets are displayed with images  
- Users can click on a pet to view details  

#### Search & Filter  
- Filters work correctly  
- Results update instantly  

#### Pet Details  
- Full information is displayed  
- Images are visible  

#### Meeting Scheduling  
- User selects date and time  
- System confirms booking  

## Non-Functional Requirements  

### Description  

1. The system should load quickly.  
2. The system should be responsive on all devices.  
3. The system should have a user-friendly interface.  
4. The system should ensure data security.  
5. The system should be reliable and stable.  
6. The system should support multiple users simultaneously.  
7. The system should handle errors gracefully. 
8. The system should have fast search functionality.  
9. The system should ensure data consistency.  
10. The system should provide clear navigation.  
11. The system should have high availability.  
12. The system should protect user privacy.  
13. The system should support scalability.  
14. The system should provide quick response times.  
15. The system should have minimal downtime.  
16. The system should support secure authentication.  
17. The system should store data safely.  
18. The system should provide a smooth user experience.  
19. The system should be compatible with major browsers.  
20. The system should prevent unauthorized access.  
21. The system should have efficient database performance.  
22. The system should allow easy maintenance.  
23. The system should support future upgrades. 
24. The system should display data accurately. 
25. The system should ensure system integrity.
    
### Acceptance Criteria  
- Pages load in under 2 seconds  
- System supports multiple concurrent users  
- Search results appear in under 3 seconds  
- No data loss occurs  
- System uptime is above 99%  

## Application Specifications  

### Architecture  
The system follows a three-tier architecture consisting of a frontend (user interface), backend (business logic), and database. The frontend handles user interaction, the backend processes requests and manages logic, and the database stores all user and pet information efficiently.  

### Database Model  
The database is structured with tables such as Users, Pets, Bookings, and Shelters. Each user can interact with multiple pets, and each booking connects a user with a specific pet. Relationships are maintained using unique identifiers and foreign keys to ensure data integrity.  

### Technologies Used  
The system is developed using HTML, CSS, and JavaScript for the frontend to create a responsive interface. The backend uses Python for handling logic and server-side processing, while MySQL is used as the database for efficient data storage and management.  

### User Interface Design  
The user interface includes a login/register page, a pet browsing page, a pet details page, and a booking page. The design is simple, intuitive, and user-friendly, ensuring easy navigation and clear interaction for all users.  

### Security Measures  
The system implements user authentication with secure login credentials, encrypts passwords before storage, and uses role-based access control to differentiate between users and admins. It also ensures data protection and prevents unauthorized access.  
