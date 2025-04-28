1. line 12 will log "3"
2. line 13 will log "150"
3. line 14 will log "150"
4. it will return [50, 100, 150]. The for loop goes through all the prices and gets the discounted price using the discount. These are pushed into an array which is returned. 
5. there will be an error since we are trying to access i when it has not been declared in that scope. it only exists inside the for loop.
6. this will run into the same error as earlier. discountedPrice is declared inside the for loop scope so it cannot be accessed from outside it.
7. this will log "150". finalPrice was declared in the same scope as line 14 so it can be called. its last value from inside the for loop was 150.
8. this will return [50, 100, 150]. The for loop goes through all the prices and gets the discounted price, pushing it into the array which gets returned. 
9. this will run into an error since i was declared inside the for loop scope and not the function scope.
10. it will return "3". the length was calculated in line 4 and that is being returned. no const variables are getting their valeus rewritten so no errors.
11. it will return [50, 100, 150]. we never reassigned discounted so it isn't violating const properties. the for loop calculates and adds these discounted prices into that array which gets returned.
12. The notations are below
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting()
    4.  student["Favorite Teacher"].name
    5.  student.courseload[0]
13. Arithmetic
    1.  The output is 32 since the integer gets converted into a exact string of its current value
    2.  The output is 1 since the string gets converted into an integer (cant really 'subtract' strings).
    3.  The output is 3 since null gets changed to 0. 
    4.  The output is 3null since null gets converted into an exact string
    5.  The output is 4 since true is a boolean value and gets converted to 1
    6.  The output is 0 since both false and null get converted to 0 
    7.  The output is 3undefined since undefined gets converted into an exact string 
    8.  The output is NaN since we are trying to do integer operations and undefined is NaN
14. Comparison
    1.  The output is true since '2' gets converted into an integer for comparison
    2.  The output is false since we are comparing strings, character by character and 2 comes after 1 looking at hex characters
    3.  The output is true since we are just checking values and the string 2 gets converted into a value
    4.  The output is false since we are also looking at the type and they have different types
    5.  The output is false since true is 1, not 2. Therefore even after type conversion they arent the same
    6.  The output is true since the boolean of any number greater than 0 is true and they are both the same type as well.
15. == only checks values and converts the types to match and === also checks the type and does no type conversions.
17. The function would return [1, 4, 6]. The array [1, 2, 3] gets passed into the modifyArray method as array and the doSomething function gets passed in as callback. Now, the for loop goes through each element of array and passes it to doSomething, which returns the number times 2. This gets added into the newArr which is returned.
19. The output would be "1 4 3 2" going to a new line each time. 