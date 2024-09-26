# QR_CodeGenerator
This is my first project using NodeJS. The code converts a URL into a QR_Code which after scanning leads to the site of the url!
QR Code Generator

This is a simple QR Code generator built using Node.js. The user can input text, and the application will generate a QR code based on the input, which can be saved as an image file.
Features:
Accepts user input via command line.
Generates a QR code based on the user's input.
Saves the QR code as an image file.

Prerequisites: 

To run this project, you will need to have Node.js installed on your system.

Installation:
>Clone the repository or download the project files.
>Navigate to the project directory.
    
    //enter the path in which you have downloaded the repo and then cd to qr-code-generator
    
    cd qr-code-generator
    
Install the required dependencies using npm:

run-

    npm install

Dependencies

The project relies on the following npm packages:

inquirer: A collection of common interactive command-line user interfaces.
qr-image: A library for generating QR code images.

You can install these dependencies using:
    npm install inquirer qr-image

Usage
Run the project:
    node index.js

Follow the prompts to enter the text you want to convert into a QR code.
The generated QR code will be saved as an image file (qr.png) in the project directory.

Example

After running the program, you will be prompted to enter the text. Once the text is entered, a QR code will be generated and saved as qr.png.
File Structure

bash

    qr-code-generator/
    │
    ├── index.js        # Main file containing QR code generation logic
    ├── package.json    # Project configuration and dependencies
    └── README.md       # Project documentation

License

This project is licensed under the MIT License. See the LICENSE file for details.

This README gives clear instructions about your QR Code Generator project and can be customized further if needed!
