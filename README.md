Name:V Nikhilkumar

Company:CODTECH IT SOLUTIONS

Id:CT08DS6418

Domain:CYBER SECURITY AND ETHICAL HACKING

Duration:AUG to SEP 2024

Mentor:


## Project Overview: Password Strength Assessment Tool

### **Objective**
The primary goal of this project is to develop a tool that assesses the strength of passwords entered by users. The tool evaluates passwords based on length, complexity, and uniqueness to provide feedback on their strength. This helps users create more secure passwords and enhances overall cybersecurity.

### **Features**
1. **Length Evaluation**: Checks if the password meets the recommended length requirements.
2. **Complexity Check**: Evaluates the presence of:
   - Uppercase letters
   - Lowercase letters
   - Digits
   - Special characters
3. **Uniqueness Assessment**: Compares the password against a list of common passwords to avoid easily guessable passwords.
4. **Strength Feedback**: Provides feedback on the password strength with categories such as Very Strong, Strong, Moderate, Weak, and Very Weak.

### **Implementation**

#### **1. Password Strength Assessment Algorithm**
- **Length Score**: The length of the password is assessed to ensure it meets the minimum requirement (e.g., 8 characters).
- **Complexity Score**: Checks for the presence of various character types (uppercase, lowercase, digits, special characters) to determine complexity.
- **Uniqueness Check**: The password is compared against a set of common passwords to ensure it is not easily guessable.
- **Strength Categorization**: Based on length, complexity, and uniqueness, the password is categorized into one of five strength levels:
  - Very Strong
  - Strong
  - Moderate
  - Weak
  - Very Weak

#### **2. User Interaction**
- **Input**: Users are prompted to enter their password.
- **Output**: The tool provides feedback on the strength of the entered password.

### **Technical Details**

- **Programming Language**: Python
- **Dependencies**: Regular expressions (`re` module) for pattern matching
- **Script**:
  - `assess_password_strength(password)`: Function to evaluate password strength.
  - `main()`: Function to handle user input and output the strength feedback.

### **Usage**

1. **Save the Script**: Save the provided Python code into a file named `password_strength_checker.py`.
2. **Run the Script**:
   - Open a terminal or command prompt.
   - Navigate to the directory containing the script.
   - Execute the script using the command: `python password_strength_checker.py`.
   - Enter a password when prompted and receive feedback on its strength.

### **Future Enhancements**
- **Extended Common Password List**: Incorporate a more comprehensive database of common passwords.
- **Entropy Calculation**: Implement entropy measurement to quantify randomness.
- **Pattern Detection**: Add checks for common patterns and sequences.
- **User Interface**: Develop a graphical or web-based interface for better user interaction.

### **Conclusion**
This project provides a foundational tool for evaluating password strength, which is crucial for improving user security and preventing unauthorized access. By assessing passwords based on length, complexity, and uniqueness, users receive actionable feedback to enhance the strength of their passwords.

