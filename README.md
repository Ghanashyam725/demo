<h1>🔐 Password Strength Checker</h1>
    <p>
      This project is a powerful and intuitive Password Strength Checker and Generator built with Python and Tkinter.
      It evaluates the security of a password in real-time using entropy calculation, pattern analysis, and modern evaluation techniques.
      It also includes a strong password generator that ensures high randomness and complexity.
    </p>
  </div>

  <div class="section">
    <h2>🚀 Features</h2>
    <ul>
      <li><strong>Real-time Password Strength Evaluation</strong></li>
      <li>Analyzes character types, length, repetition patterns, and more</li>
      <li>Uses Shannon entropy to measure password unpredictability</li>
      <li>Estimates time to crack using brute-force attacks (1 billion guesses/sec)</li>
    </ul>
    <ul>
      <li><strong>Visual Strength Meter</strong></li>
      <li>Color-coded label (Weak, Medium, Strong, Very Strong)</li>
      <li>Progress bar to show strength visually</li>
      <li>Suggestions to improve password strength</li>
    </ul>
    <ul>
      <li><strong>Secure Password Generator</strong></li>
      <li>Generates 24-character strong passwords</li>
      <li>Includes lowercase, uppercase, digits, and symbols</li>
      <li>High entropy (>120 bits) for robust security</li>
    </ul>
    <ul>
      <li><strong>User-Friendly GUI</strong></li>
      <li>Built using Tkinter</li>
      <li>Modern, responsive UI</li>
      <li>Toggle password visibility</li>
      <li>Copy password with one click</li>
    </ul>
  </div>

  <div class="section">
    <h2>🔍 How Password Strength is Measured</h2>
    <ul>
      <li><strong>Entropy Calculation:</strong> <br>
        Entropy = password length × log₂(character set size)<br>
        Higher entropy = more combinations = more secure
      </li>
      <li><strong>Time to Crack:</strong><br>
        Calculates time required for brute-force attacker to crack it (1B guesses/sec)
      </li>
      <li><strong>Pattern Analysis:</strong><br>
        Detects repeating characters (e.g., aaa, 111)<br>
        Flags passwords with over 50% of identical characters
      </li>
      <li><strong>Length and Complexity Scoring:</strong><br>
        Rewards variety in characters<br>
        Penalizes short or repetitive inputs
      </li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠 Tech Stack</h2>
    <ul>
      <li>Python 3</li>
      <li>Tkinter for GUI</li>
      <li>secrets and string for secure generation</li>
      <li>math and re for entropy and patterns</li>
    </ul>
  </div>

  <div class="section">
    <h2>📦 Setup Instructions</h2>
    <p>Clone this repository and run the script:</p>
    <pre><code>
git clone https://github.com/your-username/password-strength-checker.git
cd password-strength-checker
python password_checker.py
    </code></pre>
    <p>💡 Make sure <strong>Python 3</strong> is installed on your system.</p>
  </div>

  <div class="section">
    <h2>📄 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong>.</p>
  </div>
