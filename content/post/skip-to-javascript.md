---
title: Skip To Javascript
date: '2019-05-04T16:40:40+05:30'
draft: false
categories:
  - Javascript
  - Programming
tags:
  - javascript
  - programming
  - coding
keywords:
  - javascript
  - programming
  - coding
autoThumbnailImage: true
thumbnailImagePosition: left
thumbnailImage: ''
---
![javascript logo](/images/uploads/logo.png)

**Hi guys!** we are going to skip right into modern Javascript. this tutorial may be splited into several parts based upon how much i can cover about each topic in Javascript.  

So lets jump right into the Javascript.

## Why Javascript?

You may wonder why to choose Javascript from several programming languages out there. Well for me it doesn't need an initial setup. All you need is a text editor and browser in your computer. It is the most trending programming language right now.

## Javascript:

Javascript is a scripting language used for creating web pages, web applications, games etc...

 (scripting language is a programming language that doesn't need any complicated setup.)

## Lets Skip In:

Open your preferred text/source-code editor there are plenty of them available right now. Some of the popular ones are are [VS Code](https://code.visualstudio.com/ "Download VS Code") , [Atom](https://atom.io/ "Download Atom") , [Brackets](http://brackets.io/ "Download Brackets"). 

Create a new file with **.js  **extension (Example: **main.js**).

That's it we are ready to begin our journey.

## Variables and Conditional Statements:

**main.js**
```
let num = 200;
let ans = num/2;
if (ans === 0)
{   
    document.write("number is even");
} 
else
{
   document.write("number is odd");
}
```

You may wonder what is shown above. Just try to read it as it is and you may get a idea of what is going on. Yes, the above code is used to check whether a number is odd or even.

### 1) Variables:

The words declared using **let** keyword are known as **variables** and they store values that are given after an equal (=) sign.

As you seen above variable can hold numbers, result of an arithmetic expression, strings and more.

> Strings  is anything written in between " " or ' ' in Javascript. In the above example  "number is even" is a string. 
>
> Numbers, strings are generally called as datatypes in Javascript. there are more datatypes in javascript than the ones mentioned here.
> Click  [here](https://www.w3schools.com/js/js_datatypes.asp)  for viewing all the datatypes that variables can hold in in Javascript.

### 2) Conditional Statements:

Conditional statements run according to a particular condition.

In above example **if(){  } else{ }** block is a conditional statement.The if block executes if the condition is true otherwise else block gets executed.

In JavaScript we have the following conditional statements:

* if - specifies a block of code to be executed, if a specified condition is true
* else - specifies a block of code to be executed, if the same condition is false
* else if - specifies a new condition to test, if the first condition is false
* switch - specifies many alternative blocks of code to be executed

[Click here](https://www.w3schools.com/js/js_if_else.asp "Conditional Statements") for more info about conditional statements.

## Running a Javascript program:

Save the above "odd or even" code as main.js. This is our Javascript program.
To execute a Javascript program we need a browser. Since browsers displays only HTML documents we need an HTML file to embed our Javascript file.

So create an **index.html** file and copy the below code into it.

```
<!DOCTYPE html>
    <head>
        <title></title>
    </head>
    <body>
        <script src="main.js"></script>
    </body>
</html>
```

This is a simple html document structure with our Javascript file is embeded using **<script></script>** tags **src** (source) attribute.

Now save the file and run it by either right clicking it and selecting your browser or dragging it into your browser.

You will see a output like the one shown below. 

**Output**

![null](/images/uploads/screenshot_2019-05-05_15-12-25.png)

## Your Project:

Now that you know some Javascript let's put it into some practice.
Modify the above program to add 10 to the number if number is even else subtract 10 from the number.
Don't worry it's simple just think. If you stumble check [my repositoy](https://github.com/fosscaml/skiptocodetuts "skiptocoderepository") for the project files.

## Conclusion:

Don't worry if you find some concept hard to grasp just ask for help in the below comment section.

If you find this tutorial simple don't worry we will skip into some complex stuffs really soon.

**See you later!**
