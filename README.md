# Password-Strength-checking
Password-Strength-Checker
Password Generator and Strength Checker
This is a Streamlit-based web application that allows users to generate secure passwords and check their password strength.

Features
Password Generator:
Customize password length (8-25 characters)
Include/exclude uppercase letters, lowercase letters, numbers, and special characters
Generates a secure random password based on user preferences
Password Strength Checker:
Analyzes the strength of a given password
Provides feedback on whether the password is Very Weak, Weak, Medium, Strong, or Very Strong
Technologies Used
Python
Streamlit
Random & String modules
Installation
Clone the repository:
git clone https://github.com/Syeda-Rubab/Password-Strength-checking.git
cd password-tool
Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies:
pip install -r requirements.txt
Usage
Run the Streamlit application:
streamlit run app.py
Open your browser and go to http://localhost:8501/
File Structure
password-tool/
│── app.py               # Main application script
│── requirements.txt     # Dependencies
│── README.md            # Project Documentation
Dependencies
Make sure you have the following installed:

Python 3.x
Streamlit
To install dependencies, run:

pip install -r requirements.txt
Author
Developed by Syeda Rubab. Feel free to contribute or report issues!
