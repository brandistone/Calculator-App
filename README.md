
# Calculator App

## Overview

The Calculator App is a simple and user-friendly application designed to perform basic arithmetic operations. This app provides a graphical user interface to perform calculations with ease. It supports operations like addition, subtraction, multiplication, and division.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Clear Function**: Clear the current input or reset the calculation.
- **User-Friendly Interface**: Easy-to-use graphical interface with buttons for each function.

## Installation

To run the Calculator App, you'll need to have Python installed on your machine along with the Kivy framework. Follow these steps to set up the app:

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/brandistone/Calculator-App/tree/main
    cd calculator-app
    ```

2. **Create a Virtual Environment** (optional but recommended):

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:

    Install tkinter using pip:

    ```sh
    pip install tkinter
    ```

4. **Run the Application**:

    Navigate to the directory containing the `main.py` file and execute:

    ```sh
    python main.py
    ```

## Usage

1. **Open the Calculator App** by running `main.py`.
2. **Use the On-Screen Buttons**:
   - Enter numbers and operations using the buttons on the screen.
   - Press `=` to get the result of the calculation.
   - Press `C` to clear the current input.

## Project Structure

- `main.py`: The main Python script containing the app logic and user interface.
- `calculator.kv`: The Kivy language file defining the user interface layout.
- `README.md`: This README file providing information about the project.

