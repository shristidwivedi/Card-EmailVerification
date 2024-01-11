# Card-EmailVerification
The provided HTML document represents a simple web page with JavaScript functionality for verifying credit card numbers and Gmail accounts.
JavaScript Functions:
Two JavaScript functions, VerifyCard and VerifyEmail, are defined in the <script> section.
VerifyCard Function:

The VerifyCard function is triggered on the keyup event of an input element with the ID txtCard.
It retrieves the value entered in the input field.
If the input value starts with "4444," it sets the source of an image (pic) to "visa.jpg."
If the input value starts with "5555," it sets the source of the image to "master.png."
If the input value doesn't match either pattern, it clears the image source, sets an alternate text ("Invalid"), and removes any previous styling.
VerifyEmail Function:

The VerifyEmail function is triggered on the blur event of an input element with the ID txtEmail.
It retrieves the value entered in the email input field.
If the email address ends with "gmail.com," it clears any previous error message.
If the email address doesn't end with "gmail.com," it displays an error message below the input field, indicating that a valid Gmail account should be entered.
HTML Body:

The <body> section contains two sections for card and email verification.
For card verification, there's an input field (txtCard) that triggers the VerifyCard function on keyup. The result is displayed using an image (pic).
For email verification, there's an input field (txtEmail) that triggers the VerifyEmail function on blur. Any error message is displayed in a <div> with the ID error.
Overall, the code creates a simple web page with interactive features to verify credit card numbers and Gmail accounts using JavaScript. The design is enhanced with Bootstrap styles.
