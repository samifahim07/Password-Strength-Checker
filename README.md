# Password-Strength-Checker


This is a simple Python project that checks whether a password is Strong or Weak based on some basic security rules.

📌 Project Description

The program takes a password input from the user and checks if it meets the following conditions:

Password must be at least 8 characters long

Must contain at least one uppercase letter

Must contain at least one lowercase letter

Must contain at least one digit (0–9)

Must contain at least one special character (like !@#$%^&*)


🛠️ How It Works

The program uses:

len() to check password length

any() function with:

.isupper() → checks uppercase letters

.islower() → checks lowercase letters

.isdigit() → checks digits

.isalnum() → detects special characters

All conditions are combined using an if statement to determine the password strength.



Output: 




<img width="450" height="46" alt="1" src="https://github.com/user-attachments/assets/7ec570ed-a689-4ca8-b293-3dbb06686989" />

<img width="450" height="48" alt="2" src="https://github.com/user-attachments/assets/cd895086-bc67-4ce2-8b6d-7f0637b4b197" />




