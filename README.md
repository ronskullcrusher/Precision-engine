Precision Engine Calculator
Welcome to the Precision Engine Calculator project! This simple, yet elegant calculator is built using HTML, CSS, and JavaScript. It features a clean and intuitive user interface, making it easy for users to perform basic arithmetic operations. This README will guide you through the setup, structure, and functionalities of the project.

Table of Contents
Project Overview
Technologies Used
Installation & Setup
File Structure
Functionalities
Customization
Contributing
License
Contact
Project Overview
The Precision Engine Calculator is a web-based application designed to handle basic mathematical calculations. The calculator includes features like addition, subtraction, multiplication, division, percentage calculation, and more. It also includes buttons for clearing the input, backspacing, and appending double zeroes.

The calculator's interface is designed with simplicity in mind, offering a smooth user experience with its rounded buttons, vibrant colors, and a custom font.

Technologies Used
HTML5: Structuring the web content.
CSS3: Styling the interface and layout, including grid display for buttons.
JavaScript (ES6): Adding interactivity and functionality.
Installation & Setup
Prerequisites
To run this project locally, you will need:

A web browser (Google Chrome, Firefox, etc.)
A code editor (VSCode, Sublime Text, etc.)
Steps to Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/precision-engine-calculator.git
Navigate to the project directory:

bash
Copy code
cd precision-engine-calculator
Open index.html in your web browser:
You can do this by simply double-clicking the file or by running a local server if you prefer.

Optional: Running a Local Server
If you prefer to use a local server, you can utilize Python's built-in HTTP server. Run the following command in your terminal:

bash
Copy code
python3 -m http.server
Then, navigate to http://localhost:8000 in your web browser.

File Structure
The project is organized into the following files:

graphql
Copy code
precision-engine-calculator/
│
├── index.html        # The main HTML file that structures the calculator.
├── styles.css        # The CSS file that styles the calculator.
└── script.js         # The JavaScript file that powers the calculator's functionality.
index.html
This file contains the structure of the calculator, including the display area and the buttons. It also links the CSS and JavaScript files and includes the custom font from Google Fonts.

styles.css
This file defines the layout and appearance of the calculator. The calculator is centered on the page, and buttons are arranged using CSS Grid. The CSS also includes hover effects, custom fonts, and responsive design considerations.

script.js
This file contains the JavaScript functions that control the calculator’s functionality. It handles button clicks, calculations, error handling, and updating the display.

Functionalities
Display Input: Users can input numbers and operators using the on-screen buttons, which are displayed in the input field.
Basic Operations: Perform basic arithmetic operations such as addition, subtraction, multiplication, and division.
Percentage Calculation: Calculate the percentage of a number using the % button.
Clear Display: Clear the entire input field using the AC button.
Backspace: Remove the last character entered using the C button.
Decimal Point: Add a decimal point to your calculations using the . button.
Equal: Compute the entered expression and display the result using the = button.
Customization
Changing Colors
To customize the colors of the calculator, modify the background-color properties in the styles.css file. For example:

css
Copy code
.btn {
    background-color: #e0e0e0; /* Change this color to your preference */
}
Changing Fonts
You can change the font by modifying the font-family properties in the styles.css file or by linking a different font in the index.html:

css
Copy code
font-family: 'Sankofa Display', sans-serif;
Adding New Buttons
To add more functionality, such as advanced mathematical functions, simply add new buttons in the index.html file and define corresponding functions in the script.js file.

Contributing
We welcome contributions to improve the Precision Engine Calculator. To contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License. You are free to use, modify, and distribute this software as long as you include the original license.

Contact
If you have any questions or feedback, feel free to reach out:

GitHub: ronskullcrusher
Email: ronskullcrusher27@gmail.com
