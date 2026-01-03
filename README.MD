# ASCII Art Project: Lionel Messi 

This project is a Python-based implementation that generates an ASCII-style portrait of the legendary footballer, **Lionel Messi**. Developed as part of a Minor II project, it demonstrates the use of core Python programming concepts like loops, conditional statements, and file handling.


## Project Overview
The goal of this project was to translate a visual image into a character-based representation using symbols like `#`, `*`, and `.`. By leveraging Python's logic-building capabilities, the code processes raw ASCII data and renders it into a recognizable portrait in the terminal.

##  File Structure
* `analyze_data.py`: The main Python script that contains the logic to read, process, and print the ASCII face.
* `ascii_art.txt`: A text file containing the raw ASCII character mapping for the portrait.

## How It Works
1.  **Data Storage**: The face structure is stored in `ascii_art.txt`.
2.  **Processing**: The `analyze_data.py` script opens the file and iterates through each line using `for` loops.
3.  **Rendering**: The script uses conditional logic to ensure the spacing and characters align correctly to form Messi's features.

## Logic Implementation
To create this, I focused on:
* **Nested Loops**: Iterating through rows and columns of character data.
* **String Manipulation**: Handling special characters to ensure the image doesn't distort.
* **Efficiency**: Using a "shorter code" approach to minimize memory usage while printing the output.

## Usage
To view the ASCII art in your terminal, run:
python analyze_data.py