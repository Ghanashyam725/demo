🔐 Password Strength Checker

This project is a powerful and intuitive Password Strength Checker and Generator built with Python and Tkinter. It evaluates the security of a password in real-time using entropy calculation, pattern analysis, and modern password evaluation techniques. The tool also includes a strong password generator that ensures high randomness and complexity.
<br>
🚀 Features
<br>
Real-time Password Strength Evaluation
<br>
Analyzes character types, length, repetition patterns, and more
<br>
Uses Shannon entropy to measure password unpredictability
<br>
Provides estimated time to crack using brute-force attacks (assuming 1 billion guesses/sec)
<br>
Visual Strength Meter
<br>
Color-coded strength label (Weak, Medium, Strong, Very Strong)
<br>
Progress bar to visually represent strength
<br>
Detailed suggestions for improving password quality
<br>
Secure Password Generator
<br>
Generates strong 24-character passwords
<br>
Ensures use of lowercase, uppercase, digits, and special characters
<br>
High entropy (>120 bits) for enhanced security
<br>
User-Friendly GUI
<br>
Built with Tkinter
<br>
Smooth and responsive interface with modern button styles
<br>
Toggle to show/hide password
<br>
Copy password to clipboard with a single click
<br>
🔍 How Password Strength is Measured
<br>
Entropy Calculation:
<br>
Entropy = password length × log₂(character set size)
<br>
Higher entropy implies more possible combinations and greater resistance to attacks
<br>
Time to Crack Estimation:
<br>
Based on the entropy, calculates how long it would take a brute-force attacker (guessing 1 billion passwords per second) to crack it
<br>
Pattern Analysis:
<br>
Checks for continuous character repetition (e.g., aaa, 111)
<br>
Flags passwords with over 50% of the same character
<br>
Length and Complexity Scoring:
<br>
Rewards passwords that include diverse character types
Penalizes short or overly repetitive inputs
<br>
🛠 Tech Stack
<br>
Python 3
<br>
Tkinter for GUI development
<br>
secrets and string for secure password generation
<br>
math and re for entropy and pattern calculations
<br>
📦 Setup Instructions
<br>
Clone this repository:
<br>
git clone https://github.com/your-username/password-strength-checker.git
cd password-strength-checker
<br>
Run the script:
<br>
python password_checker.py
<br>
💡 Make sure Python 3 is installed on your system.
<br>
📄 License
<br>
This project is licensed under the MIT License.
