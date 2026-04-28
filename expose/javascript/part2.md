1. 3, the var i can be used in the whole function and after the for loop, i = 3
2. 150, the var discountedPrice can be used in the whole function and after the for loop, discountedPrice is used in the last iteration of the for loop, which is 300*0.5 = 150
3. 150, the var finalPrice can be used in the whole function and after the for loop, finalPrice is calculated using the last iteration of the for loop, which is 150. 
4. [50, 100, 250]. This is what is returned after the function is run. There are no errors and each element in the prices after discounted are returned in the set discounted[]. 
5. This returns an error because let cannot be used since it is block scoped, that variable can't be used outside the for loop. 
6. This returns an error because let cannot be used since it is block scoped, that variable can't be used outside the for loop. 
7. this will print 150. since let is declared inside the function and outside any code blocks, it can be used in this instance since the print operation is in the same function as well. The value is the last iteration of the for loop in which finalPrice is declared for. 
8. this returns [50, 100, 150]. There are no errors and the function correctly evaluates the discounted prices and returns them in a discounted set. 
9. This will return an error. i can't be seen since it is block scoped and it is inside the for loop
10. This will print 3. The reason is beacuse this is a fixed length declared at the beginning of the function and can be used anytime in the function. 
11. This returns [50, 100, 150]. The const variables are used correctly and every iterations of the for loop, const discountedPrice and be declared again as it acts like another variable. 
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' When adding with a string, the 2 gets converted to a string and concatenates with the 3.
    B. 1. When subtracting with a string and an integer, the string turns into an integer and subtracts to get 1. 
    C. 3. When adding with an int with a null, the null acts as a 0 and adds 0 to 3. 
    D. '3null'. When adding with a string and a null, it acts as if null is a string and concatenates it with the stirng '3'.
    E. 4. adding with a boolean and an integer turns the boolean into a number 0/1 depending on if it is true or false and adds them. 
    F. 0. Both values turn to integers for addition, making it 0+0=0.
    G. '3undefined'. It treats undefined as a string and concatenates them together
    H. NaN. The - is for arithmetic. While '3' becomes 3, undefined cannot be converted into a meaningful number, so it becomes NaN.
14. A. true. When comparing with >, the '2' acts as integer 2. 
    B. false, when comparing two strings, JavaScript does not look at the numerical value it compares them lexicographically. Since the character '2' comes after the character '1', '2' is considered than '12'.
    C. true, it converts the string '2' into the number 2 before comparing. 
    D. False, It checks both the value and the type. Since one is a number and the other is a string, it returns false.
    E. false, it converts true to the integer 1 and compares
    F. True, boolean(2) is converted to true since it is not 0. Since they are both the same type and value, it returns true. 
15. The == will convert data types into a common type before checking if they are equal. The === is more strict in where if the types don't match, it will return false automatically. 
17. [2, 4, 6]. First modifyArray starts with newArr. Then the loop iterates with calling the function doSomething for each iteration which multiples each element by 2. After the loop ends, it returns the new array.
19. 1
    4
    3
    2