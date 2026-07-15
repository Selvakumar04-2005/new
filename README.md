# Selvakumar K — Portfolio Website

Personal portfolio website for **Selvakumar K**, ServiceNow Certified Application
Developer (CAD) and Information Technology undergraduate at Karpagam Institute
of Technology, Coimbatore.

## Sections
- **Home** — introduction with a typing animation of core skills
- **About** — profile summary, contact details, and downloadable resume
- **Skills** — ServiceNow, Java, Spring Boot, MySQL, AWS, Firebase, Git and more
- **Education** — B.Tech (IT), HSC, and SSLC academic history
- **Work** — featured projects (Blood Donation Management System, System Log
  Tracker REST API, Student Management System)
- **Achievements** — certifications (ServiceNow CAD, AWS, Deloitte, Google,
  MongoDB) and Smart India Hackathon 2025 participation
- **Contact** — contact form that opens a pre-filled email to
  selvakumarammugkavery@gmail.com

## Tech
Plain HTML, CSS and JavaScript (jQuery), with Typed.js, Particles.js,
ScrollReveal and Vanilla-Tilt for animation/interaction.

## Structure
```
index.html          Home page (single-page sections)
projects/            Full projects listing page
experience/          Full certifications & achievements page
assets/css/          Stylesheets
assets/js/           Scripts
assets/images/       Images (hero, profile, project thumbnails, favicon)
assets/files/        Downloadable resume PDF
skills.json          Skill list rendered on the home page
projects/projects.json  Project list rendered on the home & projects pages
```

## Running locally
This is a static site — no build step required. Serve the folder with any
static file server, e.g.:
```bash
npx serve .
```
