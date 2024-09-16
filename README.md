## catalog
This repository contains a Node.js script for solving a secret sharing problem using Lagrange interpolation. The code reads input from JSON files, decodes values, and calculates the constant term.

## Prerequisites
Node.js: Ensure that Node.js is installed on your system. You can download and install it from nodejs.org.

## File Structure
main_code.js: The main JavaScript file containing the code for decoding values and calculating the constant term.

testcase.json: Example JSON file with input data for testing

testcase2.json: Another JSON file with different input data for testing.

## Running the Code
   1. Save the JavaScript Code:
      Save the provided JavaScript code into a file named main_code.js using a text editor like Notepad.
   
   2. Create Test Case Files:
     Create JSON files named testcase.json and testcase2.json with the required input data. Example content for testcase.json:
  
{
    "1": {"base": "10", "value": "2"},
    "2": {"base": "10", "value": "3"},
    "3": {"base": "10", "value": "5"}
}

   3. Run the Code:
     Open the Command Prompt or Terminal, navigate to the directory containing main_code.js, and execute the script using Node.js
     node main_code.js
     
Ensure that the JSON files (testcase.json and testcase2.json) are in the same directory as main_code.js or adjust the file paths accordingly in the code
     
   4. Check the Output:

      The script will output the decoded factors and the calculated constant term c for the given test cases.

## Example Output
For the example testcase.json provided:
The constant term c is: 3



