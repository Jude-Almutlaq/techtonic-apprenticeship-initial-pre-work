# techtonic-apprenticeship-initial-pre-work

#### Which freeCodeCamp lessons were most
difficult for you and why? Please be as
in-depth as possible. There is no limit to
the number of responses or lessons
mentioned. We have provided you with the
template below and expect you to format any
additional entries in the same way, so
simply copy and paste the following three
lines for each lesson you struggled with,
change the subject title and the lesson
title, and fill out your answers under the
lessons you struggled with below:
### Introduction to Basic HTML and HTML5
**Create a Set of Radio Buttons**
- I didn't know there was an easy way of making a setup like this for questions with single answers. it is also good to know that it is common practice to use a for attribute in the label with a value equal to the input id. I'm not familiar with assistive technologies or how they work work but knowing best practive for them seems likely to be useful.
### Introduction to Basic HTML and HTML5
**Create a Set of Checkboxes**
- I am a little confused as to why these inputs need to be wrapped in a label element and if they would lose some functionality if they weren’t? Is that just common practice in order for it to look nicely formatted?
### Basic CSS
**Use an id Attribute to Style an Element**
- I did not realize that ids were more specific than classes and therefore override the styles of the class if both are applied. I can see where this would be helpful when you want two items in the same class to have mostly the same styles but one slightly different and also where this can cause problems if you don't realize where the style is coming from. 
### Basic CSS
**Use CSS Variables to change several elements at once**
- The variables are very cool functionality that I didn't know about. I feel like above all it makes the code cleaner to look at so when you see what color the element is it's not just gray, it penguin-skin which gives you more information about what the element is and what it's doing. It also seems you can use this for more than just colors which is really cool. 
### CSS Flexbox
**Align Elements Using the align-items Property**
- This makes everything make so much more sense! I've used flexboxes and couldn't find a consistent way to center items inside of them but that is because I was using some rows and some columns and now I get the actual difference between justify content and align-items.
### CSS Grid
**Use grid-column to Control Spacing**
- This one took me several tries because of how the grid lines are numbered and the fact that you span three numbers i.e 1 / 3 to make the item span two spaces. It was a little bit of a difficult concept to wrap my head around at first.
### CSS Grid
**Align an Item Horizontally using justify-self**
- It took me a little bit to understand why when you justify the item to center it becomes so small. I understand now that you are taking it off the pre-set stretch and now it is only the size of the text that is inside of it. it leaves me wondering how to justify only the items inside the grid item, I assume center-text will work for text but what if I had a photo inside the grid that I wanted centered while keeping a grid background that stayed stretched? I wonder if I would just have to do the math and use margins or if there is a better way.
### CSS Grid
**Place Items in Grid Areas Using the grid-area Property**
- This is an interesting way way to avoid using grid-column or grid-row that may make the code make more sense since you are using names to identify where the items are going as opposed to just numbers i.e "header" as opposed to 2 / 4.
### CSS Grid
**Limit Item Size Using the minmax Function**
- I am a little confused as to what this is actually doing and why. I see that when I resize the window, the columns have a minimum height and don't get smaller as opposed to the rows which resize consistantly. My question is on the fr unit, as I understand that means fraction so why would we use 1fr as the maximum height when it would be smaller than the 90px minimum height in most cases when resizing the screen. I guess that actually does make sense, I just had to work through it, the items will get bigger when the whole grid is larger and smaller until the items reach 90px, I think the fr unit was just throwing me off before. 
### Basic JavaScript
**Stand in Line**
- I struggled with this a little, partially because I forgot the shift command, mostly because I forgot to use 'var' before my variable... woops.
### Basic JavaScript
**Selecting from Many Options with Switch Statements**
- I have never used switch statements before, this is a cool tool and an interesting alternative to long else if chains although setting a case for each scenario seems like it could be tedius or not possible.
### Basic JavaScript
**Adding a Default Option in Switch Statements**
- Aha! My previous concern about the switch statements is revoked, the default is a nice tool to avoid that problem. Also, this took me a little while bacuse I didn't realize the letters needed to be in quotes, seems like it should have been obvious, alas, it was not.
### Basic JavaScript
**Multiple Identical Options in Switch Statements**
- This is another cool tool although using else if statements for this scenario seems better because you can use > and < with numbers, but I can see where this is better for other things like strings where multiple answers are accepted like "yes" and also "Yes" as inputs or something. 
### Basic JavaScript
**Replace Loops using Recursion**
- This was a bit of a difficult concept for me to grasp. I see now that we are calling the same function within a function and just passing in the arguement - 1 which will make the function essentially loop until the first if statement is met and the return kicks you out of the function before it loops again. It was just a little confusing at first.
### Basic JavaScript
**Profile Lookup**
- This challange was more difficult for me than most. I think I was approaching the problem wrong by thinking "how do I chack that the property doesn't exist?" instead of checking first that it does and then using an else statement. I also struggled with where to put the "no such contact", not realizing it needs to go outside the for loop.
### Basic JavaScript
**Use the Conditional (Ternary) Operator**
- This is very cool shorthand I've never used before, easy to understand and read, saves on lines of code. I like it!
### Basic JavaScript
**Use Recursion to Create a Range of Numbers**
- I struggled a little because I forgot to pass in both startNum and endNum - 1 into the recurring function, of course it needs both arguements passed in, I just wasn't thinking about it. 
### ES6
**Use a Rest Parameter with Function Parameters**
- I understand the rest parameter but am confused as to what the reduce function is doing and where the a and b are coming from... it seems from looking up the reduce function the a is a callback and the b is the initial value which still confuses me. Oh no, I see, we are using an arrow function to pass in the arguements a and b and then add them together as the callback and the initial value is 0... I get it now.
### ES6
**Use Destructuring Assignment to Pass an Object as a Function's Parameters**
- I am confused on this one when we get rid of 'stats' how does the function know which object to pull max and min from? What if two objects had max and min keys, how would you specify the object the function is using? ... Oh yeah, when you call the function the object is the arguement, silly me. 
### ES6
**Create Strings using Template Literals**
- I had to look up the answer for this question. It uses the map function which I don't believe we've been introduced to so that was confusing for me. I believe I could have used a loop to do the same thing but it would be many more lines of code. The map function is really cool and helpful taking each item in the array and doing something with it, I've never used it before but I can see many uses.

