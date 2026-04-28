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