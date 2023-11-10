# Machine Problem: Basic Login System

## Objective
Write a Python function named `login_system` that simulates a simple login mechanism using a predefined set of credentials.

## Instructions

1. The function will accept two arguments:
    - A string representing the attempted username.
    - A string representing the attempted password.
2. The credentials will be stored in a dictionary where the key is the username and the value is the password. For instance: `{"user1": "pass1", "user2": "pass2"}`.
3. Define a separate function `validate_credentials(username, password, credentials_dict)` that will check if the provided username and password match any entry in the credentials dictionary.
4. The `login_system` function should use the `validate_credentials` function to verify the login attempt.
5. Use `if` and `else` to determine the login status:
    - If the credentials are valid: "Login successful"
    - If the credentials are invalid: "Login failed"
6. The function should return the login status.

## Example Usage

```python
credentials = {"user1": "pass1", "user2": "pass2"}
username_input = "user1"
password_input = "pass1"

print(login_system(username_input, password_input))
