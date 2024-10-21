# intern-portal
This platform will serve as a centralized system for the dsaStats team, allowing interns and admin staff to manage intern information, monitor team projects, and ensure smooth collaboration within the team.
### Important Note! Ensure to sync all the changes made to the Origin ( Main ) branch of this repo with your forked repo, before pushing any code.

## Tech Stack 
HTML CSS JS
NODEJS + EXPRESS + PostGres

Here is a structured outline for the README.md file for your project:

---

## Features Overview

### Login and Signup Pages

- **Header:**
  - Title: "Welcome to dsaStats," animated with a fade-in effect.
  - Navigation Links: "Login," "Signup," and "Intern Login" for easy switching.

- **Custom Cursor:**
  - Cursor design changes appearance when hovering over interactive elements.

#### Login Form (Standard User):
- Email/Username Field: Simple input field.
- Password Field: Includes visibility toggle.
- Remember Me Checkbox: Standard functionality.
- Login Button: No additional effects.
- Forgot Password Link: Redirect to password reset page.
- Social Media Login: Available option for quick login.

#### Exclusive Intern Login Form:
- Employee ID Field: Features animated effects when focused.
- Password Field: Includes strength meter and visibility toggle.
- Login Button: Hover animation (glow/pulse).
- Redirect: Upon successful login, interns are redirected to the intern dashboard.

#### Signup Form:
- **Fields:** Name, Email, Password, Confirm Password.
- Animated features for placeholders and real-time feedback.
- Signup Button: Animates on hover/click.
- Terms and Conditions Checkbox: Animated rotation effect.
- Redirect to login page for existing users.

#### Password Reset Page:
- **Fields:** Email input with underline animation.
- Reset Button: Ripple effect on click.
- Back to Login Link: Fade-in animation.

### Interactive Animations:
- Background animations respond to cursor movement.
  
### Footer:
- Support Contact: Expanding text effect.
- Copyright Information: Slide-in on scroll.

---

## Admin Dashboard

- **Employee and Intern Overview:** Details viewable by team leaders and super admins.
- **Project Management:** Super Admin can move interns between projects, create new projects, and assign team leads and interns.
- **Feedback System:** Super Admin and Team Leaders can give feedback to interns.
- **Intern of the Month:** Voting system for team leaders and super admin.

---

## Team Page

- **Header:**
  - Title: "Meet Our Interns."
  - Search Bar: Real-time filtering by name or role.

- **Intern Cards:**
  - Display Profile Image, Name, Role, and Social Media Links.
  - **Read More Button:** Redirects to portfolio page with details like bio, experience, skills, and contact info.

- **Footer:**
  - Copyright Information.

---

## Intern Profile Page

- **Editable Components:**
  - Full Name, Role, Self-Description, Profile Photo, Achievements, Social Media Links.
  - Toggle Edit Mode for all fields except Employee ID.

---

## Project Showcase Page Design

- **Dynamic Scrolling Interaction:**
  - Split-view div for project description and demo video synced with scrolling.
  - Links to GitHub repository and intern profile.

- **Homepage Project Section:**
  - Split-text animation for the introduction.
  - Card carousel for projects, with zoom and demo video on hover.

### Technologies:
- **GSAP (GreenSock Animation Platform):**
  - Scroll Trigger: Syncs scrolling with content updates.
  - Split-text: Engaging split-text animation.
  - Hover Animations: Smooth zoom and video play effects.

### Benefits:
- Engaging and interactive user experience.
- Easy navigation of projects.
- Professional appeal with animations and content synchronization.

---

## Technologies Used
- HTML5, CSS3
- JavaScript, GSAP
- Node.js (Backend)
- PostgreSQL (Database)


## Contribution
Feel free to submit pull requests for any improvements or issues.

