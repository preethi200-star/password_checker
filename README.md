# Password_checker
🔐 Password Strength Checker

A simple Python script that evaluates the strength of a password based on common security criteria.
It provides real-time feedback by listing exactly which requirements your password does not meet.

Ideal for beginners learning Python, security basics, or regex usage.

**🚀 Features**

Checks password against multiple security criteria:

Minimum length (8+ characters)

At least one uppercase letter

At least one lowercase letter

At least one digit

At least one special character

No spaces allowed

Displays Strong or Weak result

Gives detailed improvement suggestions

Runs in an interactive loop (test unlimited passwords)

Simple and beginner-friendly code structure

**📂 File Structure**
password_checker.py
README.md

**🛠 Requirements**

Python 3.x
No additional libraries are needed — everything uses Python’s built-in re module.

To check your version:

python --version

**▶️ How to Run the Program (Windows)**
1. Save the script
Save password_checker.py anywhere, for example:
C:\Users\YourName\Documents\password_checker.py

2. Open Command Prompt
Press Windows Key
Type cmd
Press Enter

3. Navigate to the script’s folder
cd C:\Users\YourName\Documents

4. Run the program
python password_checker.py
If that doesn’t work, try:
py password_checker.py

5. Use the program

You will see:
Welcome to the Password Strength Checker!
Enter a password to check (or 'quit' to exit):
Type any password to get instant feedback.
Type quit to exit.

**🧠 How It Works**

The script checks your password using regular expressions (re.search) to detect:
Uppercase letters: [A-Z]
Lowercase letters: [a-z]
Digits: \d
Special characters from a predefined set
Whitespace (\s)
If all conditions pass, the password is marked Strong.
Otherwise, the script lists every missing requirement.

**💡 Possible Improvements**

You can enhance this project by adding:
Hidden password input using getpass
Password strength scoring (Weak → Medium → Strong)
More advanced validations (entropy, patterns, keyboard sequences)
A GUI version using Tkinter
A web version using Flask or FastAPI

**📜 License**

This project is free to use for learning or personal use.
