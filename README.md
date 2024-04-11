# Palindrome Lab


## Learning Goals


- Practice algorithmic problem solving


## Introduction


Now that we've discussed what an algorithm is and defined a problem-solving
approach, it's time to apply that to your first algorithm problem! Fork and
clone this lab, then **read the instructions before running any tests**.


## Instructions


Write a function `isPalindrome` that will receive one argument, a string. Your
function should return `true` if the string is a palindrome (that is, if it
reads the same forwards and backwards, like `"mom"` or `"racecar"`), and return
`false` if it is not a palindrome.


mom === mom // true
abc === cba // false


I need to make a function that returns true if a word is a palindrome adn false if not. That means if the word is the same as the word in reverse it should return tue.


To keep things simple, your function only needs to deal with lowercase strings
that are all letters (don't worry about spaces or special characters).


Here are a few examples:


```txt
Input: "madam"
Output: true


Input: "robot"
