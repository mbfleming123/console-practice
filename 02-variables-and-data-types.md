# 02 Variables & Data Types

Open your JavaScript Console in Google Chrome and enter the following examples. If your console becomes too cluttered with commands or errors, remember you can type `clear()` for a fresh start.

Type in the command as it is next to the number, then go through the modifications below.

You may want to write down your findings during this exploration for future reference.

If a solution or answer to a question eludes you, ask!

---

1. `var cats = 2;`

   Then type `cats;`. We have declared a variable (a container for a value), then called that variable.

   Type `cats = 3;`. Then type `cats`.

   Type `cats = "Flynn and Quorra";`. Then type `cats` again.

   Type `cats = true;`. Then type `cats` again.

   Type `var dogs = cats;` Type `dogs`. Then type `cats` again.

   What does this tell you about variables?

2. What is it?

   Most of these you *should* know, but let's get into the habit of becoming familiar with `typeof` as tool you'll feel comfortable going to in the future.

   `typeof 3`

   `typeof "Hello!"`

   `typeof true`

   `typeof 102`

   `typeof false`

   `typeof (2017 + "Miami Hurricanes")`

3. Basic math

   Construct a statement using each of the basic arithmetic operators (addition, subtraction, multiplication, modulo). It's just like using a calculator. :)

4. Order of operation

   Evaluate the following in the console:

   `0 - (-15)`

   `8 - (-3) * (-2 - 6)`

   `(35 * 15 + 8) - 20 - 48`

   (Yeah, yeah. Enough math. For now.)

5. Count up

   We haven't learned about loops yet, but let's use our knowledge to make one work.

   Enter the following code into the console. Remember to hit 'shift-return' to move on to the next line without executing the code. Add the increment operator to `i`.

   ```javascript
   var i = 1;
   while (i < 10) {
      console.log(i);
      i  // add the operator to this i!
   }
   ```

   Now, change the operator on `i` to an 'add and assign' operator so the count increases by two (2) each time.

6. Count down

   Let's make our loop count down.

   Enter the following code into the console. Remember to hit 'shift-return' to move on to the next line without executing the code. Add the decrement operator to `i`.

   ```javascript
   var i = 10;
   while (i > 0) {
      console.log(i);
      i    // add the operator to this i!
   }
   ```

   Now, change the operator on `i` to a 'subtract and assign' operator so the count decreases by three (3) each time.

7. Take your pick

   Try each example of the ways one can 'calculate and assign' (use 'multiplication and assign').

   ```javascript
   var i = 4;
   i = i * 2;

   var j = 4;
   j *= 2;
   ```
   Which do you find more comfortable?

8. True or False, Part I

   Sadly, truth tables are one of those things you've just got to memorize. Before entering each of the following, write down what you believe the console will return: true or false.

   `true && false`

   `true || false`

   `true && true`

   `false || true`

   `!false`

   Got 'em all right?  You should still keep studying! :)

9. True or False, Part II

   Now we're mixing up all kinds of data types to determine whether our statements are true or false. Again, before entering each of the following, write down what you believe the console will return: true or false.

   `(1 < 2) && (3 == 3)`

   `("Hello" !== "World") || false`

   `!(2 > 4)`

10. Say Hello!

   Using what you know thus far, ask a user for his/her name, then use the input to say "Hello, <name>!".

   (Hint: Use the window methods to gather the input. Print messages to the console.)

   **Example Output:**
   What is your name? (Flynn)
   Hello, Flynn!

11. Letter count

  Ask a user for a phrase, then use the input to tell the user how many characters are in the phrase. Include the input in the output string.

  **Example Output:**
  What would you like to say? (Hello, world!)
  "Hello, world!" has 13 characters.

  Can you find a way to include the user's phrase in the output? (We have not covered this yet, but may have by the time you work through the exercise!)

12. More Math! Yargh!

  Ask a user for two numbers (using separate prompts). Then use the input to display the result for addition, subtraction, multiplication, division and modulo.

  **Example Output:**
  Enter a number: (100)
  Enter another number: (10)
  100 + 10 = 110
  100 - 10 = 90
  100 * 10 = 1000
  100 / 10 = 10
  100 % 10 = 0

  We haven't reached this step yet, but think of how you might approach bad input. What if someone gave you a letter instead of a number? Or an empty response? How might you respond to the user?

  Write out your plan in plain English. We'll get to the code implementation soon enough!
