# Tips for good code writing, README formatting, and other things

## Commenting your code

you need to make sure you add comments to your code.  If you're smart , you'll write your comments
at the same time as you're writing your code.  Remember comments are any text that follows // or any
text between /* and */ .  Here's the 3 big rules to commenting:

* It is a good practice to put your name, the date you wrote the code, and a brief description of what
 the code does at the top.
 ```C++
 //Karl Helmstetter
 //November 19th, 2020
 //Code Title: Here, I would write one sentence about what this code is supposed to do.
 ```
 * You want to have enough comments that someone reading your code can understand
 what is happening. 
 ```C++
 int BlinkCounter = 0; // This Variable is easy to understand, no comment would be needed.
 int LED1 = 9;
 int roflcopter = 0; //If you're going to use silly variable names, you need to explain what the variable is for.
 
 void setup(){
 pinMode(LED1, OUTPUT); // If this is NOT a novel piece of code for you, then there's no need to comment on it. 
 }
 
 void loop(){
 /*
 Sometimes, it makes sense to write code in blocks.
 These symbols are used to comment off multiple lines, without having to comment code each line.
 Nice and simple, right?
 
 The reason we comment our code is to say what the code is doing, but in simple english.
 
 Theres no reason to comment every single line, you can sometimes make more sense by adding a single comment 
 at the top of a block of code, like this:
 */
 
 //This will make LED1 blink 2 times a second.
 digitalWrite(LED1, HIGH);
 delay(250);
 digitalWrite(LED!, LOW);
 delay(250);
 }
 ```
 
 * You will be graded on this, so the bare minimum you should do is step #1  and commenting on any 
 code that you just did for the first time.  For your second assignment, there's no reason to comment on things like "pinMode" or "digitalWrite"
