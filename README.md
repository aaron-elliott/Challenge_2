# Project Title

Just after the title, introduce your project by describing attractively what the project is about and what is the main problem that inspires you to create this project or what is the main contribution for the potential user of your project.

"This application takes user-specific infomration and quickly filters out any loan for 
which the user is unlikely to be qualified.

The application increases the efficiency of the loan appliation process by pre-screening applicants and then
matching applicants' to loan types and institutions best suited to meet the needs of the particular applicant
while ensuring that the applicants meet minimum lending requirements for the loan type which they are seeking."


---

## Technologies

Describe the technologies required to use your project such as programming languages, libraries, frameworks, and operating systems. Be sure to include the specific versions of any critical dependencies that you have used in the stable version of your project.

Requirements for use:
    Gitbash for Windows 7 or 10 
    Terminal for Mac OSX
    Python (3.8.8 recommended)
    Visual Studio Code
    Libraries:
        Fire
        Questionary

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.
Set up for Application use:
    Use cd & ls to navigate to the proper location
    Check python version using "python --version"
    Install fire library using "pip install fire"
    Install questionary library using "pip install questionary"
    
 

---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

How to start the application:
    Ensure that all applicaple files are installed (calculators.py, fileio.py, max_loan_size.py, loan_to_value.py, debt_to_income.py, credit_score.py, app.py, and daily_rate_sheet.csv)
    Run application with "python app.py"
    When prompted for csv, input location of daily_rate_sheet.csv
    Follow prompts for inputting application data e.g."What's your credit score?"
    After answering all of the prompts, the application will print a list of qualifying loans into the terminal and also create a csv of the qualifying loans in a document called "qualifying_loans.csv."
        *if you do not want the loans list to print in the terminal, you can delete the code in line 144 "print(qualifying_loans)

---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

https://www.linkedin.com/in/aaron-elliott85/
https://www.linkedin.com/in/kirkdotcam/
https://www.linkedin.com/in/calebmcbride/
https://www.linkedin.com/in/jonathan-randolph-37177a91/


---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
