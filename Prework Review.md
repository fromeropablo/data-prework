# Charlotte Stiller

Hello Charlotte! You have finished the Prework, congrats! That's your first step here, you finished this task incredibly well, congrats! 

If you have any doubt here, don't hesitate to ask me about.

## 1. Snail and the well

You did a good work here, it seems that you understood how to work with `while` loops in general!

Remember to show the output of every cell of your code. It's really important for us to take a look at your results. 

In the main question you almost got it! You just had to remove the substraction of the `nightly_distance` variable from the first part of the while loop and substract it inside the if condition. Take in count that if the snail gets out of the well by day, you can't substract the distance slided by night. It would be something like this:
```python 
while snail_position < well_height:
    days_that_pass += 1
    snail_position += daily_distance
    if snail_position > well_height:
        snail_position -= nightly_distance
```

You did it great in the bonus, congrats! The structure of your code is really good but you can remove the last `if` condition and name the variable `snail_in_well` in your first conditional properly.

Try it and if you have any doubt, ask me!

Good work at the end of the assignment, it's perfect!

## 2. Duel of sorcerers

In this assignment you had to understand how to work with `for` loops and `if` conditions. Well done here!

In question #3, it gives you an error because you are trying to append an integer. It is not posible, instead, you have to sum one to the variable. 

It would be something like this:
```python
count= 0

for i in gandalf:
    count += 1
    if saruman[count] > gandalf[count]:
        saruman_wins += 1
    else:
        gandalf_wins += 1

print('Out of', spells, 'clashes')
print('Gandalf wins', gandalf_wins, 'clashes')
print('Saruman wins', saruman_wins, 'clashes')
```

Great work in the bonus! You solved the tasks with an excellent structure of code, just remember to restart your variable count to 0, so the code will work!

Really cool that you used the `statistics` library in the last question, congrats!

## 3. Bus

Excellent work here! You have sent a really good solution for this task.

## 4. Robin Hood

Another brilliant exercise, and it was a tough one! You have shown how to work with points of coordinates, which will be very useful in the future. 

Also, you defined a function as the hint explained to get your variable distance. Good work in this task, it's really good too. 

## 5. Temperature

Good job! In this exercise you had to deal with operators and the logic behind them and you solve the questions without any problem, great!

Be careful using a temporary variable like `i` in a different place outside the `for` loop. 

You have used the `round` function, that's perfect. If you want to learn more about it, hope it helps:
https://www.geeksforgeeks.org/round-function-python/#:~:text=Python%20provides%20an%20inbuilt%20function,number%20to%20the%20nearest%20integer.

## 6. Rock, paper, scissors

Amazing work here! Also in the bonus, your answers are perfect!

Just be careful closing the while loops and for loops with `:` and with the indentation levels inside the loops. 

Overall, it was a great exercise here!


