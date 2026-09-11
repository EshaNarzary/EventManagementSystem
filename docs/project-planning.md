# EventManage – Project Planning & Requirement Analysis

## 1. Project Title
EventManage – Event Management System

## 2. Problem Statement
Organizing events such as college fests, seminars, workshops, and community gatherings is often done manually through spreadsheets, phone calls, and paper registration forms. This makes it difficult for organizers to manage attendee registrations, track venue and schedule details, coordinate staff, and monitor event progress.

The people affected are event organizers, administrators, participants, and venue/staff coordinators. A centralized web application is needed to streamline event creation, registration, and management, reduce manual errors, and give organizers real-time visibility into event status and attendance.

## 3. Project Objective
To develop a web-based Event Management System that enables organizers to create and manage events, handle participant registrations, track schedules and venues, and monitor event status through a centralized dashboard.

## 4. Target Users / Stakeholders

### Administrator
- Manages users and user roles.
- Monitors all events and system reports.
- Manages system settings.

### Event Organizer
- Creates and manages events.
- Sets event schedule, venue, and capacity.
- Manages participant registrations.
- Reviews event reports and attendance.

### Participant
- Browses and searches available events.
- Registers for events.
- Views registration status and event details.
- Manages their own profile.

## 5. Core Modules
1. User Management
2. Authentication and Role-Based Authorization
3. Event Management
4. Registration Management
5. Venue & Schedule Management
6. Attendance Tracking
7. Dashboard and Reports

## 6. Project Scope

### Included Features
- User registration and login.
- JWT-based authentication.
- Role-based authorization for Administrator, Event Organizer, and Participant.
- User profile management.
- Create, view, update, and delete events.
- Set event date, time, venue, and capacity.
- Participant registration for events.
- View list of registered participants per event.
- Update event status: Upcoming, Ongoing, Completed, Cancelled.
- Dashboard showing event and registration statistics.
- Basic event and attendance reports.
- Responsive web interface.

### Excluded Features
- Native mobile application.
- Video conferencing / live streaming.
- Real-time chat.
- AI-based event recommendations.
- Calendar synchronization with external apps.
- Email/SMS notification services.
- Payment gateway for paid events.
- QR-code based check-in system.

## 7. Functional Requirements

### Authentication and Users
- The system shall allow new users to register.
- The system shall allow users to log in and log out.
- The system shall securely authenticate users using JWT.
- The system shall restrict features based on user roles.
- The system shall allow users to view and update their profile.

### Events
- An Event Organizer shall be able to create an event.
- An Event Organizer shall be able to view, edit, and delete events they manage.
- The system shall display event name, description, date, time, venue, capacity, and status.
- The system shall allow an Event Organizer to set a maximum participant capacity for an event.

### Registrations
- A Participant shall be able to browse and search available events.
- A Participant shall be able to register for an event.
- The system shall store registration details including participant, event, and registration date.
- The system shall prevent registration once an event reaches its capacity.
- An Event Organizer shall be able to view and manage the list of registered participants.
- Authorized users shall be able to cancel a registration.

### Dashboard and Reports
- The system shall display event summaries on a dashboard.
- The system shall display registration counts per event.
- The system shall show upcoming and ongoing events.
- The system shall generate basic event-attendance and registration reports.

## 8. Non-Functional Requirements

### Security
- Passwords must be hashed before storage.
- Protected API routes must require a valid JWT.
- Role checks must prevent unauthorized access.
- User input must be validated.

### Performance
- Normal pages and API responses should load promptly under expected classroom-scale usage.
- Database queries should be designed efficiently.

### Usability
- The interface must be responsive on desktop and mobile browsers.
- Navigation and event registration must be simple and clear.
- Validation errors must be understandable.

### Reliability
- The system should handle invalid requests without crashing.
- Important errors should return meaningful messages.

### Maintainability
- The backend must use modular routes, controllers, models, and middleware.
- The frontend must use reusable React components.
- Code should be organized and documented.

### Scalability
- The design should allow later additions such as QR check-in, payment gateway, notifications, and calendar sync.

## 9. Expected Outcome
EventManage will provide a centralized platform where organizers can create and manage events, participants can discover and register for events, and administrators can oversee the entire system. It will give students practical experience with MERN development, REST APIs, MongoDB relationships, JWT authentication, role-based access control, and team collaboration through GitHub.