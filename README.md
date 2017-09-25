# Chapter 1 Textbook Exercises

## Set A
* The book does not go over **assignment** before this problem set, but you should use it here anyway.  Assignment means using equal signs.  Here is a really straightforward way to calculate the number of seconds in a year and display it to the screen:
```Python
years = 1
days = years*365
hours = days*24
minutes = hours*60
seconds = minutes*60
print(seconds)
```
If you want to be a little more fancy, try
```Python
print('There are', seconds, 'seconds in', years, 'years.')
```
If you don't like that grammar, try changing the number of years and see what happens.  Try checking your answers
[here](https://www.wolframalpha.com/input/?i=seconds+in+a+year).

## Set B
* Python sees a difference between an [integer](http://en.wikipedia.org/wiki/Integer) and a [rational](http://en.wikipedia.org/wiki/Rational_number) number.  When you do division of integers you will notice that a lot of rounding happened.  Use [floating point](https://www.google.com/search?q=python+float) math when you need to avoid this kind of rounding.
* Don't know what a **factorial** is?  [Find out](https://www.google.com/search?q=factorial)!
* On most calculators and computers, 2 to the power of 5 is expressed as 2^5.  *Not in Python!*
* *rate=distance/time* and therefore, _distance=rate*time_.  What does *time* equal in terms of rate and distance?

## Set C
* Use `turtle.exitonclick()` to at the end of your `turtle` programs to keep the canvas open.  When you click on it, your program will finish.

## Set D
* Many problems will ask you to *"modify the function __"*.  If you are editing these functions in the same file, you should not have the same name for two different functions.  When you modify functions, **give the new function a unique name**.
