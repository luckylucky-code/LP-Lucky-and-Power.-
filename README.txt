LP (Lucky and Power) — Recruitment Website Package
=====================================================

PUBLIC WEBSITE
--------------
index.html
- Responsive LP Careers website
- Official LP logo embedded in the page
- Marketing, Finance, Human Resources, and Production openings
- Professional/experienced applicant requirements
- Application form
- Mobile responsive navigation

RECRUITER DASHBOARD DEMO
------------------------
admin-dashboard.html
- Separate recruiter-facing dashboard design
- Applicant counts and application table
- Demonstrates how the internal side can look

REAL APPLICATION RECEIVING
--------------------------
A static website cannot securely store uploaded resumes by itself. The recommended
simple setup for the school/company project is:

LP Website
    -> Google Form application
    -> Google Sheets (applicant list)
    -> Google Drive (uploaded resumes/supporting documents)
    -> Recruiter reviews the responses

Google Forms supports File upload questions and copies uploaded files to the
form owner's Google Drive. This is suitable for collecting resumes.

TO FINISH THE LIVE VERSION
--------------------------
1. Create a Google Form using the fields in the website:
   Full Name
   Email
   Contact Number
   Position
   Educational Background
   Work Experience
   Skills
   Resume/CV (File upload)
   Supporting Documents (File upload)
   Cover Letter / Message

2. In the form, turn on File upload for Resume and Supporting Documents.
3. Link the form to Google Sheets.
4. Replace the website's demo form submit action with the Google Form URL,
   or embed the Google Form in the Apply section.
5. Keep the response sheet and Drive folder restricted to authorized recruiters.

LIVE WEBSITE
------------
GitHub Pages can host this static website publicly. The exact live URL depends
on the GitHub account/repository name. Do not put private applicant data in the
public repository.

Files:
- index.html
- admin-dashboard.html
- lp-logo.jpg
- README.txt
