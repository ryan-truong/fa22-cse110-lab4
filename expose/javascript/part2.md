1. It will print 3 because that is the length of the array inputted. Since the variable `i` has function scope, it will not cause an error, but the for loop will run and finish before the `console.log` is executed thus its value was updated last to be 3.
2. It will print 150 because that is the last value in the array multiplied by its discount. Since the variable `discountedPrice` has function scope, it will not cause an error, but the for loop will run and finish before the `console.log` is executed thus it will print the last value it was updated to be which was `300 * 1 - 0.5` which is 150.
3. It will print 150 because that is the last discountedPrice that is inputted into `finalPrice`. Since `finalPrice` has function scope, it will not cause an error, but the for loop will run and finish before the `console.log` is executed thus it will print the last value it was updated to which will be `Math.round(150 * 100)/100`
4. The function will return an array of elements where each element in the *ith* position represents the value in the *ith* position of the original array with the discount being applied.
5. The code will cause an error because `i` is declared with let, meaning it is contained within the scope of the block, or the `for` loop. Since we are trying to access `i` outside the block, it is not defined.
6. The code will cause an error because `discountedPrice` is declared with let, meaning it is contained within the scope of the block, or the `if` statement. Since we are trying to access `discountedPrice` outside the block, it is not defined.
7. It will print 150 because that is the last value in the array that is calculated. No error occurs because `finalPrice` was declared in the same block we are trying to access it from and the `for` loop updates the value of `finalPrice`.
8. The function will return an array of elements where each element in the *ith* position represents the value in the *ith* position of the original array with the discount being applied.
9. The code will cause an error because `i` is declared with let, meaning it is contained within the scope of the block, or the `for` loop. Since we are trying to access `i` outside the block, it is not defined.
10. It will print 3 because that is the length of the array inputted. Since `length` is declared with `const` it can not be reassigned, but since it is only being printed no error occurs.
11. The function will return an array of elements where each element in the *ith* position represents the value in the *ith* position of the original array with the discount being applied. No error occurs because the variable `discounted` is not being reassigned and stays referenced to an array.

12a. `student.name`

12b. `student['Grad Year']`

12c. `student.greeting()`

12d. `student['Favorite Teacher'].name`

12e. `student.courseLoad[0]`

13a. `'32'` - this output was given because the integer 2 is converted to its string literal so 2 is concatenated to 3.

13b. `1` - this output was given because the string 3 is converted to its integer so it becomes 3 - 2.

13c. `3` - this output was given because a numeric conversion causes null to become 0 so it is 3 + 0.

13d. `'3null'` - this output was given because null was converted to its string literal 'null' so 'null' is concatenated to 3

13e. `4` - this output was given because a numeric conversion causes true to become 1 so it is 1 + 3.

13f. `0` - this output was given because a numeric conversion causes false to become 0 and null to become 0 so it's 0 + 0.

13g. `'3undefined'` - this output was given because undefined is converted into its string literal and concatenated to 3.

13h. `NaN` - this output was given because 3 and undefined were converted to a numeric so 3 - NaN is NaN.

14a. `True` - 2 is converted into a number so 2 > 1.

14b. `False` - the letters of '2' (two) and '12' (twelve) are compared and since 12 comes before 1 it is smaller.

14c. `True` - the string '2' becomes a number and since they are both the same number it is true.

14d. `False` - because this is a strict comparison 2 and '2' are not of the same type so it is false.

14e. `False` - true becomes 1 so 1 == 2 is false.

14f. `True` - when casted to a Boolean, values that are not intuitively meant to be "empty" become true so true === true.

15. The difference between == and === is how strict the comparison is. For == a conversion can happen so 2 == '2' would be true, but === is strict and checks for the types as well. Thus, if two values being compared are of different types it would return false.

17. The result will be an array where every value in the *ith* position of the array is the *ith* element of the original array that was given as an argument multiplied by 2. To arrive at this result, I noticed that every value of the original array was being passed as an argument into the `doSomething` function which multiplies the input by 2 and the result was pushed into a new array which was being returned.

19. ```
    1
    4
    3
    2
    ```

