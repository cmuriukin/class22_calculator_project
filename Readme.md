1. Overview and Introduction: This Bash script performs basic arithmetic operations (addition, subtraction, multiplication, and division) between two numbers entered by the user. It provides a simple command-line interface for mathematical calculations.
2. Input: The script prompts the user to input two numbers and then select an arithmetic operation from the displayed menu. The menu options are addition (+), subtraction (-), multiplication (*), and division (/).
3. Operations: Based on the user’s choice, the script computes the result of the selected operation using the bc utility for accurate mathematical calculations.
4. Division Handling: Special error handling is included for division operations to prevent division by zero, displaying an appropriate error message if the second number is zero.
5. Expected Output: After performing the selected operation, the script displays the result in a clear format, indicating the operation performed and the computed value.
6. Changes: The script can be easily extended by adding more operations or enhancing error handling for invalid inputs, making it a versatile tool for basic command-line calculations.


echo "END================END"
 
 Save the file and exit the text editor. 
 Make the script executable by running the command below: 
 $ chmod +x calculator.sh
 
 Run the script by executing the command below: 
 $ ./calculator.sh
 
 You will be prompted to enter two numbers and select an arithmetic operation. 
 Conclusion 
 You have successfully created a simple calculator script using the bash shell. You can now perform basic arithmetic operations using the script. 
 You can also add more arithmetic operations or improve the script to handle more complex calculations. 
 If you have any questions or feedback, feel free to leave a comment. 
 Happy coding!

