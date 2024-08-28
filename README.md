# Operating Systems
## C programming assignment

Write a C program that complies with the following requirements:

1. When the program is called with a number of arguments different from 2, the code will output the following text to the standard output:

    ```Incorrect usage. You provided n arguments. The correct number of arguments is 2```
    
    Instead of n, the program will output the actual number of arguments passed to the program.

2. The program will then check if all arguments passed are integers greater than 0. If this is not the case, the program will output the following text to the standard output:

    ```Incorrect usage. The parameters you provided are not positive integers```

3. The program will then create a dynamically allocated matrix of integers using the dimensions passed as parameters. For instance, if the program is called with ``assignment 5 10``, a matrix of 5 rows and 10 columns will be created. Each entry of this matrix will be initialized to a random integer between 1 and 100.

4. The program will create a file called ``matrix.txt`` that contains the previously generated matrix with one row on each line, and using a whitespace separator between each entry. No whitespace should be appended at the end of each line. The last row should end with a carriage return.

Please use the provided ``Makefile`` to build and test the executable.
Please run ``make clean`` before committing to avoid including the executable files in your submission.
