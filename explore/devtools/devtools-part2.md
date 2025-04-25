## DevTools - Debugging

[The Lab 4 DevTools site](https://cse110-fa22.github.io/Lab4_Hosted) contains a simple program that calculates the sum of two input numbers. However, the program is not functioning as expected. You will be using the Chrome DevTools to debug the Javascript code to fix this program.

Note: Do not debug using console.log(). Practice using the Debugging tool in the Chrome DevTools for this exercise.

During the debugging process, include the following screenshots:

* When the debugger is triggered, set a breakpoint at the initialization of the local variable *result* in calculateSum(). Take a screenshot of the list of breakpoints containing the breakpoint you just added. Name it **result-calculateSum.png** (or whatever image extension you would like to use).

> Refer to `result-calculateSum.png` in the `expand/screenshots` directory.

* Add watch expressions to find the value of *num1* and *num2*, and the **data type** of *result*. Take a screenshot of the watch expressions list. Name it **result-dataType.png** (or whatever image extension you would like to use).

> Refer to `result-dataType.png` in the `expand/screenshots` directory.

Answer the following questions:

1. What was the bug?

> The program was not returning the correct sum of the two input numbers. The issue was that the program was trying to add two strings rather than two numbers. The `document.getElementById("num1").value` and `document.getElementById("num2").value` calls were returning strings, and the program did not convert them to numbers before adding them. Instead, it concatenated the two input strings together. For example, if the user entered `'1'` and `'2'`, the program would return `'12'` rather than `3`.

2. How would you fix it? Include a screenshot of your fix. Name it **fix.png** (or whatever image extension you would like to use).

> To the fix bug, I would convert the input strings to Numbers before adding them, using the `Number()` function to typecast `num1` and `num2` to numbers.

> Refer to `fix.png` in the `expand/screenshots` directory for the fixed code.