# Javascript Console Methods That will improve your debugging
Alot of us (Javascript developers) have been using the console to debug our applications 
but most of the time what we use only console.log but there are other method which you can use in different cases

Today I am going to show your some console methods that weill help you debug faster and also 
code faster. 

There are more that 15 console methods you can use and each of them have their unique cases where
they are applied.

## Basic console Logging methods
We will start of with the basic console methods which many of us know about. We will move from the known to the unknown

* Console.log("Log a variable or activity")
* Console.info("shows information")
* Console.warn("Shows warning")
* Console.error("displays errors")

Before you can see the output of this codes you need to open your console and select the appropriate tab to show you any of the above. You can show or hide any of the console by toggling it.


![Console](img.PNG)

As you can see from the above image all the tabs are are selected except warning which you can select by toggling it. 

## Examples of Basic Console Logging Methods

Now lets look at example of how to use this javascript basic console to debug our code. 

```javascript
    let name = "Nwankwo Ifeanyi";

    console.log("The student name is ", name)
```




![Console.log output](logoutput.PNG)

As you can see my log tab is selected and that is why the console.log was able to show the output.


```javascript
    console.info("const values cannot be changed...")
```

![Console.info output](infooutput.PNG)

From the picture above you will see that my info tab is selected. Also you notice the i icon beside the text which shows that this is info.

```javascript
    console.warn("const values cannot be changed...")
```

![Console.warn output](warningoutput.PNG)

From the picture you can see the warning side beside the text which shows this is a warning.


```javascript
    console.error("Undefined variable name")
```

![Console.error output](erroroutput.PNG)

From the picture you can see the error sign beside the text and also this is mostly in red color to show it is an error.



