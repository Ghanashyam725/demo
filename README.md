🔐 Password Strength Checker

This project is a powerful and intuitive Password Strength Checker and Generator built with Python and Tkinter. It evaluates the security of a password in real-time using entropy calculation, pattern analysis, and modern password evaluation techniques. The tool also includes a strong password generator that ensures high randomness and complexity.
<br>
🚀 Features
Real-time Password Strength Evaluation
Analyzes character types, length, repetition patterns, and more
Uses Shannon entropy to measure password unpredictability
Provides estimated time to crack using brute-force attacks (assuming 1 billion guesses/sec)
Visual Strength Meter
Color-coded strength label (Weak, Medium, Strong, Very Strong)
Progress bar to visually represent strength
Detailed suggestions for improving password quality
Secure Password Generator
Generates strong 24-character passwords
Ensures use of lowercase, uppercase, digits, and special characters
High entropy (>120 bits) for enhanced security
User-Friendly GUI
Built with Tkinter
Smooth and responsive interface with modern button styles
Toggle to show/hide password
Copy password to clipboard with a single click
<br>
🔍 How Password Strength is Measured
Entropy Calculation:
Entropy = password length × log₂(character set size)
Higher entropy implies more possible combinations and greater resistance to attacks
Time to Crack Estimation:
Based on the entropy, calculates how long it would take a brute-force attacker (guessing 1 billion passwords per second) to crack it
Pattern Analysis:
Checks for continuous character repetition (e.g., aaa, 111)
Flags passwords with over 50% of the same character
Length and Complexity Scoring:
Rewards passwords that include diverse character types
Penalizes short or overly repetitive inputs
<br>
🛠 Tech Stack
<br>
Python 3
Tkinter for GUI development
secrets and string for secure password generation
math and re for entropy and pattern calculations

📦 Setup Instructions
Clone this repository:
git clone https://github.com/your-username/password-strength-checker.git
cd password-strength-checker
Run the script:
python password_checker.py
💡 Make sure Python 3 is installed on your system.
📄 License
This project is licensed under the MIT License.
