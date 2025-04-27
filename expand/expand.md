# Expand

1. Some JavaScript developers believe that most of the issues with JavaScript steam from its asynchronous nature, its loose typing, and the web platform it runs on. For each of the three reasons listed, explain in your own words why a developer might believe that it is a pain point.

> Asynchronous nature: JavaScript often runs code that does not wait for other code to finish executing. When it calls asynchronous functions, it keeps executing the rest of the code and does not wait for them to finish and return something. This can make it harder to predict and understand the flow of the code, hence making it much more difficult to debug.

> Loose typing: Like Python, is a dynamically typed language, so you do not need to declare the data type of the variable when you create it. Even though this makes it more flexible, it can also lead to bugs that can be hard to find, especially when JavaScript may attempt to convert variables to different types without warning when we may not want it to.

> Web platform: JavaScript was created to run on web browsers. However, the code may run on different browsers as browsers may interpret JavaScript differently from each other. This means that developers often have to write code that works for different browsers, which can take a lot of time and work.

2. Related to the first question, why do you believe that the developer(s) who created JavaScript made it loosely typed? Why do you think they added asynchronous features?

> I think the developer(s) who created JavaScript made it a loosely typed language to make it easier for developers, particularly beginners, to write code. Also, this allows for more flexibility in the code and fewer chances for errors when declaring and using variables. I think they added asynchronous features to allow for more efficient web applications. If we waited for every single function to finish before moving to the next one, it would make the web applications VERY VERY slow. For example, if we are fetching data from a server, we may not want to wait until we finish getting all the data before we continue running the rest of the code. Asynchronous features allow us to run other code while waiting for other code to finish running, making it a much better experience for users.

3. What are the key differences between a compiled language and an interpreted one? Which one is JavaScript? What are the benefits & drawbacks of JavaScript being made that way?

> A compiled language is a programming language that is compiled into machine code before we run it. Some examples of compiled languages are C++ and Java. While they execute code faster and are able to catch errors before running the code, they require the code to be compiled first, which can take a non-trivial amount of time. An interpreted language, like JavaScript, is a programming language that is read and executed line by line, without compilation. While this makes interpreted languages more flexible and easier to debug, they are often a lot slower than compiled languages. In the case of JavaScript, an interpreted language, it allows for faster development and easier debugging, but it can lead to much slower code execution and performance.

4. The professor believes that, though sometimes misused, JavaScript frameworks are incredibly powerful tools that can help teams work more efficiently and effectively. Given that, why do you believe he is focusing more on vanilla JavaScript for this course? What are the benefits of mastering vanilla JS first? What are the drawbacks of not learning a framework?

> I think the professor is focusing more on vanilla JavaScript so that students can understand the core principles of JavaScript before moving onto frameworks. If you don't understand how JavaScript works, using Frameworks like React and Angular can be very hard to understand, especially when something does not work as intended. However, without learning a framework, it may be a lot harder to build large-scale applications as frameworks can provide a lot of features that make it easier to build and maintain web applications.

5. Explain, in your own works, how you think this lab relates to your project. How might you be able to use this information in your own project?

> This lab shows why it is important to understand the core principles of JavaScript, especially without the use of AI. It also shows how important it is to plan and visualize a web application before going into the code. In our project, building flowcharts or diagrams can help me and my team understand how users may interact with the application, which can then help us design and build an application with better user interactions.