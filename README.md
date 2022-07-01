# Loan Qualifier Application

A command line inerface application that finds lenders that meet the applicant's criteria for a loan request. The Loan Qualifier Application allows for a quick analysis of available loans output to a CSV file at the user's request. The application will ask the user to provide a rate-sheet source file as .csv. Next the application will ask for client data for the loan application. The app will then retrieve a list of lenders based on the financial criteria. The option to save the data to a CSV file is prompted, and the user can choose the filepath on the next prompt.  


---

## Technologies
The Loan Qualifier Application is built on Python 3.9. Libraries installed and used include Python Fire, and Questionary. Operating system: Mac OS 12 Monterey.


---

## Installation Guide
The Loan Qualifier Application runs in Python 3
1. Install python.
2. Load the Loan Qualifier folder in your IDE.
3. Install Fire using the command: pip install fire. Enter the command in Terminal on Mac OS or your Command Line Interface
4. Install Questionary using the command: pip install questionary. Enter the command in Terminal on Mac OS or your Command Line Interface
5. The Loan Qualifier Application is now ready to run in your IDE.
---

## Usage

1. When prompted to enter a file path for the rate sheet copy and paste the .csv filepath to the command line, press ENTER.
2. The next prompt asks for the client's credit score. Enter the credit score and press ENTER.
3. Next, enter the amount of monthly debt. Be sure to not include commas as seperators. Press ENTER. 
4. Next, enter the total monthly income. Be sure to not include commas as seperators. Press ENTER.
5. Next, enter the desired loan amount. Be sure to not include commas as seperators. Press ENTER.
6. Next, enter the home value. Be sure to not include commas as seperators. Press ENTER.
7. The application will return calculations for the monthly debt to income ratio, loan to value ratio, and the number of qualifying loans. 
8. To save a .csv file enter Y when prompted. Press ENTER
9. Enter a file path and use _ as word separators, be sure to specify .csv after you choose a filename.
10. Your file is now saved in the folder that you chose as a .csv file. 

---

## Contributors

Mike Cutno
mikecutno@gmail.com
LinkedIn: https://www.linkedin.com/in/mikefree27/

---

## License

Private
