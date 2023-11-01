**DAY 1 LAB 1**

<u>Part 1</u> Syntax Error

https://replit.com/@rocknrome/SEAL-Day-1-LAB?v=1

<u>Original code:</u>

console.log("Making your way in the world today takes everything you've got.");
console.log("Taking a break from all your worries, sure would help a lot.");
console.log("Wouldn't you like to get away?");
console.log("Sometimes you want to go");
console.log("Where everybody knows your name,");
console.lo("and they're always glad you came.");
console.log("You wanna be where you can see,";
console.log("our troubles are all the same");
console.log("You wanna be where" "everybody knows");
console.log("Your name.");



<u>Fixed code:</u> 

console.log("Making your way in the world today takes everything you've got.");

console.log("Taking a break from all your worries, sure would help a lot.");

console.log("Wouldn't you like to get away?");

console.log("Sometimes you want to go");

console.log("Where everybody knows your name,");

console.log("and they're always glad you came.");

console.log("You wanna be where you can see,");

console.log("our troubles are all the same");

console.log("You wanna be where everybody knows");

console.log("Roman Larionov");





<u>Part 2</u> Boolean Expressions

By just looking at the following expressions, determine in your mind whether or not each will evaluate to **true** or **false**

1. `999 > 999`  FALSE
2. `999 == 999` TRUE
3. `999 != 999` FALSE
4. `-5 >= -4` FALSE
5. `100 <= -100` FALSE
6. `20 + 5 < 5` TRUE
7. `81 / 9 == 9` TRUE
8. `9 != 8 + 1` FALSE 



<u>Part 3</u> Assignment Operator vs Equality operator

Write: What is the difference between:

the **assignment operator** `=`

and the **equality operator** `==`

Answer: The major difference is that the Equality operator also compares the type of the variable. 



<u>Part 4</u> While Loops

### 1

Write a *while* loop that will log in the console

```
'Ginger chocolate honey patties'
```

1000 times. You can test it out with a smaller number first, such as 10, and when that works, use 1000.

Make sure you do not run an infinite loop! If you do, close your Terminal. Oops!

Answer: Construct is like following WHILE (TRUE) {RUN BLOCK OF CODE} until it is not TRUE

`let i = 2; //declaring the variable (counter)`
`while (i < 5) { // setting up loop's condition.  Change 5 to 1000 as asked in the task`
`console.log("Ginger chocolate honey patties"); //running necessary code`
`i++; //adding counter's increment`
`}`



Second version: 

`for (let i = 2; i < 10; i++) { //FOR loop construct. Declaring variable, counter and loop condition. Change 10 to 1000 as asked in the task`
`console.log("Ginger chocolate honey patties"); //running necessary code`
`}`



### **2**

Write another *while* loop that counts from 0 to 1000 and will log in the console the current loop number.

> => 0
>
> => 1
>
> => 2
>
> => 3

etc.

Answer:

`let j=0; //declaring the initial variable (counter)`
`while (j < 5) { // setting up loop's condition.  Change 5 to 1000 as asked in the task`
`console.log("=> " +j); //running necessary code, printing loop number`
`j++; //adding counter's increment`
`}`



### 3

Write another *while* loop that prints a message to the console *and* concatenates the current loop number. Make it count from 0 to 1000.

> => "Current loop number is: 0"
>
> => "Current loop number is: 1"
>
> => "Current loop number is: 2"
>
> => "Current loop number is: 3"

Answer: 

`let k=0; //declaring the initial variable (counter)`
`while (k < 5) { // setting up loop's condition.  Change 5 to 1000 as asked in the task`
`console.log("Current loop number is: " +k); //running necessary code, printing loop number`
`k++; //adding counter's increment`
`}`



## For Loops
