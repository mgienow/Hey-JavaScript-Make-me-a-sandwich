# Hey JavaScript - Make me a sandwich!

> A program, often referred to as source code or just code, is a set of special instructions to tell the computer what tasks to perform.
          *Kyle Simpson, YDKJS*

Writing JavaScript code is not much different from making a sandwich.

Really!

You've made sandwiches, right? Now imagine explaining how to make a sandwich to someone who has not ever done it before. (Also, they are not terribly bright, so you have to be very, very specific with your instructions). You break it down to extremely basic steps, each next step building on the one before. "First you get out the bread. Then get out a plate. Put two slices of bread on the plate. Now get out a knife. Use the knife to spread some mayo on one of the slices of bread..."

Easy, right? Well, the process for putting together a useful hunk of JavaScript to do cool things in the browser works pretty much the same way.

###  Let's Start With Functions

> A function is typically a named section of code that can be "called" by name, and the code inside it will run each time.
   *Kyle Simpson, YDKJS*

- A JavaScript `function` is a block of **reuseable** code

- A  function stores the specific steps for performing an assigned task. This means that, instead of having to type out instructions over and over every time you want your program to do a particular thing, you can simply point it toward your handy-dandy function

- Functions save time (and typing!), help organize code to make things more readable, and reduce repetition.

----------------------------------------
## Functions are like recipes

A cooking recipe is a list of instructions for how to prepare a specific dish. Functions do pretty much the same thing for creating a JavaScript program.

JavaScript wants to be helpful and do whatever it is you are asking it to do. To be successful, the instructions you give need to be broken down into *single separate steps* in the *logical order* they need to be executed.

Let's got back to making a sandwich. You can't just give a general direction like, "Hey JavaScript, make me a sandwich!"  Beyond telling JavaScript **what** to do, you also need to specify exactly **how** to do it.

   1. Get a plate.
   2. Lay a slice of bread on the plate.
   3. Spread mayo on the bread.
   4. Put turkey on top of the mayo.
   5. Put another slice of bread on top of the turkey.

Every time you are hungry for a tasty sandwich snack, though, you would need to tell JavaScript *again* how to make the same exact sandwich. Kind of tedious.

**But**: if you write a function that contains all the steps for making your favorite sandwich, every time you want a snack, you can just tell JavaScript *"Use the sandwich function!"*

______________________________________
## Writing a function

```JavaScript
function makeSandwich() {
      //sandwich making steps here
}
```

- In JavaScript, functions always contain the `function` keyword.

- This is often followed by the name of the function - a short, descriptive identifier that says what the function does. In this case, make a sandwich: makeSandwich()

- The function's name is followed by a pair of parentheses () -- we will get to why in a minute -- and then two curly brackets {}.

- Between the open curly bracket { and the closing curly bracket } is where the magic happens: that is where you write the code, your set of instructions for what you want JavaScript to do.

(Fun fact: When a name contains more than one word, JS uses _camel case_ syntax for naming things -- functions, variables, etc. This means the first word is lower case, and each word after that has its first letter capitalized. Kind of like humps on a camel: camelCase. makeMeASandwichPlease. You get the idea. :camel: :camel: :camel:)

-------------------------------------------
## Invoking, Calling, Executing or Running A Function (i.e., making a function do something useful)

There are two parts to how functions, well, function:

First is the `function declaration` -- where you define the function and whatever it is you want it to do.

Second is the `function invocation` -- where you tell it to now actually Do The Thing. This is where the parentheses come in: makeSandwich(). The point in your code where you call a function is known as the `call site`.

Both parts are necessary, but they don't have to actually be kept together inside your JavaScript code. (In fact, you can actually invoke a function BEFORE you even declare it, due to the magic of something known as `hoisting`, but don't worry about that right now).

------------------------------------
##Enter the console

Let's try it: pop open the developer tools in your browser. `Command + Option + J` for Mac (or `Ctrl + SHift + J` for that other one). This opens the _console_ pane directly - just as the dev tools _elements_ tab is where a page's HTML and CSS reside, console is where you can inspect a page's JS code.

You can also use the console to write, run and test your own JavaScript!

- To give yourself a nice blank slate in this JS playground, it can be good to start by typing `about:blank` in the browser bar. This brings up a completely empty browser window, so there is no competing JS code from somebody else's web page. It's all you!

- The little :no_entry_sign: symbol at the far left of the toolbar is the `clear console` button -- if your console window is getting filled up, or you just want some whitespace, hit that to clear the deck.

- You can also use the up arrows to autocomplete recent code entries. This recall utility is really handy because it can range from bringing back a simple one-line function invocation like `makeSandwich()` to a lengthy multi-line code block. Saves mucho typing!    
