# Threat Model (Easy Version)

## 1. What we want to protect (Assets)
- Username & Password
- Database

## 2. Where attack can happen (Entry Points)
- Login form
- User input fields

## 3. Possible Attacks (Threats)
- SQL Injection
- XSS (script attack)
- Weak password login

## 4. Risk Level

| Threat          | Risk     |
|-----------------|----------|
| SQL Injection   | High 🔴  |
| XSS             | Medium 🟠|
| Weak Password   | Low 🟡   |

## 5. Simple Conclusion
The login page is the most critical part.
We must secure user input and database queries.