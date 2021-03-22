## Python user inputs

### To create your inputs

1. Create a variable to store the data
2. Use ``` input() ```
3. Write your question inside speech marks in the input brackets to prompt user to enter their information
   ``` input("your prompt") ```
4. If you want an integer, or a float instead of the default type, string do this:
  ```
  int(input("your prompt")) # for integer
  float(input("your prompt")) # for float
  ```
### To print out the type of each data received from the user

Use the command below to print out the type of the data.
``` print(type(variable_name)) ```
type will return one of 
```
<class 'str'> # for strings
<class 'int'> # for integers
<class 'float'> # for float
```
depending on the variable entered and the format of the input.