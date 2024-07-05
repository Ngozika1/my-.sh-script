ask
Your company has employed many new developers. As a SysOps engineer, write a bash script called create_users.sh that reads a text file containing the employee’s usernames and group names, where each line is formatted as user;groups.
The script should create users and groups as specified, set up home directories with appropriate permissions and ownership, generate random passwords for the users, and log all actions to /var/log/user_management.log. Additionally, store the generated passwords securely in /var/secure/user_passwords.txt.
Ensure error handling for scenarios like existing users and provide clear documentation and comments within the script.
Also write a technical article explaining your script, linking back to HNG
Requirements:
Each User must have a personal group with the same group name as the username, this group name will not be written in the text file.
A user can have multiple groups, each group delimited by comma ","
Usernames and user groups are separated by semicolon ";"- Ignore whitespace
e.g.
light; sudo,dev,www-data
idimma; sudo
mayowa; dev,www-data
For the first line, light is username and groups are sudo, dev, www-data
Technical Article: The article should be well-structured.
It MUST include at least two links to the HNG Internship websites; choose from any of https://hng.tech/internship, https://hng.tech/hire, or https://hng.tech/premium so others can learn more about the program.
The report should be concise.
The article should be public and accessible by anyone on the internet.
Acceptance Criteria:
Successful Run: The mentors will test your script by supplying the name of the text file containing usernames and groups as the first argument to your script (i.e bash create_user.sh <name-of-text-file> ) in an Ubuntu machine.
All users should be created and assigned to their groups appropriately
The file /var/log/user_management.log should be created and contain a log of all actions performed by your script.
The file /var/secure/user_passwords.csv should be created and contain a list of all users and their passwords delimited by comma, and only the file owner should be able to read it.
The technical article is clear, concise and captures the reasoning behind each step in your script.
Submission Mode:
Submit your task through the designated submission form Ensure you’ve:
Double-checked all requirements and acceptance criteria.
Provided a link to your GitHub repository containing your file in the submission form.
Thoroughly reviewed your work to ensure accuracy, functionality, and adherence to the specified guidelines before you submit it.
Provided a link to your technical article containing the reasoning behind your specific implementation.
PS:
Use a new repository for this task and your script should be in the root directory
Your repo should contain only 2 files - README.md, create_users.sh
Submission Deadline:
The deadline for submissions is Wed 3rd July, at 11:59 PM GMT. Late submissions will not be entertained. (edited) 
hng.techhng.tech
HNG Internship | HNG
Learn from the best in the game and become world-class!
hng.techhng.tech
HNG
Start your journey to becoming a world-class developer today!
hng.techhng.tech
HNG Premium
Learn from the best in the game and become world-class!
Google DocsGoogle Docs
HNG 11 Stage 1 - DevOps Track Submission Form
Kindly read this very carefully before submitting!
This is the submission form for HNG11: DevOps Track Stage 1. You were given a task to write a Linux Bash Script.
Ensure you submit the correct link in the correct input field below. Submitting a wrong link and/or private link will lead to automatic failure.
Good luck!
https://forms.gle/8SiPKuwbEjViWRbKA

:white_check_mark:
12
:bananadance:
2
:orange_heart:
1
:img_8417:
2
:slightly_smiling_face:
1






9+
48 replies
Last reply today at 2:58 AMView thread


bolex_is_away
:star:  10:05 PM
@channel your devops task is above 
:raised_hands:
2
:100:
1



buka
:stars:  1:10 AM
set the channel topic: :rotating_light: FOR PROJECT ANNOUNCEMENTS ONLY! PLEASE DON’T POST HERE :rotating_light:
:white_check_mark:
7

Pinned by 
Rotimi


zxenon__
:stars:  9:34 AM
@channel
Stage 1 Task - Product Testing (QA) -  Bug Hunting on SAW :mag:
Study Material:
How to Write a Good Bug Report: Some Tips
Bug Report Template
Scrape Any Web
SAW - Windows Store
Task: Bug Hunting on SAW
This stage introduces you to the fundamentals of bug reporting. Here's what you'll do:
Download and Install SAW:
SAW (ScrapeAnyWebsite) is a Windows application designed to scrape and extract data from various websites. It provides a user-friendly interface to help users gather and organize information from the web efficiently.
Download SAW from the Windows Store. - Download the application from the Windows Store not from the website.
Install the application on your Windows device.
Exploratory Testing:
SAW Application: Launch SAW and thoroughly explore its functionalities. Identify any bugs, usability issues, or inconsistencies you encounter during your exploration.
Focus Areas: Test the features of the application, try to break the app, and find at least 3 bugs. Pay special attention to the most severe and critical bugs, focusing on areas that might have usability issues, performance issues, or security vulnerabilities. Test both the happy paths and the edge cases.
Test Reporting: Document your testing findings using the provided Bug Report Template. Ensure your report includes the following sections:
Description: A short description that describes the exact problem you faced.
Environment: Details about the environment where you encountered the problem (e.g., operating system, app version).
Visual Proof: Include a screenshot or video that demonstrates the issue.
Steps to Reproduce: Specific steps to reproduce the issue.
Expected Result: What you expected to happen.
Actual Result: What actually happened.
Severity: The impact of the bug (e.g., critical, major, minor).
:scroll: Requirements:
Bug Report Format:The bug report should be submitted in an Excel sheet following the provided template.
Specify the name and version of the SAW application tested.
Briefly describe the exploratory testing approach used.
List all identified issues using the template. Ensure each issue is thoroughly documented with clear descriptions, steps to reproduce, and visual proof.
Accurately categorize each issue based on its severity.
Blog postIn addition to the bug report, write a comprehensive blog post highlighting your findings and suggesting improvements.
In your blog post, include a link to Scrape Any Website and the Windows Store download page, ensuring to link to the download page instead of the website directly.
Use 'Scrape Any Website' with spaces as the anchor text for these links.
Include a link to your bug report.
:memo: Acceptance Criteria:
Ensure all specified testing areas (functional, usability, performance, security, compatibility) are covered for the SAW software.
All issues must be clearly documented using the standard template.
Issues should be categorized accurately by severity.
The bug report should be well-structured, clear, and comprehensive.
The report must be formatted professionally and include all required sections.
The blog post should be well-written, clear, and free from grammatical errors.
The post should have a clear introduction, body, and conclusion.
Include relevant screenshots or videos to illustrate the bugs and issues found.
Links:Include a link to Scrape Any Website with the anchor text 'Scrape Any Website'.
Include a link to the Windows Store download page with the anchor text 'Scrape Any Website'.
Ensure the links point to the correct URLs and use the specified anchor text.
Include a link to the bug report in your blog post.
The blog post should be professionally formatted and visually appealing.
All information provided should be accurate and based on your testing experience.
:pushpin: Submission Mode: Submit your task through the designated submission form. Ensure you've:
Double-checked all requirements and acceptance criteria.
Uploaded the completed Excel sheet with the bug report in the submission form.
Granted view access to the Excel sheet.
Thoroughly reviewed your work to ensure accuracy, functionality, and adherence to the specified guidelines before you submit it.
:checkered_flag: Submission Deadline: The deadline for submissions is Tuesday, 2nd July 2024 at 11:59 PM GMT +1. Late submissions will not be entertained. (edited) 
:smiling_face_with_tear:
7
:+1::+1::skin-tone-4:
15
:white_check_mark:
5