# Expose Part 2 Lab 4

1. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^ <br>
At line 12, the console logs and displays the value of "i" which is the iterating variable. Since at line 19, prices is an array of size 3, the loop iterates three times hence having "i" = 3 thus returning 3. Since the index variable "i" is declared by var, it is function scoped hence able to be accessed by line 12.
2. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^ <br>
  At line 13, the console logs and displays the value of the last discountedPrice variable on line 7 which is "150". Since the discountedPrice variable is declared using a "var" keyword, it is function scoped hence declarable by line 13.
3. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^ <br>
  At line 14, the console logs and returns the value of the varaible finalPrice on line 8 after the for loop, which is then is the value "150". Since the variable "finalPrice" was declared using the "var" keyword on line 4, it is accessible by line 14 since it is function scoped.
4. ^^^ What will this function return? Give a brief explanation why. If the code causes an error, explain why. ^^^ <br>
  This function will return the array discounted and the values after running it through the for loop on line 6. So in the end it returns "[50, 100, 150]". Since the "var" keyword was used to create the discounted variable, it is able to stay declared until the end when it returned. 
5.  ^^^ What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)). <br>
  At line 12, there is an error because the variable "i" is not declared outside that for loop making it undeclared when it hits line 122 causing an error. This is due to the fact that the variable "i" is being declared by the "let" keyword making it block scoped, more spcefically only accessible in that for loop.
6.  ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^ <br>
  At line 13, there is since the variable discountedPrices is declared using a "let" keyword on line 7, the variable is then block scoped meaning on within that for loop is it accessible. Hence on line 13, there is an error saying that the variable discountedPrice is undefined. 
7.  ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^ <br>
  On line 14, the console logs and displays the value of finalPrice which is "150". Although the finalPrice variable was declared using "let" since it is not within any other blocks, it is still accessible by line 14 hence, no errors. 
8.  ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^ <br>
  This function will return the values of the discounted array which are "[50, 100, 150]" since the discounted array was declared using "let" but is still accessible throughout the function where it is called since all operations on it is within its block scope.
9.  ^^^ What will happen at line 11 and why? If the code causes an error, explain why. ^^^ <br>
  At line 11, the function returns an error since "i" is still within a for loop when declared and was declared using "let" making it accessible only in the for loop and not in the rest of the function as "let" is block scoped. 
10. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^ <br>
  At line 12, the console logs and displays the value of "length" on line 4 which is declared using the "const" keyword making it accessible to line 12. And since length is the length of the prices array which is size 3, it returns "3".
11. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^ <br>
  This function returns the value of the discounted prices which is "[50, 100, 150]". Since the variable discounted was declared using const, it is block scoped and it is not defined in an inner block thus does not return an error. 
12.  Given the above Object, write the notation for:  (These should be in your part2.md) <br>
  1.  Accessing the value of the name property in the student object <br>
    student.name
  2.  Accessing the value of the Grad Year property in the student object <br>
    student['Grad Year']
  3. Calling the function for the greeting property in the student object <br>
    student.greeting()
  4.  Accessing the name property of the object in the Favorite Teacher property in student <br>
    student['Favorite Teacher'].name
  5.  Access the first index in the array of the courseLoad property of the student object <br>
    student.courseLoad[0]
13.  Arithmetic <br>
  1.  ‘3’ + 2 <br>
    32
  2.  ‘3’ - 2 <br>
    1
  3.  3 + null <br>
    3
  4.  ‘3’ + null <br>
    3null
  5.  true + 3 <br>
    4
  6.  false + null <br>
    0
  7.  '3' + undefined <br>
    3undefined
  8.  '3' - undefined  <br>
    NaN
14. Comparison <br>
  1.   ‘2’ > 1 <br>
    true
  2.   ‘2’ < ‘12’ <br>
    false
  3.   2 == ‘2’ <br>
    true
  4.   2 === ‘2’ <br>
    false
  5.   true == 2 <br>
    false
  6.   true === Boolean(2) <br>
    true
15. Explain difference between the == and === operators. <br>
  The difference between the == and === operators is that for the == operator, it converts the types of the variable values to the same type before comparing the two values. On the other hand for the === operator, it does not change the types of the variable values and only returns true if not only the values are the same but also the type.





