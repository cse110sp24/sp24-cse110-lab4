1. 3 is printed
2. 0.5 is printed
3. 150 is returned
4. `[ 50, 100, 150 ]` will be returned. This is because the `finalPrice` is pushed to the array `discounted` at each iteration of the `for` loop. 
5. An error is thrown because the scope of `i` is limited to the `for` loop
6. 0.5 is printed
7. 150 is returned
8. `[ 50, 100, 150 ]` will be returned. This is because the `finalPrice` is pushed to the array `discounted` at each iteration of the `for` loop. 
9. An error is thrown because the scope of `i` is limited to the `for` loop
10. 3 is printed
11. `[ 50, 100, 150 ]` will be returned. Even though `discounted` is declared as `const`, the contents of the array can still be modified--you just can't reassign `discounted` to a different reference
12. 
    1.  `student.name`
    2.  `student["Grad Year"]`
    3.  `student.greeting()`
    4.  `student["Favorite Teacher"].name`
    5.  `student.courseLoad[0]`
13. 
    1.  '32'
    2.  1
    3.  3
    4.  '3null'
    5.  4
    6.  0
    7.  '3undefined'
    8.  NaN
14. 
    1.  true
    2.  false
    3.  true
    4.  false
    5.  false
    6.  true
15. `==` performs type conversions before comparing whereas `===` performs equality checks without type conversions
16. 
    ```js
    for (const car in statistics) {
        if (car[0] === 'r' || statistics[car] % 2 === 1) {
            console.log(car);
        }
    }
    ```
17. `[ 2, 4, 6 ]` will be returned. This is because the function `callback` is applied to each element in `array`. In this case, each element is multiplied by 2 because `callback` is `doSomething()`.
18. 
    ```js
    setInterval(() => {
        let d = new Date();
        let time = d.toLocaleTimeString();
        console.log(time);
    }, 1000)
    ```
19. It outputs 
    ```
    1
    2
    3
    ```
    with time delay increments in between.