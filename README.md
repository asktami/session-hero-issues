# session-hero-project-management

Issues, Project, User Stories and Wireframes for Session Hero - Bloc.io Fullstack Capstone.

## App Name: SessionHero

## Top 5 Wireframes
  1. Landing Page
  2. Registration Form
  3. Login Form
  4. Sessions List
  5. Session Detail

## Top 5 User Stories
### 1. As a new user I want to sign up for an account

REGISTRATION FORM
- user enters valid email & password and clicks submit -----> Login Form

--------------------

- user enters invalid email/password and clicks submit -----> error message appears to supply valid email/password

--------------------

- user enters an email that's already in the system -----> message appears that an account already exists with that email, login if its your account



### 2. As a new user I want to log in to my account

LOGIN FORM
- user enters valid email & password and clicks submit -----> SESSIONS LIST page showing all sessions +  "My Schedule" and "Logout" buttons

--------------------

- user enters invalid email/password and clicks submit -----> error message appears to supply valid email/password



### 3. As a new user I want to see sessions (can see all/filter sessions without logging in)
### 4. As a new user I want to filter sessions

SESSIONS LIST
- user, that has NOT logged in, clicks on button to "SHOW ALL" sessions, or uses pulldowns to "FILTER BY DAY" or "FILTER BY TRACK" -----> sees SESSIONS LIST page with sessions that match the filter criteria +  "My Schedule" and "Logout" and "ADD TO SCHEDULE" buttons

--------------------


- user, that HAS logged in, clicks on button to "SHOW ALL" sessions, or uses pulldowns to "FILTER BY DAY" or "FILTER BY TRACK" -----> sees SESSIONS LIST page with sessions that match the filter criteria +  "My Schedule" and "Logout" and "ADD TO SCHEDULE" and "COMMENT" buttons + IF that session is in the user's SCHEDULE, they see text saying "in schedule" instead of the "SCHEDULE" button

--------------------


    - when user, that HAS logged in, clicks on the SCHEDULE button -----> session is added to the user's SCHEDULE and sessions list refreshes to show text saying "in schedule"

--------------------


    - when user, that HAS logged in, clicks on the COMMENT button -----> SESSION DETAIL screen with session details AND list of all COMMENTS and COMMENT ADD FORM


### 5. As a new/returning user I want to see session info

SESSION DETAIL
- user, that has NOT logged in, clicks on Session Name (link) -----> SESSION DETAIL page with list of SESSION COMMENTS

--------------------


- user, that HAS logged in, clicks on Session Name (link) -----> SESSION DETAIL page with list of SESSION COMMENTS AND if an existing COMMENT was created by the user, that COMMENT has UPDATE COMMENT and DELETE COMMENT buttons
