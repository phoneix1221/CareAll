# CareAll
console application for taking care of old people by caretakers(young people)

This is a console application written in python with connectivity with sqlite3 database

Some feature of application
1) signin and signup for both type of users (caretakers and care needers).
2) differentiate between care taker and care needer based on age criteria( if age<60 you can signup for caretaker else if age>60 you can      signup for care needer)
3) Both type of users can search each other.
4) carenneder can allocated fund for caretakers.
5) caretaker can send request to careneender and if accepted by carenneeder caretaker will be assigned to careneeder and the fund will be      transfered to caretaker wallet.

6) Both type of users can broke the contract for caretaking and careneeding.

7) Both type of users can give rating/review to opposite category users (only who they are assigned) you cannot give rating /review to anyone who you didnt work with till now.

8) can see reviews/rating of opposite category user.

Execution:
Step 1

Install this required packages before execution

1)bcrypt

Step 2

run app.py from terminal which can be found in path careall\projectfiles\


Recomendation:
I haven't applied any form input check so plz type inputs carefully otherwise you will run into errors.
