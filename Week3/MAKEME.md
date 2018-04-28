## Homework Week 3

```
Topics discussed in class this week:
• Git work flow
• Advanced data types [Objects]
• Conditions
• Statements vs Expressions
• Loops (for/while)
• Functions
```

>[Here](./../../../../JavaScript2/tree/master/Week1) you find the readings you have to complete before the first JavaScript2 lecture.

## Step 0: Feedback

_Deadline Monday_

Provide feedback to the homework of last week to one of your fellow students. You will be assigned to one of the assignments by the class lead of this week.

## Step 1: Recap/Read

- Have a look at [The Secret Life of JavaScript Primitives](https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/)

- Review the topics of last week:
    - [Variables](./../../../../fundamentals/blob/master/fundamentals/variables.md)
    - [Values](./../../../../fundamentals/blob/master/fundamentals/values.md)
    - [Operators](./../../../../fundamentals/blob/master/fundamentals/operators.md)
    - [Naming conventions](./../../../../fundamentals/blob/master/fundamentals/naming_conventions.md)

- Go through the topics of this week:
    - [Git work flow](https://github.com/HackYourFuture/Git/blob/master/Lecture-3.md)
    - [Advanced data types (Objects)](./../../../../fundamentals/blob/master/fundamentals/objects.md)
    - [Conditional execution](./../../../../fundamentals/blob/master/fundamentals/conditional_execution.md)
    - [Statements vs Expressions](./../../../../fundamentals/blob/master/fundamentals/statements_expressions.md)
    - [Loops (for/while)](./../../../../fundamentals/blob/master/fundamentals/loops.md)
    - [Functions](./../../../../fundamentals/blob/master/fundamentals/functions.md)
    - [Scope](./../../../../fundamentals/blob/master/fundamentals/scope.md)

## Step 2: Watch

1. If you haven't done already, watch: [What is programming](https://www.khanacademy.org/computing/computer-programming/programming/intro-to-programming/v/programming-intro)
Just watch the 2 min video, you do not have to do the entire JavaScript course (It could be useful later on though).

2. Please watch the following parts of the course, [Programming Foundations Fundamentals](https://www.lynda.com/Programming-Foundations-tutorials/Welcome/83603/90426-4.html) on Lynda.com (if you don't have access to Lynda yet ask Gijs):
    <br>**4. Writing Conditional Code**
    <br>**5. Modular Code**
    <br>**6. Iteration: Writing Loops**
    <br>**7. More About Strings**
    <br>**8. Collections**
    <br>**11. When Things Go Wrong**

## Step 3: Rover the Robot

Go and try out this cool game: [roverjs.com](http://roverjs.com), written by one of our HYF teachers, Joost Lubach. There are different levels, see how far you can get!

## Step 4: String, Array and Loop challenges

_Deadline Wednesday_

> Create a `week3` folder in your repo `hyf-javascript1`. For each of the following exercises, create a new `.js` file in the `week3` folder with the file name as specified in parentheses in the exercise heading. Remember to start each file with `'use strict';`.

*IMPORTANT NOTE*
In each assignment write at least two `console.log` statements to verify if your code works correctly. In other words proof that you code works as expected. If you need inspiration look at the steps defined in the assignments from last week.

### Exercise 1 - Strings! (`strings.js`)

Consider the following string:

```js
let myString = "hello,this,is,a,difficult,to,read,sentence";
```

1\.1 Add the string to your file and log it.<br />
1\.2 Log the length of `myString`.<br />
1\.3 The commas make that the sentence is quite hard to read. Find a way to remove the commas from the string and replace them with spaces.<br />
1\.4 Log `myString` to see if you succeeded.<br />

### Exercise 2 - Arrays! (`arrays.js`)

Consider the following array:

```js
let favoriteAnimals = ['blowfish', 'capricorn', 'giraffe'];
```

**2.1** Add a statement that adds Mauro's favorite animal *'turtle'* to the existing array.<br />
**2.2** Log your new array!<br />
**2.3** Now add Jim's favorite animal to the array, it's *'meerkat'*, but make sure it will be placed after *'blowfish'* and before *'capricorn'*.<br />
**2.4** Write a `console.log` statement that explains in words _you think_ the new value of the array is.<br />
**2.5** Log your new array!<br />
**2.6** Log the length of the array, add a message: *'The array has a length of: '* (here you should show the length of the array).<br />
**2.7** Jason does not like *'giraffe'*, delete this animal from the array.<br />
**2.8** Again log your new array.<br />
**2.9** Now if unlike Jim, you don't like *'meerkat'* and you want to delete it from the array, but you don't know the position or the `index` of the item in the array, how can you find it?<br />
**2.10** Log the index of *'meerkat'*. Add a message so it says: *'The item you are looking for is at index: '* (here you should show the index of the item).<br />

### Exercise 3 - Maartje's work (`maartje.js`)

Below you see a very interesting small insight in Maartje's work (note: the durations are in minutes):

```js
const monday = [
  {
    name: 'Write a summary HTML/CSS',
    duration: 180
  },
  {
    name: 'Some web development',
    duration: 120
  },
  {
    name: 'Fix homework for class10',
    duration: 20
  },
  {
    name: 'Talk to a lot of people',
    duration: 200
  }
];

const tuesday = [
  {
    name: 'Keep writing summary',
    duration: 240
  },
  {
    name: 'Some more web development',
    duration: 180
  },
  {
    name: 'Staring out the window',
    duration: 10
  },
  {
    name: 'Talk to a lot of people',
    duration: 200
  },
  {
    name: 'Look at application assignments new students',
    duration: 40
  }
];

const tasks = monday.concat(tuesday);
```

Your assignment is to compute how much Maartje has earned by completing these tasks. For some unexplained reason, Maartje only gets paid for tasks that take two hours or more. We don't know what Maartje earns per hour (she won't tell us), so just make up a reasonable number yourself (by the way, she gets paid in Euros).

When you have computed Maartje's earnings, use a `console.log` statement to print the message (replace the amount by the result of your computation):

```
Maartje has earned €123.45
```

You need to do some research on how you can format a number so that it prints with two decimal places.

In addition to writing code, compute the expected result manually. Use a spreadsheet or pen and paper to compute Maartje's earnings and check it against the result from your code.

## More JavaScript :tada:

_Deadline Wednesday_

For each numbered assignment in this list create a separate file, for instance `1-more.js`, `2-more.js`, etc. in the `week3` folder. Remember to start each file with `'use strict';`.

**1.** Create a function that takes 3 arguments and returns the sum of the these arguments. Test your function by calling it with three numbers and using `console.log` to print the result. For example:

```js
// fill in the dots
function sum(...) {
    return ...;
}

const result = sum(...);
console.log(result);

// or, in a single line:
// console.log(sum(...));
```

**2.** Create a function named `colorCar` that receives a `color` argument. It should returns a string, for example`'a red car'` when called with `'red'` as argument. Test your function by calling it, passing a color name as a string and using `console.log` to print the result.

**3.** Create a function called `printObject` that takes an object as a parameter and prints out all of its properties and values.

Next, create an object that contains some properties with values. Now call your function and passing the object just created as an argument to test your function. Your function should not make any assumptions about the actual object passed. Instead, you should find a way to obtain the property keys and their values programmatically.

For example:

```js
function printObject(obj) {
  // Add your code here
}

const person = {
  firstName: 'Maartje',
  lastName: 'Kruijt',
  city: 'Amsterdam'
};

printObject(person);
```

Output:

```
firstName = Maartje
lastName = Kruijt
city = Amsterdam
```

**4.** Create a function named `vehicleType` that receives a `color`, and a `code`, 1 for 'car', 2 for 'motorbike'. Any code other than 1 or 2 should produce 'unknown vehicle'. Your function should return a string, for example `'a blue motorbike'` when called as `vehicleType('blue', 2)`. Try your function with different values for `color` and `code`. Use a `console.log` to print out each result.

**5.** Can you write the following without the `if` statement, but with just as a single line with `console.log(...);`?

```js
if (3 === 3) {
  console.log('yes');
} else {
  console.log('no');
}
```

>Note: If you see a warning from ESLint `Unexpected constant condition.` you can safely ignore it for this particular assignment. But otherwise you should always correct errors and warning flagged by ESLint.

**6.** Copy the `vehicleType` function from assignment **4**, but modify it so that it takes a third parameter called `age`, so that: 

```js
console.log(vehicleType('blue', 1, 5));
```
prints `'a blue used car'`.

Note: For this assignment, a car that is at most one year old is still considered `'new'`.

**7.** Make a array of vehicles, you can add `'car', 'motorbike'`, `'caravan'`, `'bike'`, or more.

Copy the `vehicleType` function from assignment **6** and modify it to use the array just created. When your function is called like this:

```js
console.log(vehicleType('green', 3, 1));
```

...it should print `'a green new caravan'`.

If `code` is something other than a number between 1 and the length of your vehicle array then the vehicle should be reported as `unknown vehicle`. (Try it!)

**8.** Create a function called `advertisement` that takes an array of vehicle names as an argument and returns a corresponding advertisement text string, for example:

```js
function advertisement(vehicleNames) {
  // Add your code here
}

const vehicles = [...];

const text = advertisement(vehicles);
console.log(text);
```

Example output:

```
Amazing Joe's Garage, we service cars, motorbikes, caravans and bikes.
```

Copy the array from assignment **7** and call the function you just created, passing the array as an argument. Use `console.log` to print the result.

> Hint, the output should be correct English with all the punctuation in place (that's the challenge). So plurals for the vehicle types, commas followed by a single space, the word and to replace the final comma and closed off by a period.

**9.** Copy the code from assignment **7** and add another vehicle to the array. Confirm that your advertisement function now includes the new vehicle in its advertisement text.

**10.** Create a single `.js` file containing the following:

- Declare a variable and initialize it with an empty object. (Just to show that you know what an empty object looks like.)
- Create an array of teachers that you have had so far for the different modules. Each element of the array should be an object that contain properties for the first name and the last name of the teacher.
- Add a property to the objects you just created that contains and array of languages that they have taught you.

**11.** Write some code to test two arrays for equality using `==` and `===`. Test the following:

```js
const x = [1, 2, 3];
const y = [1, 2, 3];
const z = y;
```
What do you think will be the result of `x == y`, `x === y` and `z === y` and `z === x`? Prove it!

> Don't cheat! Seriously - try it first.

Note: If you see an ESLint error `Expected '===' and instead saw '=='.` then you can ignore it for this assignment.

Check out the code below (no need to include this code in your homework file, just try and understand the code and play with it, e.g. make a change to one of the arrays or add a value):

```js
'use strict';

const array1 = [4, 8, 9, 10];
const array2 = [4, 8, 9, 10];

function equal(a, b) {
  let same = a.length === b.length;
  if (same) {
    const len = a.length;
    for (let i = 0; same && i < len; i++) {
      if (a[i] !== b[i]) {
        same = false;
      }
    }
  }

  return same;
}

console.log(equal(array1, array2));
```

More insights from this [Stack Overflow question](http://stackoverflow.com/questions/22395357/how-to-compare-two-arrays-are-equal-using-javascript).


**12.** Copy this code into and run it.

```js
'use strict';
const o1 = { foo: 'bar' };
const o2 = { foo: 'bar' };
const o3 = o2;

console.log('o1', o1, 'o2', o2, 'o3', o3);

o1.foo = 'baz';
console.log('o1', o1, 'o2', o2, 'o3', o3);

o2.foo = 'hyf';
console.log('o1', o1, 'o2', o2, 'o3', o3);
```

- Explain why making a change to `o1` does **_not_** affect `o3`.
- Explain why making a changes `o2` **_does_** affect `o3`.

Add your explanations in a JavaScript comment.

**13.** What will be the value of `result`? (And why?) Add your explanation in a JavaScript comment.

```js
const bar = 42;
const result = typeof typeof bar;
```

## Step 7: **Finish basic freeCodeCamp challenges:**

_Deadline Saturday_

Go back to FreeCodeCamp, start where you left of and finish the rest of the Basic JavaScript challenges.

Please make sure you REALLY understand the exercises below:
- https://www.freecodecamp.com/challenges/multiply-two-decimals-with-javascript
- https://www.freecodecamp.com/challenges/store-multiple-values-in-one-variable-using-javascript-arrays
- https://www.freecodecamp.com/challenges/build-javascript-objects
- https://www.freecodecamp.com/challenges/add-new-properties-to-a-javascript-object
- https://www.freecodecamp.com/challenges/delete-properties-from-a-javascript-object

## Step 8: Read before next lecture

_Deadline Sunday morning_

Go through the reading material in the [README.md](./../../../../JavaScript2/tree/master/Week1) to prepare for your next class

---

## How to hand in your homework:

Go over your homework one last time:

- Does every file run without errors and with the correct results when you run them with Node?
- Does every file start with `'use strict';`?
- Have you used `const` and `let` and avoided `var`?
- Do the variable, function and argument names you created follow the [Naming Conventions](../../fundamentals/blob/master/fundamentals/naming_conventions.md)?
- Is your code well-formatted (see [Code Formatting](../../fundamentals/blob/master/fundamentals/naming_conventions.md))?

If the answer is 'yes' to all preceding questions you are ready to:

```
git add .
git commit -m "added homework week 3"
git push
```

Finally, add a link to your repository folder in Trello.
