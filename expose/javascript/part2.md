## Part 2 Answers

1. It will print 3 because var i is function scoped so after the for loop, i is still accessible
2. It will print 150 since discounted price is also function scoped and it holds the value of the last iteration (300 * 0.5)
3. 150 because same reason as above and it holds the last value that was computed
4. [50,100,150] because the array is properly discounted and returns properly
5. Throws an error because i is defined within the for loop, so it doesn't exist outside of it
6. Throws an error because discountedPrice is defined in the for loop, so it doesn't exist outside of it
7. 150 because finalPrice is defined outside of the for loop, so it's accessible within the for loop and also outside of it, so it will hold the value of the last iteration
8. [50,100,150] since discounted is defined outside of the for loop, it's accessible within the for loop and also outsied of it, so it will hold the correct values
9. Throws an error since is is defined in the for loop and it is scoped to the loop
10. 3 since length is defined outside of the for loop and is accessible
11. It should return [50,100,150] since const prevents reassignment, not mutation. So it should hold the correct values
12. 
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. 
    a. '32' since + with a string makes the 2 become a '2' and concatenation occurs
    b. 1 since - makes it a math equation and the '3' becomes a 3
    c. 3 since the null will become 0 (due to the +)
    d. '3null' because the null converts to the string 'null'
    e. 4 since the true will become a 1
    f. 0 because both will become 0 due to the arithmetic operation
    g. '3undefined' because undefined will convert to its string version
    h. NaN because the 3 will get converted into a number and so will undefined. undefined number is NaN and any artihmetic operation involving that will be NaN
14. 
    a. true because '2' becomes 2 and 2 is greater than 1
    b. false because it compares it string by string and the character '2' is less than '1'
    c. true because '2' becomes 2 and they are both equal
    d. false since they are not both of the same types
    e. false since true becomes a 1 and 1 isn't equal to 2
    f. true since boolean(2) is true and both are true booleans
15. == is loose equality so different types can be equal and it does type coercion before comparing. However, === is more srict in the sense that it doesn't do that coercion so both the value and type must match. 
17. It will return [2,4,6] because each element in the array, doSomething is called as a callback, which multiplies it by 2. So [1,2,3] becomes [2,4,6]
19. 1, 4, 3, 2 because first it will immediately print 1 and 4, and then it will print out 3 as it waits after the current call stack clears. Then it will print 2 after 1000ms.