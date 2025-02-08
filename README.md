# Job Portal with Resume Builder & Interview Scheduler

This project is a job portal application designed to connect job seekers with companies. It allows users to create and update resumes using pre-built templates, apply for jobs, and schedule interviews. Companies can post job listings, and the platform includes features like interview scheduling with email notifications and reminders. Additionally, there is an admin panel to manage users, job posts, and interviews, making it a comprehensive tool for both candidates and employers.

## Key Features

### Frontend
- React: The frontend is built with React, offering a dynamic and responsive user interface.
- Dynamic Forms: Users can fill out forms to create and update their resumes, using pre-built templates for easy customization. The forms include sections for personal details, work experience, education, skills, and more.
- Interview Scheduling Interface: Job seekers can schedule interviews with companies using an easy-to-use interface that allows them to choose available time slots.
- User Dashboard: Both job seekers and companies have dashboards to manage their profiles, job applications, and postings.

### Backend
- Java & Spring Boot: The backend is developed with Java using Spring Boot, providing a robust and secure platform to manage user accounts, job listings, applications, and interview scheduling.

### Resume Builder
- Pre-built Resume Templates: Job seekers can select from multiple resume templates and fill out the necessary information to create a professional-looking resume.
- Resume Editing: Users can edit and update their resumes anytime to match different job applications.

### Job Postings & Applications
- Job Listings: Companies can post job listings, including job titles, descriptions, qualifications, and application instructions. 
- Direct Applications: Job seekers can apply directly for jobs by submitting their resumes via the platform.
  
### Interview Scheduling
- Calendar Interface: Job seekers can select from available interview slots set by the company.
- Email Notifications: Both candidates and companies will receive email notifications when an interview is scheduled or updated, with reminders leading up to the event.

### Admin Panel
- User Management: Admins can manage user accounts, including job seekers and employers, view resumes, and approve or reject job applications.
- Job Post Management: Admins can view, edit, and delete job postings submitted by companies.
- Interview Management: Admins can manage scheduled interviews, modify times, or send reminders.

## How It Works

1. Frontend:
   - The React frontend includes dynamic forms for creating and editing resumes. Users can select from pre-built templates, input their information, and download their resumes in PDF format.
   - The interview scheduling interface allows candidates to choose available interview slots from a calendar and confirms their selections.
   - The user dashboard lets job seekers track job applications and interview schedules, while companies can view and manage job posts.

2. Backend:
   - The Spring Boot backend handles authentication, job post management, resume storage, and interview scheduling.
   - JWT Authentication ensures that users can securely log in and access their data.
   - The backend also sends email notifications for interview scheduling and reminders, using tools like Spring Mail or an external email service (e.g., SendGrid).
   - Data like resumes, job posts, and interview schedules are stored securely in a database (e.g., MySQL or PostgreSQL).

3. Resume Builder:
   - Job seekers can choose from a variety of pre-built resume templates and fill in the necessary fields (e.g., name, contact details, skills, work experience).
   - The application will allow users to update their resumes and download them in PDF format for job applications.
  
4. Job Postings & Applications:
   - Employers can create job listings that include job titles, descriptions, requirements, and application instructions.
   - Job seekers can search for jobs based on categories or filters, view job details, and apply by submitting their resumes.

5. Interview Scheduling:
   - Companies can set up available interview time slots.
   - Job seekers can pick a suitable time from the available slots and schedule their interviews accordingly.
   - Email notifications will be sent to both candidates and companies with details about the interview, including reminders before the scheduled time.

6. Admin Panel:
   - Admins have access to a dashboard where they can manage users, job posts, and interviews.
   - Admins can approve or reject job applications and schedule interviews for job seekers if necessary.


## Technologies Used

- Frontend: React, React Hooks, Dynamic Forms, Email Scheduling, FullCalendar (for scheduling)
- Backend: Java, Spring Boot, Spring Security, Spring Mail (for sending emails)
- Authentication: JWT (JSON Web Tokens)
- Database: MySQL or PostgreSQL (for storing user data, resumes, job posts, applications, interviews)
- Resume Builder: Pre-built templates for easy resume creation
- Email Notifications: Spring Mail / SendGrid or SMTP for interview notifications
