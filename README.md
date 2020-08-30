# Sprint Challenge: Algorithms

In this week's Sprint you explored and implemented some classic algorithmic approaches and used them to solve novel problems. You also implemented some classic and fundamental sorting algorithms and learned how to go about evaluating their respective runtimes and performance. This Sprint Challenge aims to assess your comfort with these topics through exercises that build on the algorithmic intuition you've started to build up.

## Instructions

This is an individual assessment. All work must be your own. 
Your Challenge score is a measure of your ability to work independently using the material covered throughout this sprint. 
You need to demonstrate proficiency in thebconcepts and objectives that were introduced and that you practiced in the preceding days.
You are not allowed to collaborate during the Sprint Challenge.

#### 1. Analyzing runtime

Given 3 blocks of code, identify the runtime of each. Justify your answer.

#### 2. Find the highest floor

Suppose that you have an n-story building and plenty of eggs. 
Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. 
Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.
Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

#### Use recursion to complete the `count_th()` function 
Inside the `recursive_count_th` directory you'll find the `count_th.py` file. In this file, please add your recursive implementation to the `count_th()` method following these rules:

* Your function should take in a signle parameter (a string `word`)
* Your function should return a count of how many occurences of ***"th"*** occur within `word`. Case matters.
* Your function must utilize recursion. 
  * It cannot contain any loops.

Run `python test_count_th.py` to run the tests for your `count_th()` function to ensure that your implementation is correct.

##### Complete robot_sort with existing functions

Inside the `robot_sort` directory you'll find the `robot_sort.py` file. Open it up and read through each of the robot's abilities. Once you've understood those, start filling out the `sort()` method following these rules:

  * You may use any pre-defined robot methods.
  * You may NOT modify any pre-defined robot methods.
  * You may use logical operators. (`if`, `and`, `or`, `not`, etc.)
  * You may use comparison operators. (`>`, `>=`, `<`, `<=`, `==`, `is`, etc.)
  * You may use iterators. (`while`, `for`, `break`, `continue`)
  * You may NOT store any variables. (`=`)
  * You may NOT access any instance variables directly. (`self._anything`)
  * You may NOT use any Python libraries or class methods. (`sorted()`, etc.)
  * You may define robot helper methods, as long as they follow all the rules.

### Stretch 
[x] Uncomment the `test_stretch_times()` test in `test_robot.py`. Can you optimize your robot sort to perform better than the given times?
