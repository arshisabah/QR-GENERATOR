QR Code Generator🖼️

A simple Node.js command-line tool that generates a QR code from a user-provided URL and saves it as an image file. Additionally, it stores the URL in a text file.


Features ✨

Interactive command-line prompt for URL input using Inquirer.js.
QR code generation from URLs using qr-image.
Saves the QR code as a PNG file.
Stores the input URL in a text file.
Simple and efficient error handling.


Prerequisites 🛠️

Make sure you have the following installed:
Node.js (version 14+ recommended)


Installation 📥

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/qr-code-generator.git

cd qr-code-generator
Install the dependencies:

bash
Copy code
npm install


Usage 🚀

Run the script:

bash
Copy code
node index.js
Follow the prompt to enter a URL.

The QR code will be generated and saved as:

qr_img.png (QR code image)
URL.txt (stored URL)


Example Output 🖼️
QR Image:![Screenshot 2024-11-29 161757](https://github.com/user-attachments/assets/1291abe4-9cb7-4571-8dd3-151092d504e0)

Stored URL: URL.txt(https://github.com/arshisabah)


Technologies Used 🛠️

Node.js: JavaScript runtime
Inquirer.js: Command-line prompt library
qr-image: QR code generation library
fs: Node.js file system module


Project Structure 📂

bash

Copy code

qr-code-generator/

├── index.js           # Main script file

├── package.json       # Dependencies and project info

└── README.md          # Documentation
