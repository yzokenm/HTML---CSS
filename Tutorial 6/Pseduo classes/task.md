Scenario:
You are tasked with designing a form for a website that allows users to sign up for a newsletter. The form should include fields for the user's name, email, and a submit button. You'll also apply various pseudo-classes and elements to enhance the UI and user interaction.

Steps:
HTML Structure:

Create a form with three fields:
Name (input type="text")
Email (input type="email")
Submit button
Add placeholders for both inputs.
CSS Styling:

Style the form and apply the following pseudo-classes/elements:
Pseudo-Classes:
:active:
Style the submit button when it is being clicked.
:hover:
Add hover effects for input fields and the submit button, changing their background color when the user hovers over them.
:focus:
Add a border color change and maybe a box-shadow when input fields are focused (i.e., when the user is typing in them).
:nth-child():
Apply a different background color to alternate form fields using :nth-child() (odd/even) selectors.
:valid:
Change the border color of the email input when the user has entered a valid email.
Pseudo-Elements:
::before:
Add a decorative icon or some text before the submit button or one of the inputs (e.g., add a * before required fields).
::after:
Create an effect that adds a checkmark or custom text after the submit button once it's clicked.
::first-letter:
Style the first letter of a label or any text block in the form to have a larger font size or a different color.
::selection:
Change the background and text color of selected text within the form.