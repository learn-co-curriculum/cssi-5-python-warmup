# Python Day 5 Warm-up!

## Instructions:
Fork and clone this lab, then complete the drills below.

### 1. Nested for-loops and user input

Create a new python file called `warmup1.py` and complete the following:

1. Write a function called `Yes` that takes an int parameter `excitement_level`. This should print out "Yes!" `excitement_level` times. For example, `Yes(10)` should print out "Yes!" ten times.
2. Write a function called `No` that takes an int parameter `disappointment_level`. This should print out "No" with the number of "o"s equal to `disappointment_level`. For example, `No(10)` should print out "Noooooooooo".
3. 

2. Modify your code above so that it does the following:
  * Keep asking "Enter a command:" repeatedly after the user enters a command the first time
  * Stop prompting for input (i.e. break out of the loop) only after the user inputs "please" three times in a row. This should be case-insensitive.

### 2. Nested for loops

Create a new python file called `warmup2.py` and complete the following:

1. 


### 1. Loops and Lists Drills

1. Given the following list:
  
  `daily_temperatures = [83, 86, 85, 88, 86, 87, 92, 93]`

  Write a loop that prints each item in the list.
2. Write a function called `PrintTemperatures` that takes a list parameter called `daily_temperatures` and prints each item in the list.
3. Write a function called `AverageTemperature` that takes a list parameter called `daily_temperatures` and returns the average temperature in the list.
4. Write a functions called `CountHotDays` that takes a list parameter called `daily_temperatures` and returns the number of temperatures that are above 90.
5. Write a functions called `ModeTemperature` that takes a list parameter called `daily_temperatures` and returns the most common temperature in the list. If there is more than one mode, return the first mode found.
6. Write a function called `MedianTemperature` that takes a list parameter called `daily_temperatures` and returns the median element of the list.
7. Write a function called `Deltas` that takes a list parameter called `daily_temperatures` and returns a list of the differences between each temperature. For example, `Deltas([73, 75, 70])` should return `[2, -5]`. 

### 2. Loops and Dictionaries Drills

Given the following dictionary:
  ```python
  abc_name_to_age = {
    'aaron' : 30,
    'betty' : 14,
    'cindy' : 67,
    'duane' : 18,
    'edgar' : 17,
    'frank' : 65
  }
  ```
1. Write a loop that prints out all the names in the `name_to_age` dictionary.
2. Write a loop that prints out each person's name along with their age in the form of "(name) is (food)", e.g. "aaron is 30"
3. Write a function called `AverageAge` that takes a dictionary parameter called `name_to_age` and returns the average age in the list.
4. Write a function called `CountRetired` that takes a dictionary parameter called `name_to_age` and returns the number of people whose age is above 64.
5. Write a function called `Minors` that takes a dictionary parameter called `name_to_age` and returns a list of the names of the people under 18 years old.

Given the following dictionary:

  ```python
  our_favorite_foods = {
    'victoria' : 'pizza',
    'tim' : 'sushi',
    'cookie monster' : 'cookies',
    'pooh' : 'honey',
    'jiro' : 'sushi',
    'michelangelo' : 'pizza',
    'caesar' : 'pizza',
    'wimpy' : 'hamburger',
    'joseph' : 'frosting'
  }
  ```
1. Write a loop that prints out each person's name along with their favorite food in the form of "(name) loves (food)", e.g. "victoria loves pizza"
2. Write a loop that prints out each person's name along with their favorite food in the form of "(name) Loves (food)", with each word capitalized, e.g. "Victoria Loves Pizza" and "Cookie Monster Loves Cookies".
2. Write a function called `GetUniqueFavorites` that takes a dictionary parameter called `name_to_favorite_food` and returns a list of all the unique favorite foods.
3. **Extra Credit** Write a function called `PopularFood` that takes a dictionary parameter called `name_to_favorite_food` and returns the most frequent favorite food in the list. If there is a tie, return the first in alphabetical order. For example, `PopularFood(favorite_foods)` should return "pizza".
