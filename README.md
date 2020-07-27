# Instructions
## Introduction
The web app we are constructing this semester is a website for members only that will allow general public to become a member of the site. The members will have access to some content,  developed throughout the semester, upon successful login.

## Prerequisites

We use the Progressive Enhancement (PE) approach to complete each project. The PE process consists of three phases:
-   **Phase I:**  Build solid foundation with HTML5. Identify content and use the most suitable (meaningful) markup to organize it. All content must be accessible without styles.
-   **Phase II:**  Using well-formed and valid HTML5, style the elements for best presentation. All content must be accessible without scripts.
-   **Phase III:**  Using well-formed and valid HTML5 styled with well-formed and valid CSS3, add behaviour with Javascript.

All code follows 

## Requirements

- Use the [template.html](template.html) as initial HTML and CSS code. All pages share the same CSS.  Customize the content appropriately.
- Create site sub-tree on dev.fast.sheridanc.on.ca. (use internal CSS and Javascript, no images), name your public home page index.php (with the login form) -- all php files in the root directory of the project.
- Create "member" table through cPanel > phpmyadmin in `username_assignments` database
- Complete Exercise 11-3, Worksheet 11 to create the login page, registration page.
- Database connection must be implemented with PDO.
- Include internal Javascript to guide user to choose a strong password and to compare the two password fields are the same.
- Save credentials in a separate file `dbinfo.php` and change permissions to be executable only (use your Linux class knowledge).
- Upon successful login, re-direct user to the home page (see [image](content_page.png) ) and allow them to play tic tac toe. 
- Logout signs them out and redirects to the public login page.

## Evaluation

Read How evaluation works and Coding style as posted for previous assignments.

Your assignment will be evaluated by running your app on the dev.fast server.  I will attempt to log in with credentials that I select, first to ensure that the login fails, then I will register with the selected credentials, then login as a new member, to view member-only content. Finally, log out to ensure I can no longer access it. 


## Resources

See SLATE material and class recordings.

---

> SYST10199 Web Programming @ Sheridan College
