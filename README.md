# Exercise - Guess the number

Implement a program in Python which guesses a random number that the computer has chosen.

**Notes: In order for the tests to pass you will have to follow the guidelines below:**

- Use the string `"Guess a number between " + str(lower) + " and " + str(upper) + ": "` when outputting the user's guess.
- Print the string `You got it right!` when the answer is right.
- Print the string `Too high!` when the guess is too high.
- Print the string `Too low!` when the guess is too low.

You might find the following helpful:

```plaintext
computer chooses random number between 1 and 10

loop until we get it right
    computer asks us to guess

    if the guess is right
        computer says yes
    otherwise
        if the number is too low
            computer says higher
        if the number is too high
            computer says lower
```
