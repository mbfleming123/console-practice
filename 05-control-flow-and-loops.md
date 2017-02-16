# 05 Control Flow and Loops

The following exercises will require you to enter code into a file which is included in an html file. (You *could* type all this into the console, but it will probably be very frustrating).

Files have been prepared for you in the [practice-template](https://github.com/umiami-js/practice-template) repo. You may want to fork this to your own GitHub account for future use. Also, you may want to make copies of `index.html` and `script.js`, renaming them to reflect the script you are working on at any given time. (For instance, if you are working on a script about cars, you might rename the files `cars.html` and `cars.js`.)

As you work through the exercises, write down your findings during this exploration for future reference.

If a solution or answer to a question eludes you, ask!

---

## Control Flow

1. `if-else`

  Use the `confirm` method to ask a user to click okay or cancel. ('Okay' returns `true`; 'Cancel' returns false.) Use an if-else statement to print different messages to the console based on what value is returned.

2. Multiple `if-else`

  Use the `prompt` method to ask a user to choose between two items (i.e. Cats or Dogs? Chocolate or Vanilla?) Return a unique message for each answer as well as a message if the user enters neither.

3. `switch-case`

  Use the `prompt` method to ask a user to enter their favorite ... something (i.e. movie genre, music genre, candy, etc.). Write a `switch-case` statement which includes *at least* five options which print unique messages. Be sure to include a default in case your user does not enter any of the choices you are accounting for.


## Loops

1. `for`

  Write a `for` loop which prints the values 1-10 to the console.

2. `while`

  Write a `while` loop which prints the values 10-1 to the console.

3. `do-while`

  Write the same loop in step 2, but with a `do-while` loop.

  After you get the loop to run, modify it so it only runs once.

4. Iterating over an array

  Iterate over the following array so each item is printed to the console.

  `var array = ["Flynn", "Quorra", "Coby", "Charlie"];`

5. Iterate over an object

  Iterate over the following object, constructing a sentence similar to the output (a string) provided.

  ```javascript
  var car = {
    year: 2016,
    make: "Chevrolet",
    model: "Camaro"
  }
  ```

  Output: "2016 Chevrolet Camaro"
