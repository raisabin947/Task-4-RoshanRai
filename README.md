# Deployed Validation Engine

This project was developed as part of my Frontend Development Internship. The goal of this assignment was to create a validation engine using the Input → Process → Output (IPO) model. The project focuses on collecting user input, validating it with JavaScript and Regular Expressions (Regex), and displaying meaningful feedback while following accessibility best practices.

---

## Project Objective

The main objective of this project is to understand how frontend form validation works without relying only on HTML5 validation. Instead, JavaScript is used to inspect user input, provide custom error messages, and prepare the validated data for submission.

---

## Features

- Semantic HTML5 form structure
- Custom JavaScript validation
- Email validation using Regular Expressions
- Strong password validation
- Prevents page refresh using `event.preventDefault()`
- Real-time validation feedback
- Password strength indicator
- Show/Hide password option
- JSON output after successful validation
- Accessible error messages using ARIA attributes
- Responsive design for desktop and mobile devices

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Regular Expressions (Regex)
- WAI-ARIA Accessibility

---

## Project Structure

```
Validation-Engine/
│
├── index.html
└── README.md
```

---

## How It Works

### Input

The user enters their full name, email address, and password into a semantic HTML form.

### Process

When the form is submitted:

- The default browser refresh is prevented.
- JavaScript validates each field.
- Regex checks whether the email and password follow the required format.
- If any field is invalid, an appropriate error message is displayed.

### Output

If all inputs are valid:

- The entered data is converted into a JSON object.
- A success message is displayed.
- The form is reset for the next submission.

---

## Accessibility

Accessibility was an important part of this project. The following ARIA attributes were used:

- `aria-invalid`
- `aria-describedby`
- `aria-live="polite"`

These help screen readers identify invalid fields and announce error messages without interrupting the user while typing.

---

## Password Requirements

A valid password must contain:

- At least 8 characters
- One uppercase letter
- One lowercase letter
- One number
- One special character

Example:

```
Password@123
```

---

## What I Learned

While working on this project, I learned how to:

- Build semantic HTML forms
- Handle form submission with JavaScript
- Use `event.preventDefault()` to control browser behavior
- Validate user input using Regular Expressions
- Display custom validation messages
- Improve accessibility using ARIA attributes
- Convert form data into JSON format

---

## Future Improvements

If I continue developing this project, I would like to add:

- Backend integration with a database
- User authentication
- API-based email validation
- Secure password hashing
- Login and registration system

---

## Author

**Roshan Rai**

Frontend Development Intern

---

## Note

This project was created as part of my internship assignment to demonstrate frontend form validation, JavaScript programming, and accessibility practices using the IPO (Input → Process → Output) model.
