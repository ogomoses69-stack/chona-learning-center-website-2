CHONA AND LEARNING CENTER — WEBSITE
=====================================

This is the source code for the Chona and Learning Center school website
(Okpoma, Onicha LGA, Ebonyi State, Nigeria).

FILE STRUCTURE
--------------
index.html              Main page markup (all sections: hero, about,
                         academics, facilities, admissions, portals,
                         gallery, contact, footer)
style.css                All styling (colors, layout, responsive rules,
                         light/dark theme support)
script.js                Site behavior: mobile nav toggle, contact form
                         (opens the visitor's email app with the
                         message pre-filled)
assets/images/logo.jpg           School crest
assets/images/school-building.jpg   Photo of the school building
README.txt                This file

HOW TO VIEW IT LOCALLY
-----------------------
Just double-click index.html to open it in any web browser. No server,
build step, or install required — it's plain HTML/CSS/JS.

HOW TO PUT IT ON GITHUB PAGES (free hosting)
----------------------------------------------
1. Create a GitHub account and a new repository
   (e.g. "chona-learning-center").
2. Upload ALL of these files and folders, keeping the same structure:
     index.html
     style.css
     script.js
     assets/images/logo.jpg
     assets/images/school-building.jpg
3. In the repo, go to Settings -> Pages.
4. Under "Source," choose the main branch and "/ (root)" folder, then Save.
5. GitHub will give you a live link like:
     https://yourusername.github.io/chona-learning-center/

HOW TO PUT IT ON YOUR OWN DOMAIN / HOSTING
---------------------------------------------
Upload the same files (keeping the folder structure) to your web host's
public/www folder via their file manager or FTP, so that index.html
sits at the root of the domain.

THINGS TO UPDATE LATER
------------------------
- Replace/add more real photos in assets/images/ (classrooms, staff,
  students in class) and reference them in the Gallery section of
  index.html.
- The "Student / Parent / Teacher portal" and "Online result checking"
  sections are placeholders (marked "Coming soon") — they need a real
  backend/database before they can actually log anyone in or show
  results.
- The contact form currently just opens the visitor's email app with
  their message pre-filled (no server). To make it submit silently in
  the background, it would need to be connected to a form backend
  (e.g. Formspree) or a custom server script.
- Update phone/email/social links in the footer and contact section if
  they ever change.

Built as a static HTML/CSS/JS site — no frameworks, no build tools,
no dependencies to install.
