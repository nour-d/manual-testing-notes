# Registration Page

Imagine you are tasked with manually testing this Registration Page. Design your test cases.

![Registration Page](https://raw.githubusercontent.com/nour-d/manual-testing-practice/main/images/registration-page.png "Registration Page")

First, let's plan what we will test:

**Functional Testing**

*Unit and Integration Testing*
1. Check that all text fields accept input.
2. Check that the password field hides the values of the characters.
3. Check that the *Password confirmation* field hides the values of the characters.
4. Hover over the Sign Up button to confirm that it changes colors.
5. Click on the Sign Up button to confirm form submission.
6. Select the *Sign in* link to confirm users are redirected to the sign in page.
7. Submit the form using valid values. Check that a new user is made.
8. Submit the form using an invalid username. Confirm error message.
9. Submit the form using an invalid email address. Confirm error message.
10. Submit the form using an invalid password. Confirm error message.
11. Submit the form using a different password in the *Password confirmation* field. Confirm error message.

**Non-Functional Testing**
1. Confirm that the program is fully functional with 1000 users navigating the website at the same time (*load testing*).
2. Confirm that the program has proper error handling to withstand a large volume of traffic (*stress testing*).
3. Check that the program is fully functional across all browsers and operating systems (*compatibility testing*).
4. Check that the program is fully responsive across all screen sizes, all operating systems, and all browsers (*usability testing*).

*Security Testing*

5. Register a user. Confirm that the user password is encrypted in the database.
6. Type a string of "dangerous" characters (i.e. i.e. <, >, \, /) in all text fields. Confirm that the application sanitizes this input to prevent any attempted SQL injections and XSS attacks.

*Accessability Testing*

7. Confirm that alt tags are present across all images and videos.
8. Watch all videos on the website. Confirm that subtitles are present.
9. Navigate the website using only the keyboard (no mouse).
10. Confirm that the website does not contain small text.
11. Confirm that all elements on the website have a color contrast ratio of at least 4.5:1.

[Click here to view the Test Case Document](../registration-page/table.md)

<- [Return to Table of Contents](https://github.com/nour-d/manual-testing-practice/blob/main/notes/start-here.md)