# Project_Emo_Cal
Code for a basic calculator to perform arithmetic operations where operators are in disguise of emoticons.

Approach of the logic:
1. In CalculatorController.php file 
  1.1: Public function dataCalculate() retrived the data value and the operation; it then called the function to perform artihmatic operations based on the retrived input data value.
  1.2: Public function calculate() takes three argument; type of operation, two input values. This function contains the logic of addition, subtraction, multiplication and division by calling the respective functions to perform the operations defined later called add(), subtract(), multiply(),divide().
2. In welcome.blade.php file 
  2.1: The file contains HTML code to generate the interface. For turning the artihmatic operations into emoticons, respective ASCII codes is used.  

Approach to run the code:
1. Latest version of laravel has to be installed using composer. Composer contains all the libraries to run laravel project.
2. Latest version of PHP has to be installed and set as an environment variable.
3. Any IDE that can run laravel projects has to be installed.
4. In the terminal of the IDE "php artisan serve" command has to be run to the application on the PHP development server.
5. After getting the Laravel development server addresss, it has to be opened. The project will be functional on the web address. 
