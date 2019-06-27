# Types Variables Logic and Operations Lab 2

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## Question 1

You are given three grades obtained by 3 students, which are stored in variables `grade1`, `grade2`, `grade3` and all of type `Double`.
Create a variable called `yourGrade` of type `Double` and give it a value.
Print `"above average"` if your grade is greater than the class average or `"below average"` otherwise.

```swift
var grade1 = 7.0
var grade2 = 9.0
var grade3 = 5.0

// your code here

var grade1 = 7.0
var grade2 = 9.0
var grade3 = 5.0
var yourGrade = 9.0
var average = (grade1 + grade2 + grade3 + yourGrade)/4
//print (average)//

if yourGrade > average {
print ("above average")
}
else {
print ("below average")
}

```

***
## Question 2

You are given a number. Print even if the number is even or odd otherwise.

```swift
let number = 2

// your code here

let number = 2

if number % 2 == 0 {
print ("even")
}
else {
print ("odd")
}

```

***
## Question 3

You are given two numbers `a` and `b`. Print `"divisible"` if `a` is divisible by `b` and `"not divisible"` otherwise.

```swift
var a = 12
var b = 3

// code here

var a3 = 12
var b3 = 3

if a3 % b3 == 0 {
print ("divisible")
}
else {
print ("not divisible")
}

```

***
## Question 4

You are given three variables `a`, `b` and `c`. Check if at least two variables have the same value. If that is true, print `"At least two variables have the same value"` otherwise print `"All the values are different"`.

```swift
var a = 2
var b = 3
var c = 2

// your code here

var a4 = 2
var b4 = 3
var c4 = 2
if a4 == b4 || b4 == c4 || c4 == a4 {
print ("At least two variables have the same value")
}
else {
print ("All the values are different")
}

```

***
## Question 5

You are working on a smart-fridge. The smart-fridge knows how old the eggs and bacon in it are. You know that eggs spoil after 3 weeks (21 days) and bacon after one week (7 days). Given `baconAge` and `eggsAge` (both in days) determine if you can cook bacon and eggs, or which ingredients you need to throw out. If you can cook bacon and eggs, print `"you can cook bacon and eggs"`. If you need to throw out any ingredients, for each one print a line with the text `"throw out"` + bacon or eggs.

```swift
var baconAge = 6 // the bacon is 6 days old
var eggsAge = 12 // eggs are 12 days old

// your code here

var baconAge = 6
var eggsAge = 12

if baconAge > 7 && eggsAge > 21 {
print ("throw out bacon + eggs")
}
else if baconAge > 7 && eggsAge <= 21 {
print ("throw out bacon")
}
else if baconAge <= 7 && eggsAge > 21 {
print ("throw out eggs")
}
else {
print ("you can cook bacon and eggs")
}

```

***
## Question 6

You are given a year, determine if it’s a leap year. A leap year is a year containing an extra day. It has 366 days instead of the normal 365 days. The extra day is added in February, which has 29 days instead of the normal 28 days. Leap years occur every 4 years. 2012 was a leap year and 2016 will also be a leap year.
The above rule is valid except that every 100 years special rules apply. Years that are divisible by 100 are not leap years if they are not also divisible by 400. For example 1900 was not a leap year, but 2000 was. Print `"Leap year!"` or `"Not a leap year!"` depending on the year you are provided.

```swift
let year = 2014

// your code here

let year = 2000
if (year % 4 == 0 && year % 100 != 0) || (year % 400 == 0 ){
print ("Leap year!")
}
else {
print ("Not a leap year!")
}

```

***
## Question 7

If you use `random()` it will give you a random number within a specified range. Generate a random number and use it to simulate a coin toss. Print `"heads"` or `"tails"`.

```swift
let randomNum = Int.random(in: 0...100)

// your code here

let randomNum = Int.random(in: 0...100)
print (randomNum)
if randomNum % 2 == 0 {
print ("heads")
}
else {
print ("tails")
}

```

Hint: use an if/else block along with the `%` operator

***
## Question 8

You are given four variables `a`, `b`, `c` and `d`. Print the value of the smallest one.

```swift
var a = 5
var b = 6
var c = 3
var d = 4

// your code here

var a8 = 5
var b8 = 6
var c8 = 3
var d8 = 4
var array = [a8, b8, c8, d8]
var smallestValue = array.min()
print (smallestValue)

```

***
