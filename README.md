# Cal GUI

A simple calculator application with a graphical user interface built using Python's Tkinter library.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, division
- Graphical interface with buttons for digits and operations
- Backspace and clear functionality
- Uses custom images for operation buttons

## Requirements

- Python 3.x
- Tkinter (included with standard Python)
- PNG icon files for the operation buttons (place them in the specified path or update the code)

## How to Run

1. Make sure you have Python 3 installed.
2. Place the required icon PNG files in `C:/Users/HP/Downloads/` or update the file paths in the code.
3. Run the script:
   ```
   python Main_code.ipynb
   ```
   Or open the notebook in Jupyter and run the cell.

## Usage

- Click the number and operation buttons to enter your calculation.
- Press `=` to evaluate.
- Use the backspace (delete icon) to remove the last character.
- Use the `Clear` button to reset the input.

## Notes

- The calculator uses Python’s `eval()` for expression evaluation. Only use trusted input.
- You can resize the button images using the `subsample()` method in Tkinter.

---