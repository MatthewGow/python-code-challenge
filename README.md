# Python Coding Challenge
Take a deep breath, it's not too bad.

Inside this repo you will find a JSON formatted file containing employee data for The Example Company.

### THE ASSIGNMENT
You have been tasked with writing a lookup tool for The Example Company.
This will allow the user to lookup information on Employees based on their first name, last name, email address, or position at the company.

### EXPECTATIONS
- This script should optionally allow multiple or all lookup criteria to be provided.
For example, if the following arguments are provided, it should return the Employee information if an employee matches all given criteria. 
python employee_lookup.py --first-name "Matthew" --last-name "Gow" --position "Software Engineer" --email "mgow@example.com"

- The script may also be involked with just one of the aruments and should return any matching employee data, for example:
python employee_lookup.py --email "mgow@example.com"

- If there are multiple matches to supplied criteria, the script should return all employees who match that criteria.
For example, if you are looking for all Employees named 'Tim' the following arguments should return all Tims:
python employee_lookup.py --first-name "Tim"

- You may format the scripts output however you would like.

- The script should include logging for any important information, it's up to you to determine how much and what information to log.

- It is up to you if you want to enforce case sensitvity in your lookups.

### BONUS CHALLENGE
>Oh no! There are duplicates in the data! 
Figure out a way to prevent any duplicates from getting printed to the user.
It may be assumed that an email address is assigned to each unique employee.
>  
>NOTE: Do NOT edit the employee.json file!
