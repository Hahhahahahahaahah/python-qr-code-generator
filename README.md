# **QR Code Generator with GUI: The Ultimate Shortcut**

Ever seen those intriguing black-and-white squares on various items and wondered how they're made? Welcome to the world of QR Codes! In this guide, we take a leap into creating a QR Code Generator with a graphical user interface (GUI) using Python. By the end, you'll be able to generate QR codes with a simple click, all from your own GUI application. 🚀

## **Journey into QR Codes**

QR Codes, originating in Japan in 1994, are a type of 2D barcode that can store a wide range of information, from URLs to text. They are digital shortcuts, making it easier to access websites or information without typing long addresses. These versatile codes are used in marketing, ticketing, and even menus!

Ready to build your own QR Code generator with a GUI? Let's get started!

## **Preparation Phase**

1. **Code Editor**: Choose your favorite code editor or an online IDE like Replit.
2. **File Setup**: Create a Python file for your QR Code Generator program.
3. **Library Installation**: Two main libraries are needed: `qrcode` for generating QR codes and `tkinter` for the GUI. You can install them using pip:
   ```bash
   pip install qrcode
   pip install tk
   ```
## Instructions
1. Import the necessary libraries, in this case `qrcode`, `tkinter` and `messagebox` from the `tkinter` library
1. Design your GUI! It can be as simple as the following:<br><img width="250" alt="image" src="https://github.com/theyoungmaker/python-qr-code-generator/assets/130747987/84a67df9-b7a9-4d9d-8659-97444be6f11a">
1. Capture the user input for both website as well as the file name for your QR code! You will need 2 widgets from the `tkinter` library to do this! (Recall how you can do this; what widget would you need?)
1. Create a function called `generate_qr()` that gets the user input from the 2 widgets you created!
1. Now read up on how you can create the qr code using the [`qrcode` library](https://pypi.org/project/qrcode/)
1. Your `generate_qr()` should have some data validation (using if-else block) to check if the user has indeed input a url and a file name before you create the qr code, else you should display a message to the user to let them know they need to input both the url and file name
1. If you did it correctly, the QR Code png file should be saved in the same directory as your code!


## Running the GUI Application

- Execute your script to launch the GUI. Enter a URL in the entry field and click the "Generate QR Code" button.
- The QR Code will be generated and displayed in a new window.

## QR Code Created!

- Congratulations! You've just built a QR Code Generator with its own GUI. This tool can generate a QR Code from any URL input and display it instantly.

This project not only teaches you about QR Code generation but also gives you hands-on experience with building a GUI application in Python using Tkinter. It's a perfect blend of functionality and user interaction. Enjoy generating QR codes effortlessly! 🌟
