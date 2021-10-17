Q1. The code will print 3 as i = 3 at this time. The reason is in the for loop, 0 <= i < 3, so after the code runs i = 2, it will increase i to 3, and then i = 3       out of range, so it will out of the loop, and print the current i's value which is 3. <br>
Q2. The code will print 150. The variable discountedPrice defined as prices[i] * (1 - discount), and at this time i = 2 and discount = 0.5, so prices[2] = 300 and 1     - discount = 1 - 0.5 = 0.5. Therefore 300 * 0.5 = 150 <br>
Q3. The code will print 150. As question 2 mentioned we get the discountedPrice is 150. Then the finalPrice = Math.round(discountedPrice * 100) / 100, so it would       be (150 * 100) / 100 = 150. Therefore it will print 150.<br>
Q4. The code will return discounted as an array of size 3: [50, 100, 150]. In the for loop, the last caculation step is push finalPrice to discounted. If we             calculate the discounted: <br>
            when i = 0: discountedPrice = 100 * (1 - 0.5) = 50 <br>
            finalPrice = 50 * 100 / 100 = 50  <br> 
            when i = 1: discountedPrice = 200 * (1 - 0.5) = 100 <br> 
            finalPrice = 100 * 100 / 100 = 100  <br> 
            when i = 2: discountedPrice = 300 * (1 - 0.5) = 150 <br>
            finalPrice = 150 * 100 / 100 = 150 <br>
    Therefore, we push these three values to discounted which is an array of size 3 [50, 100, 150] <br>
Q5. The code causes an error. Since it uses "let" to declare the variable, it cannot be called out of the for loop block, it’s only visible inside that block. In       other words, i is not defined when line 12 runs.<br>
Q6. The code causes an error. Same reason as the question. The variable discountedPrice's is declared as let, so it cannot be called out of the for loop block,it’s     only visible inside that block. It will shows discountedPrice is not defined when line 13 runs.<br>
Q7. The code will print 150. Although the variable finalPrice is declared as let, but when line 14 runs, they are in the same block, so the code actually compiled       successfully. Therefore, we go through the for loop, and get the final answer for finalPrice is 150.<br>
Q8. The code returns an array of size 3: [50, 100, 150]. Same reason with question 7. Using let declare the variable finalPrice, but the line 16 runs in the same       block, so the code actually compiled successfully. As I showed the calculation process in the question 4. The variable discounted is pushed by the value of         finalPrice. Therefore, it returns an array of the values [50, 100, 150].<br>
Q9. The code causes an error. Smae reason with question 5. Since it uses "let" to declare the variable, it cannot be called out of the for loop block, it’s only         visible inside that block. In other words, i is not defined when line 12 runs.<br>
Q10. The code will print 3. The variable lenght is declared as const = prices.length. It will be 3 forever, and can't change anymore. Therefore, line 12 will print      the value of this variable which is 3.<br>
Q11. This function will return as an array of size 3: [50, 100, 150]. The variable declared as const, so it would be some values that can't be changed. When we go       through the for loop, the for loop will run 3 times, and for each time a new value willl be pushed to discounted, so the discounted not be changed for every         time but be updated for three times, and it works for const, so we calculate the value for discountedPrice each time which is 50, 100, and 150. Then push           these three values to discounted. When return discounted, these three values will be returned.<br>
Q12. A: console.log(Student.name); <br>
    B: console.log(Student["Grad Year"]); <br> 
    C: Student.greeting(); <br>
    D: console.log(Student["Favorite Teacher"].name); <br>
    E: console.log(Student.ourseload[0]); <br>
Q13. A. 32. Because integers map to their exact string representation.<br>
    B. 1. Because strings map to their exact integer representation.<br>
    C. 3. For maths and other comparisons, null are converted to number, so 3 + null = 3 + 0 = 3.<br>
    D. 3null. In this case, '3' maps to string "3", so combine with null is 3null.<br>
    E. 4. For boolean values, true becomes 1 and false becomes 0, so true + 3 = 1 + 3 = 4.<br>
    F. 0. For boolean values, true becomes 1 and false becomes 0. For maths and other comparisons, null are converted to number, so 0 + 0 = 0.<br>
    G. 3undefined. '3' is type of string, same as undefined, so combine together becomes 3undefined.<br>
    H. NaN. The number is “read” from the string, so the error gives NaN.<br>
Q14. A. true. String '2' becomes a number 2, so 2 > 1 is true.<br>
    B. false. Dictionary comparison, first char "2" is greater than the first char "1", so '2' < '12' is false.<br>
    C. true. String '2' becomes a number 2, so 2 == 2 is true.<br>
    D. false. 2 and '2' are different data types, so using strict equality operator to check is return false.<br>
    E. false. For boolean values, true becomes 1 and false becomes 0, so true == 1 is false.<br>
    F. true. In Boolean conversion, "Values that are intuitively “empty”, like 0, an empty string, null, undefined, and NaN, become false. Other values become           true", so In this case value is 2, it's true. <br>
Q15. "==" can compare values of different types, and converts the values to numbers, but it cannot differentiate 0 or empty string from false. "===", the strict         equality operator checks the equality without type conversion. It will return false if check with two different types values, but when compare 0 with false it       will return false.<br>
Q17. The result is an array [2, 4, 6]. Call modifyArray([1, 2, 3], doSomething), so go through the for loop inside of the function:
            when i = 0; array[0] = 1, callback(array[0]) = dosomething(array[0]) = 1 * 2 = 2; push 2 to newArr. <br>
            when i = 1; array[1] = 2, callback(array[1]) = dosomething(array[1]) = 2 * 2 = 4; push 4 to newArr. <br>
            when i = 2; array[2] = 3, callback(array[3]) = dosomething(array[2]) = 3 * 2 = 6; push 6 to newArr. <br>
            Therefore, the final answer is [2, 4, 6].<br>
Q19. 1 <br>
     4 <br>
     3 <br>
     2 <br>

