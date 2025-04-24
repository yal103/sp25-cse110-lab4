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

> 