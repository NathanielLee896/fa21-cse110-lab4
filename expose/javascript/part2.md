# Expose Part 2 Lab 4

1. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^
  1. At line 12, the console logs and displays the value of "i" which is the iterating variable. Since at line 19, prices is an array of size 3, the loop iterates three times hence having "i" = 3 thus returning 3. Since the index variable "i" is declared by var, it is function scoped hence able to be accessed by line 12.
2. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^
  2. At line 13, the console logs and displays the value of the last discountedPrice variable on line 7 which is "150". Since the discountedPrice variable is declared using a "var" keyword, it is function scoped hence declarable by line 13.
3. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^
  3. At line 14, the console logs and returns the value of the varaible finalPrice on line 8 after the for loop, which is then is the value "150". Since the variable "finalPrice" was declared using the "var" keyword on line 4, it is accessible by line 14 since it is function scoped.
4. ^^^ What will this function return? Give a brief explanation why. If the code causes an error, explain why. ^^^
  4.  This function will return the array discounted and the values after running it through the for loop on line 6. So in the end it returns "[50, 100, 150]". Since the "var" keyword was used to create the discounted variable, it is able to stay declared until the end when it returned. 
5.  ^^^ What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
  5.  At line 12, there is an error because the variable "i" is not declared outside that for loop making it undeclared when it hits line 122 causing an error. This is due to the fact that the variable "i" is being declared by the "let" keyword making it block scoped, more spcefically only accessible in that for loop.
6.  ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^
  6.  At line 13, there is since the variable discountedPrices is declared using a "let" keyword on line 7, the variable is then block scoped meaning on within that for loop is it accessible. Hence on line 13, there is an error saying that the variable discountedPrice is undefined. 
7.  ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^
  7. On line 14, the console logs and displays the value of finalPrice which is "150". Although the finalPrice variable was declared using "let" since it is not within any other blocks, it is still accessible by line 14 hence, no errors. 
8.  ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^
  8.  

