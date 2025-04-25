# Part 2. A Little More of a Challenge...

In this next section, use what you understand about the differences between declaring variables with var, let, and const to help you work with a more complicated block of code.

![image1](images_pt2/image1.png)

1. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^

> The code will print

```
3
```
> `i` is function scoped because it was declared using `var`. Therefore, `i` is accessible anywhere inside the `discountPrices` function. The `for` loop runs 3 times, from `i = 0` to `i = 2` for the array `[100, 200, 300]`, which has length 3. After the final iteration of the loop, `i` is incremented from `2` to `3`, which is the value of `i` when the code reaches line 12. Therefore, the code prints `3` at line 12.

![image2](images_pt2/image2.png)

2. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^

> The code will print

```
150
```

> `discountedPrice` is function scoped because it was declared using `var`. Therefore, `discountedPrice` is accessible anywhere inside the `discountPrices` function. The `for` loop runs 3 times, from `i = 0` to `i = 2` for the array `[100, 200, 300]`, which has length 3. During the final iteration of the loop, when `i = 2`, `discountedPrice` is assigned the value of `prices[i] * (1 - 0.5)`, which is `300 * 0.5 = 150`. After the loop is finished, `discountedPrice` is still accessible with value `150`, so the code will print `150` on line 13.

![image3](images_pt2/image3.png)

3. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^

> The code will print

```
150
```

> `finalPrice` is function scoped because it was declared using `var`.  Therefore, `finalPrice` is accessible anywhere inside the `discountPrices` function. From question 2, `discountedPrice` is set to `150` at the beginning of the final iteration of the `for` loop. In this same iteration, `finalPrice` is reassigned to `Math.round(discountedPrice * 100) / 100`, which is `Math.round(150 * 100) / 100 = Math.round(15000) / 100 = 15000 / 100 = 150`. After the loop is finished, `finalPrice` is still accessible with value `150`, so the code will print `150` on line 14.

![image4](images_pt2/image4.png)

4. ^^^ What will this function return? Give a brief explanation why. If the code causes an error, explain why.^^^

```
```

![image5](images_pt2/image5.png)

5. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).

```
```

![image6](images_pt2/image6.png)

6. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^

```
```

![image7](images_pt2/image7.png)

7. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^

```
```

![image8](images_pt2/image8.png)

8. ^^^ What will this function return? Give a brief explanation/ If the code causes an error, explain why. ^^^

```
```

![image9](images_pt2/image9.png)

9. ^^^ What will happen at line 11 and why? If the code causes an error, explain why. ^^^

```
```

![image10](images_pt2/image10.png)

10. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^

```
```

![image11](images_pt2/image11.png)

11. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^

```
```