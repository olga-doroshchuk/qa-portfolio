# Login Page Checklist

## UI

- [ ] Login page opens correctly
- [ ] Email field is visible
- [ ] Password field is visible
- [ ] Login button is visible
- [ ] Forgot password link is visible
- [ ] All elements are aligned correctly

## Email Field

- [ ] Valid email is accepted
- [ ] Invalid email format is rejected
- [ ] Empty email shows validation message
- [ ] Email field accepts maximum allowed length
- [ ] Leading and trailing spaces are handled correctly

## Password Field

- [ ] Valid password is accepted
- [ ] Empty password shows validation message
- [ ] Password characters are masked
- [ ] Password field accepts maximum allowed length

## Login

- [ ] User can log in with valid credentials
- [ ] Invalid email and password show an error message
- [ ] Login button works correctly
- [ ] User cannot log in with empty fields
- [ ] Successful login redirects to the correct page

## Security

- [ ] Password is not displayed as plain text
- [ ] User session is created after successful login
- [ ] Logout ends the user session
- [ ] Protected pages cannot be accessed after logout

## Negative Testing

- [ ] Invalid email is rejected
- [ ] Invalid password is rejected
- [ ] Empty email and password are rejected
- [ ] Special characters are handled correctly
- [ ] Very long input is handled correctly
