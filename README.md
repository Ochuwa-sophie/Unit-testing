# Unit-testing with FizzBuzz

For each of the following, write the test first, then write just enough code to get that error passing. 
Run your tests again, and then write more code until your test passes. 

For the Javascript section:
Write your code in the index.js file, and your tests in the test.js file. 
Run your tests using npm test`. 

For the C# section:
Write your code in the fizzbuzz.cs file, and your tests in the FizzBuzzShould file in the UnitTest.Tests directory.
Run your tests using dotnet test or whichever test runner you use. 

The rules of our fizzbuzz function are:

* Given a multiple of 3 and 5, returns 'FizzBuzz'
* Given a multiple of 3, returns 'Fizz'
* Given a multiple of 5, returns 'Buzz'

## Test-Driven Development:

Remember, at each stage, you want to:

* Create the test and verify that it fails.
* Modify your code so that the test passes
* Look at the structure of the code: can you clean it up (refactor it) without making any tests fail?

Here's the steps to go through:

1. Write a test for a function called fizzbuzz that, given the number 1, it should return 1.
1. Write a test that fizzbuzz, given 2, should return 2.
1. Write a test that fizzbuzz, given 3, should return 'Fizz'.

We can skip a test for 4, since we can be pretty sure that it will pass. Let's instead write a test for 5. Given 5, fizzbuzz should return 'Buzz'.

4. At '6', we'll introduce another requirement: multiples of 3 should also return Fizz. Write a test that given 6, fizzbuzz should return 'Fizz'.

We can skip the tests for 6, 7, 8, and 9 since we're already testing those cases. For our next test, write a test that given a multiple of 5, we should return 'Buzz'.

5. Write a test that, given 15, fizzbuzz returns "FizzBuzz".
6. Write a test that, given multiple of 15, returns "FizzBuzz"
