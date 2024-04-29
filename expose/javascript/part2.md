### Part 2. A Little More of a Challenge...

1. 3 is printed.
2. 150 is printed.
3. 150 is printed.
4. [50, 100, 150]. The var discounted is defined as an empty list. In the for loop, for every element in the price list, the price is discounted and pushed into the discounted list. The list is returned in line 16 because it is defined with var, and is accessible there.
5. Error, because i is defined with the keyword let, so it is not accessible outside of the for loop.
6. Error, because discountedPrice is defined by the keyword let, so it is not accessible outside of the for loop.
7. 150 is printed.
8. [50, 100, 150]. The variable discounted is defined as an empty list. In the for loop, for every element in the price list, the price is discounted and pushed into the discounted list. The list is returned in line 16 because it is defined with let, and is accessible there.
9. Error, because i is defined with the keyword let, so it is not accessible outside of the for loop.
10. 3 is returned.
11. [50, 100, 150]. The const variable discounted is defined as an empty list. Because you are able to append elements to a const list, in the for loop, for every element in the price list, the price is discounted and pushed into the discounted list. Finally, discounted is returned.
12. -
    A.  student.name
    B.  student["Grad Year"]
    C.  student.greeting()
    D.  student["Favorite Teacher"].name
    E.  student.courseLoad[0]
13. -
    A.  '32', since the addition is used as string concatenation
    B.  1, since you can't subtract strings so the string was converted to an int
    C.  3, since null is converted to 0
    D.  '3null' since null is converted to a string
    E.  4, since true is converted to 1
    F.  0, since both false and null are converted to 0
    G.  '3undefined' since undefined is converted to a string
    H.  NaN, since the '3' is converted to 3, but undefined converted to an int is NaN
14. -
    A.  true, because '2' is converted to 2
    B.  false, because '2' comes after '12' in lexicographic order
    C.  true, because '2' is converted to 2
    D.  false, because 2 and '2' are not the same types of data
    E.  false, because true is treated like 1
    F.  true, because any number input other than 0 and -0 return true
15. === checks if data are the same type, and == checks if the values are equal
16. [Answer](part2-question16.js)
17. In the for loop, the values in the parameter array are multiplied by 2, and the new value is copied into newArr. Therefore, modifyArray returns [2, 4, 6]
18. [Answer](part2-question18.js)
19. 1
    2
    3
    4