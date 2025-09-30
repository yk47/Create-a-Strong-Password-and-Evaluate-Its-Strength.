# 🔐 Password Strength Evaluation Report
Understand what makes a password strong and test it against password strength tools.

## 🎯 Objective

The objective of this task is to understand what makes a password strong by creating different passwords, testing them with an online password strength checker (e.g., passwordmeter.com
), and learning best practices for secure password creation.

## 🛠 Tools Used
- Password Strength Checker: passwordmeter.com
- Tested Passwords: Created with varying complexity

## 🔑 Password Testing
### 1. Weak Password Example
- Password: yash123
- Result:
    - Score: 37%
    - Feedback: Too short, dictionary-based, predictable, no symbols/uppercase
- Analysis: Easy to guess using brute force or dictionary attack
  
  📸 Weak Password Testing Screenshots
  
<img width="611" height="880" alt="week_password" src="https://github.com/user-attachments/assets/e89728b4-77d4-415c-b188-bf0bbc7940fb" />

  

### 2. Medium Password Example
- Password: yash@123
- Result:
    - Score: 59%
    - Feedback: Improved strength with uppercase, number, and symbol. Still short (8 chars).
- Analysis: Better than first one, but can still be cracked in hours/days with brute force
  
   📸 Medium Password Testing Screenshots
  
  <img width="609" height="881" alt="medium_password" src="https://github.com/user-attachments/assets/708ea23c-3fca-4229-af5e-9cb16b2f9c36" />


### 3. Strong Password Example
- Password: S!lvrHdow2
- Result:
    - Score: 78%
    - Feedback: Strong mix of uppercase, lowercase, numbers, and special characters. Length improves resilience.
- Analysis: Resistant to brute force, dictionary, and common password guessing attacks

   📸 Strong Password Testing Screenshots
  
  <img width="607" height="880" alt="strong_password" src="https://github.com/user-attachments/assets/56e1a5fb-9680-4478-9c9a-50cbbb3f746e" />


### 4. Very Strong Password Example
- Password: M^9!tR@pL3x#7&fQ8Z
- Result:
    - Score: 100%
    - Feedback: Excellent password — long (18 chars), random, uses all character classes
- Analysis: Nearly impossible to brute force in reasonable time, highly secure
  
  📸 Very Strong Password Testing Screenshots
  
  <img width="608" height="880" alt="very_strong_password" src="https://github.com/user-attachments/assets/1891f686-a562-4aad-a3da-3bfb52f5666c" />


## 📚 Best Practices Learned
1.**Length matters** – Aim for at least 12–16 characters. Longer passwords take exponentially longer to crack.

2.**Mix character types** – Use uppercase, lowercase, numbers, and symbols.

3.**Avoid dictionary words** – Don’t use names, birthdays, or common words.

4.**Randomness is key** – Use passphrases or password managers to generate secure random strings.

5.**Unique per account** – Don’t reuse the same password across different services.

6.**Use passphrases** – Example: G0@t$Run#F@st2025! (easy to remember, hard to crack).


## ⚔️ Common Password Attacks & Impact of Complexity
- Brute Force Attack: Tries all combinations; longer + complex passwords exponentially increase cracking time.
- Dictionary Attack: Uses common words/passwords; easily defeated by randomness and symbols.
- Credential Stuffing: Reuses stolen passwords; mitigated by unique passwords per account.

## 📝 Conclusion
From the evaluation, it is clear that password complexity and length directly affect security. Weak passwords like ```yash123``` are cracked in seconds, while complex ones like ```M^9!tR@pL3x#7&fQ8Z``` are nearly uncrackable.
The best approach is to create long, random, unique passwords and manage them using a **password manager**.
