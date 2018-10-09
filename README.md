
## Exercises

Problem Set 3 contains 10 exercises, each of which will be written in separate methods. The ```main``` method has already been declared for you, but you'll need to implement it.

### Exercise 1 (```dateFashion```)

Imagine you and your date are trying to a table at an exclusive restaurant. Your chances of getting a table are based on the combined factors of the stylishness of your and your date's clothes (respectively encoded as an integer value, 0 to 10, in the ```you``` and ```date``` parameters). If either of you is very stylish (i.e., an 8 or more), then you will get a table (```YES```). There is one exception to this rule: if either of you is very unstylish (i.e., a 2 or less), then you will not get a table (```NO```). Otherwise, you might get a table (```MAYBE```). Your method should print ```YES```, ```NO```, or ```MAYBE```. Nothing more, nothing less.

```
dateFashion(5, 10) should yield YES.
dateFashion(5, 5) should yield MAYBE.
dateFashion(2, 8) should yield NO.
```

### Exercise 2 (```fizzString```)

You have been given the very important responsibility of conditional printing. Using the first letter of an all-lowercase ```String```, you need to print either ```FIZZ```, ```BUZZ```, or ```FIZZBUZZ```. If the input ```String``` (i.e., the ```str``` parameter) starts with the letter "f", print ```FIZZ```. If ```str``` ends with the letter "b", print ```BUZZ```. If both of these conditions are true, print ```FIZZBUZZ```. In all other cases, print ```str``` unchanged.

```
fizzString("fig") should yield FIZZ.
fizzString("dib") should yield BUZZ.
fizzString("fib") should yield FIZZBUZZ.
fizzString("abc") should yield abc.
```

### Exercise 3 (```squirrelPlay```)

The squirrels in Palo Alto, CA, spend most of the day playing. In particular, they play if the temperature outside is between 60 and 90 degrees (inclusive). If it is the summer, then the upper limit is increased to 100 degrees (still inclusive). Given an integer temperature value (i.e., the ```temperature``` parameter) and a ```boolean``` variable representing whether or not it is the summer (i.e., the ```isSummer``` parameter), print ```YES``` if the squirrels are playing and ```NO``` if they are not.

```
squirrelPlay(70, false) should yield YES.
squirrelPlay(95, false) should yield NO.
squirrelPlay(95, true) should yield YES.
```

### Exercise 4 (```fizzStringAgain```)

Given an integer value (i.e., the ```n``` parameter), print the ```String``` form of the number followed by an exclamation point. There are a few expections to this rule. If ```n``` is divisible by 3, replace the number with ```FIZZ```; if ```n``` is divisible by 5, replace the number with ```BUZZ```; if ```n``` is divisible by by both 3 and 5, replace the number with ```FIZZBUZZ```.

```
fizzStringAgain(2) should yield 2!.
fizzStringAgain(9) should yield FIZZ!.
fizzStringAgain(10) should yield BUZZ!.
fizzStringAgain(15) should yield FIZZBUZZ!.
```

### Exercise 5 (```makeBricks```)

I need to build a row of bricks that is exactly ```goal``` inches long, where ```goal``` is the parameter value provided. I have a certain number of 1-inch bricks, as well as a certain number of 5-inch bricks. Using the materials at hand, print whether or not the task at hand is achievable.

```
makeBricks(3, 1, 8) should yield YES.
makeBricks(3, 1, 9) should yield NO.
makeBricks(3, 2, 10) should yield YES.
```

### Exercise 6 (```loneSum```)

This one's pretty simple. Given three integer values (i.e., the ```a```, ```b```, and ```c``` parameters), print their sum. As always, there's a catch. If one of the values is the same as another, do not count it towards the sum.

```
loneSum(1, 2, 3) should yield 6.
loneSum(3, 2, 3) should yield 2.
loneSum(3, 3, 3) should yield 0.
```

### Exercise 7 (```luckySum```)

Another one with addition. Given three integer values (i.e., the parameters ```a```, ```b```, and ```c```), print their sum. In a shocking turn of events, there's a catch. If one of the values is 13, it and any values to its right do not count.

```
luckySum(1, 2, 3) should yield 6.
luckySum(1, 2, 13) should yield 3.
luckySum(1, 13, 3) should yield 1.
```

### Exercise 8 (```factorialWithFor```)

This one couldn't get any more straightforward. Given some integer value (i.e., the parameter ```n```), compute its factorial. The factorial of an integer is that integer multiplied by all positive integers less than it (i.e., 5! = 5 * 4 * 3 * 2 * 1 = 120). Use a ```for``` loop to solve this.

```
factorialWithFor(3) should yield 3! = 6.
factorialWithFor(4) should yield 4! = 24.
factorialWithFor(5) should yield 5! = 120.
```

### Exercise 9 (```factorialWithWhile```)

This is the same as ```factorialWithFor```, except you need to use a ```while``` loop instead of a ```for``` loop.

```
factorialWithWhile(3) should yield 3! = 6.
factorialWithWhile(4) should yield 4! = 24.
factorialWithWhile(5) should yield 5! = 120.
```

### Exercise 10 (```isPrime```)

A prime number is a whole number greater than 1 that cannot be formed by multiplying two smaller whole numbers. Given some integer value (i.e., the parameter ```n```), print ```PRIME``` if it is prime. Otherwise, print ```NOT PRIME```.

```
isPrime(1) should yield NOT PRIME.
isPrime(2) should yield PRIME.
isPrime(17) should yield PRIME.
isPrime(144) should yield NOT PRIME.
```

## Deadline

Your Canvas submission is due at or before 11:59pm on your section-specific due date.
* October 9, 2018 (A 9/10)
* October 10, 2018 (B 1/2)

### Submission Requirements

All that is required for submission is the URL to your [GitHub](https://github.com/) repository for this problem set.
