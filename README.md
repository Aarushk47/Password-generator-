Password Generator
A robust and customizable password generator built with JavaScript that helps users create secure, random passwords based on their specified criteria.
Features

Generate passwords with customizable length (8-128 characters)
Include or exclude character types:

Uppercase letters (A-Z)
Lowercase letters (a-z)
Numbers (0-9)
Special characters (!@#$%^&*()_+)


Copy password to clipboard with a single click
Mobile-responsive design
Input validation to ensure at least one character type is selected
Visual feedback for successful password generation and copying

Technologies Used

HTML5
CSS3
Vanilla JavaScript
Font Awesome icons (for copy button)

Installation

Clone the repository:

bashCopygit clone https://github.com/Aarushk47/password-generator.git

Open index.html in your preferred browser

How It Works
The application uses JavaScript's built-in Math.random() function combined with character arrays to generate random passwords. The password generation algorithm:

Validates user input for password length and character type selection
Creates a pool of allowed characters based on user preferences
Randomly selects characters from the pool to build the password
Ensures at least one character from each selected type is included
Shuffles the final password to maintain randomness




Project Link: https://github.com/Aarushk47/password-generator
