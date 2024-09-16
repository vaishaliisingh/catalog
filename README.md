## catalog
This repository contains a Node.js script for solving a secret sharing problem using Lagrange interpolation. The code reads input from JSON files, decodes values, and calculates the constant term.

## Prerequisites
Node.js: Ensure that Node.js is installed on your system. You can download and install it from nodejs.org.

## File Structure
main_code.js: The main JavaScript file containing the code for decoding values and calculating the constant term.

testcase.json: Example JSON file with input data for testing

testcase2.json: Another JSON file with different input data for testing.

## How to Run the Code

1. **Save the JavaScript Code**:
   Save the provided JavaScript code as `main_code.js` using a text editor.

2. **Create Test Case Files**:
   Create the required JSON files (`testcase.json` and `testcase2.json`) with input data. Example content for `testcase.json`:
   ```json
   {
       "1": {"base": "10", "value": "2"},
       "2": {"base": "10", "value": "3"},
       "3": {"base": "10", "value": "5"}
   }
3. **Run the Script**:
   ```bash
   # Open terminal or command prompt and navigate to the directory containing main_code.js
   cd path/to/your/directory

   # Run the Node.js script
   node main_code.js
   
4. **View Output**:
   After running the script, the output will be displayed in the terminal/command prompt. Ensure that the `testcase.json` and other necessary files are in the same directory as `main_code.js`.
## Example Output
For the example testcase.json provided:
The constant term c is: 3



