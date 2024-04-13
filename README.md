# Email Validation Function

This Python script provides a function for validating email addresses using regular expressions.

## Explanation

The script defines a function `validate_email(email)` that takes an email address as input and returns `True` if the email address is valid according to the specified regex pattern, otherwise `False`.

The regex pattern used for email validation is as follows:

<b>pattern = r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+.[a-zA-Z]{2,}$'</b>

This pattern checks if the email address consists of:
- One or more characters that can be letters (both uppercase and lowercase), digits, dots, underscores, percentage signs, plus signs, or hyphens (`[a-zA-Z0-9._%+-]+`).
- The "@" symbol.
- One or more characters that can be letters (both uppercase and lowercase), digits, dots, or hyphens (`[a-zA-Z0-9.-]+`).
- A literal dot (".") character (escaped with a backslash `\.`).
- Two or more characters that can be letters (both uppercase and lowercase), representing the top-level domain (TLD) (`[a-zA-Z]{2,}`).

## Usage

1. Import the `validate_email` function into your Python script.
2. Call the function with an email address as input.
3. The function will return `True` if the email address is valid, otherwise `False`.


