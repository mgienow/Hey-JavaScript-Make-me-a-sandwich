# Hey JavaScript - Make me a sandwich!

> A program, often referred to as source code or just code, is a set of special instructions to tell the computer what tasks to perform.
          *-- Kyle Simpson, YDKJS *

Writing JavaScript code is not much different from making a sandwich.

Really!

You've made sandwiches before, right? Now imagine explaining how to make a sandwich to someone who has not ever done it before. (Also, they are not terribly bright, so you have to be very, very specific with your instructions). You break it down step by step, each next step building on the one before. "First you get out the bread. Then put two slices of bread on a plate. Now spread mustard on one of the slices of bread."

Easy, right? Well, the process for putting together a useful hunk of JavaScript to do cool things in the browser works pretty much the same way.

###  Let's Start With Functions

> A function is typically a named section of code that can be "called" by name, and the code inside it will run each time.
   *Kyle Simpson, YDKJS*

- A JavaScript `function` is a block of **reuseable** code

- A  function stores the specific steps for performing an assigned task. This means that, instead of having to type out instructions over and over every time you want your program to do a particular thing, you can simply point it toward your handy-dandy function

- Functions save time (and typing!), help organize code to make things more readable, and reduce repetition.

----------------------------------------
###  Functions are like recipes

A cooking recipe is a list of instructions for how to prepare a specific dish. Functions do pretty much the same thing for creating a JavaScript program.

JavaScript wants to be helpful and do whatever it is you are asking it to do. To be successful, the instructions you give need to be broken down into *single separate steps* in the *logical order* they need to be done.

Let's apply this to making a sandwich. You can't just give a general direction like, "Hey JavaScript, make me a sandwich!"  Beyond telling JavaScript **what** to do, you also need to specify exactly **how** to do it.

   1. Get a plate.
   2. Lay a slice of bread on the plate.
   3. Spread mayo on the bread.
   4. Put turkey on top of the mayo.
   5. Put another slice of bread on top of the turkey.

Every time you are hungry for a tasty sandwich snack, though, you would need to tell JavaScript *again* how to make the same exact sandwich.

**But**: if you write a function that contains all the steps for making your favorite sandwich, every time you want a snack, you can just tell JavaScript to use the sandwich function!

______________________________________
### Writing a function

```JavaScript
function makeSandwich() {
      //sandwich making steps here
}
```

- In JavaScript, functions always contain the `function` keyword.

- This is often followed by the name of the function - a short, descriptive identifier that says what the function does. In this case, make a sandwich.

(Fun fact: When a name contains more than one word, JS uses _camel case_ syntax for naming things -- functions, variables, etc. This means the first word is lower case, and each word after that has its first letter capitalized. Kind of like humps on a camel: camelCase. makeMeASandwichPlease. You get the idea. :camel: :camel: :camel:)

- The function's name is followed by parentheses () -- we will get to why in a minute -- and then two curly brackets {}.

- Between the curly brackets is where the magic happens: that is where you write the code, your set of instructions for what you want JavaScript to do.
