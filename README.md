# Quiz 4-7 Corrections


## Quiz 4

### Question 2
I got this question wrong because I didn't know default values can be included in prompt statements. The question asked to prompt the user to ask to enter the number of hours the user they work in a week, to set a default value to be pre-populated with the value 40, and to store the user's response in a variable named `hours`. The correct answer was a prompt with the specifics of the questions and saved under the `hours` variable. It also puts the default value of 40 after the written prompt, which I didn't know could be done.  

### Question 7
I got points off of this question because it asked to select all that apply and I missed a few correct answers and chose a few incorrect answers. Therefore the question asked to choose all the following valid data types in Javascript and I chose `boolean`, `object`, `integer`, `number`, `string`, `character`, and `symbol`, but only 5 out these 7 were correct. Two of which I chose, `integer` and `character`, were incorrect and instead I should've chosen `undefined` and `null`. 

### Question 9
For this question, I didn't get anything wrong, but I still got points off because it was a select all that apply question and I missed two correct answers. The question asked to select the following values that are always considered falsey and I chose `null`, `undefined`, `false`, and `NaN`. The correct answers I missed were `""` and `0`. 

### Question 10
This question asked to declare and initialize a variable called `x` with the value 27. I got this question wrong because I didn't know the difference between declaring and initializing so I selected the answer that only initializes the variable with the correct value, but doesn't declare it. The correct answer is the following:
```
let x;
x = 27;
```

### Question 11
This was a programming question for which I lost only a few points, but I could not open the file on my chromebook, so I don't know what were my mistakes. I'm sure my mistakes were minor and related to the execution of the code. 


## Quiz 5

### Question 2
This was another multiple-select question where I missed correct answers and chose an incorrect one. This question asked for valid relational operators in Javascript and I chose `<=`, `>`, `>=`, `=`, and `<`. Four out of these five were correct and I missed four correct answers. Thus, I incorrectly picked `=`, when instead I should've picked `!==`, `!=`, `==`, and `===`. 

### Question 4
This was another multiple-select question and for this one, I did not miss any, I just selected a lot incorrectly. I confused relational and logical operators. The wrong answers I selected were `!=`, `!==`, `===`, `?`, and `==` and are also relational operators. The correct answers I selected were `&&`, `!`, and `||` and are also logical operators. 

### Question 5
This question asked to satisfy the above statements with two missing operators. I got this question wrong simply because I chose the answer that had `&&` and `&&`. I should've chosen the answer that had `&&` and `||`. 

### Question 7
This was another multiple-select question and it asked to choose the following valid syntax for an `if` statement in Javascript. For this question, I picked two answers correctly and one incorrectly. 

### Question 11
I got this question wrong because I mixed up the four components of a `for` loop. The answer I chose had the steps in order of: setup, expression, update, loop body, and repeat. The correct answer had the steps in order of: setup, expression, loop body, update, and return to step 2. 

### Question 12
I got this question wrong because I did not clearly know the primary difference between a `while` loop and a `do...while` loop. The correct answer was: A `while` loop check its condition before running the loop body, whereas a `do...while` loop checks its condition after running the loops body. 

### Question 13
This question stated: Anything written in the form a `while`(or `do...while`) loop can be achieved with an equivalent `for` loop and vice-a-versa. I got this question wrong simply because I picked false instead of true. 

### Question 14
This was another multiple-select question and here I chose two answers, one correct and one incorrect. The questions asked which of the following represents a valid `for` loop that will execute at least once and will terminate. Even though it was a multiple-select question, there was only one correct answer which was the following piece of code:
```
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

### Question 15
The question asked which of the following code segments represents a valid `while` loop that will run at least once and will terminate. I got this question wrong because the answer I chose increases in its loop while the correct answer decreases in its loop. The correct answer was the following code:
```
while (x > 100) {
    x--;
}
```


## Quiz 6

### Question 3
This question asked which of the following can you determine based on the information provided. This was a multiple-select question and here I chose one correct answer, missed another correct answer, and chose two incorrect answers. The two correct answers were: the function is not designed to accept any parameters and the name of the function is `mystery`. 

### Question 5
I got this question wrong because I chose the wrong revision for the function provided so that it accepts as parameters the values being divided. The correct revision was as follows:
```
function divide (a, b) {
    return a / b;
}
```

### Question 8
This was another multiple-select question and here I chose two correct answers and missed one. The question asked which of the following could be a possible declaration and implementation of the `multiply` function. All the correct answers multiply 3 values and return them, and the one I missed does the same thing but one variable at a time. 

### Question 9
This was a multiple-select question which asked which of the following built-in functions accept parameters. I chose two correct answers and lost points for missing another. All together, the correct answers to this question were `alert`, `prompt`, and `console.log`. 

### Question 10
This was another multiple-select question and it asked which of the following is the correct way to print the result of calling `subtract` to the console. I chose two correct answers and one incorrect answer. The correct answers had to have the `substract` variable name, x, y, and console.log.

### Question 14
I got this question wrong because I didn't know what would be the result of the code snippet provided:
```
function example(a, b, c) {
    if (a === 1) {
        if (b === 2) {
            if (c === 3) {
                var d = 4;
            }
        }
    }
    
    console.log(d);
}
```
The answer I chose was that a ReferenceError will occur and the correct answer was `4` or `undefined` will be printed to the console. 

### Question 15
I got this question wrong because I didn't know what would be the result of the code snippet provided:
```
function example() {        // line 1
    let x = 1;              // line 2
                            // line 3
    if (x === 1) {          // line 4
        var y = 2;          // line 5
                            // line 6
        console.log(x)      // line 7
    }                       // line 8
                            // line 9
    console.log(y);         // line 10
}                           // line 11
```
The answer I chose was that a ReferenceError will occur on line 10 and the correct answer was `1` or `2` will be printed to the console. 


## Quiz 7

### Question 3
I got this question wrong because I did not understand the behavior and functionality of the `mystery` function provided. The answer I chose states that it returns `true` if some array, `a`, contains at least one instance of some value, `b`; otherwise, returns `false`. The correct answer states that it returns the index at which some value, `b`, is found in some array, `a`; otherwise, returns -1 if `b` is not found in `a`.

### Question 5
This was a multiple-select question that asked which `if` statements would print the provided statement. I lost points on this question because I chose three correct answers and one incorrect answer. I didn't realize that each of the correct answers use a built-in method, either `indexOf`, `includes`, or `lastIndexOf`. 

### Question 6
This was a multiple-select question which asked which of the following implementations would accept an array of elements and print each one to the screen one-by-one. I chose one correct answer, two incorrect answers, and missed one correct answer. I didn't understand the `for` loop for this implementation. 

### Question 9
This question asked which of the following sets of test data demonstates that `getLargest` does not work as intended. I chose the array filled with only zeros because it makes sense they are all the same value. The correct answer was `[ -9, -1, -8, -2, -7, -3, -6, -4, -5 ]` and I think it was because they were all negative numbers.

### Question 12 
The question asked what would be the value of `tripleDigits` after executing this provided code. I got this question wrong simply because I chose false instead of true because I thought since `4444` was included in the array and it didn't satisy the return parameters, the answer had to be false. 

### Question 14
I got this question wrong because I missed two correct answers, but chose one correct. The question provides the following code:
```
let a = [];
let b = [ 1, 2, 3 ];
let c = [ "a", "b", "c" ];
```
It asked which of the following represent the contents of each of these arrays, I chose `a, b, c`, and missed an empty array and `1, 2, 3` because I second guessed myself after choosing them so I unchose those answers. 
