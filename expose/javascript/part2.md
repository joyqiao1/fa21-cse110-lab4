1. The code will print 3 as i = 3 at this time. The reason is in the for loop, 0 <= i < 3, so after the code runs i = 2, it will increase i to 3, and then i = 3 out of range, so it will out of the loop, and print the current i's value which is 3.
2. The code will print 150. The variable discountedPrice defined as prices[i] * (1 - discount), and at this time i = 2 and discount = 0.5, so prices[2] = 300 and 1 - discount = 1 - 0.5 = 0.5. Therefore 300 * 0.5 = 150
3. The code will print 150. As question 2 mentioned we get the discountedPrice is 150. Then the finalPrice = Math.round(discountedPrice * 100) / 100, so it would be (150 * 100) / 100 = 150. Therefore it will print 150.
4. The code will return discounted as an array of size 3: [50, 100, 150]. In the for loop, the last caculation step is push finalPrice to discounted. If we calculate the discounted: <br>
when i = 0: discountedPrice = 100 * (1 - 0.5) = 50 <br>
            finalPrice = 50 * 100 / 100 = 50  <br> 
when i = 1: discountedPrice = 200 * (1 - 0.5) = 100 <br> 
            finalPrice = 100 * 100 / 100 = 100  <br> 
when i = 2: discountedPrice = 300 * (1 - 0.5) = 150 <br>
            finalPrice = 150 * 100 / 100 = 150 <br>
Therefore, we push these three values to discounted which is an array of size 3 [50, 100, 150] <br>
5. The code causes an error. Since it uses "let" to declare the variable, it cannot be called out of the for loop block, it’s only visible inside that block. In other words, i is not defined when line 12 runs.
6. The code causes an error. Same reason as the question. The variable discountedPrice's is declared as let, so it cannot be called out of the for loop block,it’s only visible inside that block. It will shows discountedPrice is not defined when line 13 runs.
7. The code will print 150. Although the variable finalPrice is declared as let, but when line 14 runs, they are in the same block, so the code actually compiled successfully. Therefore, we go through the for loop, and get the final answer for finalPrice is 150.
8. The code returns an array of size 3: [50, 100, 150]. Same reason with question 7. Using let declare the variable finalPrice, but the line 16 runs in the same block, so the code actually compiled successfully. As I showed the calculation process in the question 4. The variable discounted is pushed by the value of finalPrice. Therefore, it returns an array of the values [50, 100, 150].
9. The code causes an error. Smae reason with question 5. Since it uses "let" to declare the variable, it cannot be called out of the for loop block, it’s only visible inside that block. In other words, i is not defined when line 12 runs.
10. The code will print 3. The variable lenght is declared as const = prices.length. It will be 3 forever, and can't change anymore. Therefore, line 12 will print the value of this variable which is 3.
11. This function will return as an array of size 3: [50, 100, 150]. The variable declared as const, so it would be some values that can't be changed. When we go through the for loop, the for loop will run 3 times, and for each time a new value willl be pushed to discounted, so the discounted not be changed for every time but be updated for three times, and it works for const, so we calculate the value for discountedPrice each time which is 50, 100, and 150. Then push these three values to discounted. When return discounted, these three values will be returned.
          
