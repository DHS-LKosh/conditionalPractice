# conditionalPractice
Practice your knowledge of conditionals.  Challenge yourself to use ternary operators.  If possible, try to use methods to organize your code.

## Question 1
Ask the user for an integer.  Determine if the number is even or odd.
```
Enter number: 3
Odd
```

## Question 2
Ask the user to enter three doubles.  **Without multiplying** determine what the sign of the solution will be (+/-).
```
Enter number: -9
Enter number: -1.8
Enter number: 3.14
Answer is positive
```

## Question 3
You have a green lottery ticket, with ints a, b, and c on it. If the numbers are all different from each other, the result is 0. If all of the numbers are the same, the result is 20. If two of the numbers are the same, the result is 10.
```
greenTicket(1, 2, 3) → 0
greenTicket(2, 2, 2) → 20
greenTicket(1, 1, 2) → 10
```

## Question 4
Given two ints, each in the range 10..99, return true if there is a digit that appears in both numbers, such as the 2 in 12 and 23. (Note: division, e.g. n/10, gives the left digit while the % "mod" n%10 gives the right digit.)

```
shareDigit(12, 23) → true
shareDigit(12, 43) → false
shareDigit(12, 44) → false
```

## Question 5
We are having a party with amounts of tea and candy. Return the int outcome of the party encoded as 0=bad, 1=good, or 2=great. A party is good (1) if both tea and candy are at least 5. However, if either tea or candy is at least double the amount of the other one, the party is great (2). However, in all cases, if either tea or candy is less than 5, the party is always bad (0).

```
teaParty(6, 8) → 1
teaParty(3, 8) → 0
```
