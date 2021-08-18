IMPORTANT : ne PAS forker ce projet, il contient mes remarques. Copier le md dans un autre repo.



# Test Driven Development

- Repository: `challenge-TDD`
- Type of Challenge: `Learning`
- Duration: `3 days`
- Deadline: `dd/mm/yy H:i AM/PM`
- Deployment strategy :
	- Github page
- Team challenge : `solo`


## The Mission

You will learn the basics of TDD, it stands for Test Driven Development, it's a way of writing code such that at every new step of your code will be tested before you even write it.

For example if you have to write a module that will give you a price, you know that you should get a number as an output of that module. You will then write a piece of code to test if you indeed get a number, then only after that you will write the corresponding code and finally test it. And so forth for every functionality.

The challenge will be structured the following :

- Day 1 (front&back): document yourself on testing and especially TDD, what is it, how it works, what are the principles. In the afternoon try these simple introductory exercises in your language: FizzBuzz (and Leap Years and Roman Numeral if you have time).

- Day 2 (back only?): Discover testing in you Webshop framework (cf resources at the bottom). Implement some testing features in your code.

- Day 3 (back only?): Implement a new feature in your webshop according to the TDD way.


## Day 1

### FizzBuzz Testing (mandatory):

Make a very little code that takes a number as input and as output gives :
- 'Fizz' if the number is divisible by 3
- 'Buzz' if the number is divisible by 5
- 'FizzBuzz' for both
- the input number for other cases

Build every "Unit Testing" (check that term) for each case you can think of. In TDD you should begin with the test first but here in this first exercice we will just focus on making testing work. If you want to do it directly the TDD way you're obviously welcome!

### Roman Numerals (optional)


Write a code that converts normal numbers to Roman ones, examples :

`1 -> I`

`19 -> XIX`

`334 -> CCCXXXIV`

`etc.`

(Tip: Forget numbers bigger than 3000, the romans didn't really use them)

Build it using the TDD workflow.

### Leap Years (optional)

Write a code that can tell if a year is leap or not.

Build it using the TDD way


## Day 2

### Things to test in your Webshop framework

- Models : existence, creation, fields etc.
- API : endpoints existence, working fine etc.

Document yourself on how to properly test your app in your framework, then implement it.



## Day 3

### New feature to implement in your Webshop with a TDD workflow

The following feature must be added to your webshop according to the TDD way of thinking:

`Get the last 10 orders from a specified user.`

Pay attention to really think in term of TDD, think test first. What tests should I make first ? Then step by step implement the full feature.



## Learning Objectives

- To be able to test features
- To be able to implement new code the TDD way (workflow understood)
- To be able to use Unit Testing
- To be able to build features in your framework the TDD way


### Must-have features

- A working testing app for FizzBuzz with unit testing
- To have built some testing features in your Webshop app
- to have built at least one unit testing of the new feature asked for the Webshop


### Nice-to-have features

- All the optional exercises
- A full (as far as possible) testing module in your webshop app.




## Evaluation criterias

| Criteria       | Indicator                                                                             | Yes/No |
|----------------|---------------------------------------------------------------------------------------|--------|
| 1. Is complete | The student has realized all must-have features and nice to have features.            |        |
|                | The workflow of TDD is respected                                                      |        |
|                | The student can use Unit testing                                                      |        |
|                | The repo is clean                                                                     |        |
|                | The readme is clean                                                                   |        |
| 2. Is Correct  | The student has realized the first two must-have features                             |        |
|                | The workflow of TDD is respected                                                      |        |
|                | The student can use Unit testing                                                      |        |
|                | The repo is clean                                                                     |        |
|                | The readme is clean                                                                   |        |



## Resources

Examples : React, Vue, Rails :
https://learntdd.in/

Doc for Symfony:
https://symfony.com/doc/current/testing.html

Doc for Laravel:
https://laravel.com/docs/8.x/testing

Doc for Django:
https://docs.djangoproject.com/en/3.2/topics/testing/overview/

Doc for Node Express:
https://alexanderpaterson.com/posts/how-to-start-unit-testing-your-express-apps

Nice videos about testing :
https://thoughtbot.com/upcase/testing

Nice introductory videos (in ruby) :
https://thoughtbot.com/upcase/fundamentals-of-tdd

A list of TDD exercices if you want to practice (solution is in Java)
http://www.tddbuddy.com/

A list of various katas including some TDD oriented:
https://codingdojo.org/kata/

Search for "TDD katas" and you will find a lot of exercices. For yor information a kata for a developer is a coding exercice.

Of course don't forget that Google and Wikipedia are your friends, and as developers StackOverflows is your almighty god.

## A final note of encouragement

This should be everyone of you in 3 days:


![Everyone of you in 3 days!](https://media3.giphy.com/media/hpF9R9M1PHN5e5liSx/giphy.gif?cid=ecf05e47vd4pbsaibshclbkx3jcz7byn9kve1wrrp88e0zm1&rid=giphy.gif&ct=g)
