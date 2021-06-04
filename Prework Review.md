# Elissa de Jong
Hello Elissa! You have finished your Prework in a very very good way, congrats! Hope to see you making these kind of efforts during the following weeks. 


Ready to see the corrections of your Prework? Here we go!

## 1. Snail and the well

The main exercise is really good, it seems that you have understood the logic behind `for` loops and `while` loops.
The structure is almost perfect. If you check your work, you will see that you add the variable 'day' in both parts of the `if` condition. It can be written inside the while loop, so then you can remove the `else` statement. 

Then, the solution would be something like this: 
``` python 
while snail_position <= well_height:
    days += 1
    snail_position += daily_distance
    if snail_position <= well_height:
        snail_position -= nightly_distance 
```

### 1.1 Bonus!

Nothing else to say in the first exercise, because the structure is similar to the one before. Well done!

For the following questions take in count that you can replace the number of days advanced (5 in this case) by your variable `days_advanced` which is already equal to this number. The question #2 is perfect!

In the last two exercises you did a great effort calculating the mean and the standard deviation manually. Congratulations, that kind of efforts will help you a lot during these weeks!

Some tips to improve your code and save time:

3. You have already assigned a variable to the total distance risen by the snail, which is `snail_position`, so you don't need to operate again. 
4. Great job here! You did every step perfectly and you used the math library. In fact, in libraries such as `math` or `statistics` you can calculate directly both the mean and the standard deviation. 

## 2. Duel of sorcerers

Wow! You used the `zip` function, excellent! The first exercise is perfect, nothing to say here!

### 2.1 Bonus!

Here you worked great one more time. I found some tips that will improve your code here:
   1. When the battle results in a tie you don't need to sum a win to the sorcerers. You just have to keep the counts of wins as before that battle.
   2. In the key loop, you can order the lines of code reallocating the last if, elif conditions to its respective sorcerers. It will be something like this: 
``` python 
for g, s in zip(gandalf_power, saruman_power):
    if g > s:
        gandalf_wins += 1
        saruman_wins *= 0
        if gandalf_wins == 3:
            print("Gandalf wins the battle by being the first to win ",
            gandalf_wins, "spell clashes in a row")
    elif s > g:
        gandalf_wins *= 0
        saruman_wins += 1
        if saruman_wins == 3:
            print("Saruman wins the battle by being the first to win ",
            sarumam_wins, "spell clashes in a row")
```
## 3. Bus

Good answers here. Just an advice related to the float values. If it is not specified or not needed, you can round a decimal number with the `round` method. Here an example where the variance is rounded to two decimals:

``` python 
round(variance, 2)
```

## 4. Robin Hood

Your code here is excellent again! Well done comparing the unique values with the complete list, but be careful with it because in the future you will have to deal with thousands or millions values. 

It seems that you have understood perfectly how tuples, lists and points of coordinates work. 

## 5. Temperature

In this assignment you had to deal with operators and you did it pretty good.
In the last exercise before the bonus, you can optimize your code grouping every condition in one line with the `or` operator:
``` python
need_to_change = len(seventies_temp) > 4 or max_temp > 80 or avg_temp > 65
```

Great work in the bonus part!

## 6. Rock, paper, scissors

Wow! It seems that you worked a lot here! 

To define a function is as easy as this: 
``` python 
def cpu_gesture(gestures):
    return random.choice(gestures)
```
Then you just have to call the function, but don't worry you will see it i the next classes. 

About your question of invalid entries, you have to name the variable choice in and out the while loop to avoid this problem. 

In the following questions until the end of the lab you have shown a lot of work behind your code, writing each possible combination in the main exercise and also in the bonus. 

Defining functions is the best way to save time and optimize our code when we have to write the same line (or similar) multiple times. With them, you just have to "ask the user" which parameters or arguments want to use when calling the function every time. 

Abhi will explain to you how to work with functions but in the meanwhile you can read basic info about them here: 
https://www.w3schools.com/python/python_functions.asp


Overall, you have done a great great work and you have shown tones of efforts. Congrats!!!
