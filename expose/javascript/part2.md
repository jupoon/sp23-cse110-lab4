** Lab 4 Part 2 Answers

1. Line 12 prints `3`.
2. Line 13 prints `150`
3. Line 14 prints `150`
4. Function will return the array of discounted prices, `[50, 100, 150]`
5. Code causes an error. `let` variables can only be accessed in the block it was defined in. Since the var `let i` was defined in the for loop, it cannot be accessed outside the for loop, which is what line 12 tried to do, which is why it returns an error.
6. Code causes an error. `let` variables can only be accessed in the block it was defined in. Since the var `let discountedPrice` was defined in the for loop, it cannot be accessed outside the for loop, which is what line 13 trie to do, which is why it returns an error.
7. Line 14 prints `150`.
8. Function will return the array of discounted prices, `[50, 100, 150]`
9. Code causes an error. `let` variables can only be accessed in the block it was defined in. Since the var `let i` was defined in the for loop, it cannot be accessed outside the for loop, which is what line 12 tried to do, which is why it returns an error.
10. Line 12 prints `3`.
11. Function will return the array of discounted prices, `[50, 100, 150]`
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student[Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. Output: `32`. int 2 was mapped to string rep of '2' and appended to the string '3'.
    B. Output: `1`. string '2' was mapped to int rep of 2 and subtracted from 3
    C. output: `3`. null value was mapped to its int rep 0 and added to 3.
    D. Output: `3null`. null value was mapped to string rep of 'null' and appended to the string '3'.
    E. Output: `4`. boolean value `true` was mapped to its int rep 1 and added onto 3
    F. Output: `0`. boolean value `false` was mapped to its int rep 0 and appended the null value which was mapped to its integer representation 0.
    G. Output: `3undefined`. undefined val was mapped to its string rep 'undefined' and appended to the string '3'
    H. Output: `NaN`.undefined value was mapped to its integer representation NaN and subtracted the string '3' which was mapped to its integer value 3. 
14. A. true. string '2' is mapped to int value of 2, which is greater than 1 so it returns true.
    B. false. string '2' is lexicographically greater than string '12'.
    C. true. string '2' is mapped to int value of 2 which is then compared to int 2.
    D. false. 2 cannot be compared to string '2'
    E. false. true is mapped to int value of 1, which is not == to int 2.
    F. true. Boolean (2) converted 2 to a bollean true value, which makes it == to `true`. 
15. the === operator checks for data type first before checking for equality, whereas == converts two values to the same data type before checking for equality. 
16. see part2-question16.js
17. Output: 2, 4, 6. First `modifyArray([1, 2, 3], doSomething)` creates a `newArr` that calls the `doSomething` function on each of the original arr's elements ([1, 2, 3]). doSomething doubles the numeric input it is given, so newArr is populated by doubles of the original arr [1, 2, 3]. Returning newArr, you get the array [2, 4, 6].
18. see part2-question18.js
19. Output: 1, 4, 3, 2. First it prints out 1 from line 2, then 4 from line 5 due to console.log functions. at second 0, right after printing 1 and 4, it prints 3. Then 1000 ms later, it prints out 2. 
