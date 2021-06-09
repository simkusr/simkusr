# TDD in Python daily code

Any developer that is working longer than 1 year as a professional has heard the term [TDD](https://en.wikipedia.org/wiki/Test-driven_development), but in case you haven't heard or don't know what it is, then please read about [Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development) before continuing reading. I will not provide the description of `TDD` in this blog post.


## Our tools with which we will work

### Python Language
I will asume that you are a [Python](https://www.python.org/) developer and you know at least basics of how it works, if not, please checkout this blog post at [freeCodeCamp](https://www.freecodecamp.org/news/learning-python-from-zero-to-hero-120ea540b567/) which provids a good foundation.


### Pytest vs unittest
`Python` has it's own built in [unittest](https://docs.python.org/3/library/unittest.html) library that allows to write tests. This is a great library which is a very simillar to [Java JUnit](https://junit.org/junit5/). But we will work with a different one - [pytest](https://docs.pytest.org/en/6.2.x/) which is widly accepted in `Python` community. Here is a great [StackOverflow](https://stackoverflow.com/questions/27954702/unittest-vs-pytest) thread where you can see the benefits of using `Pytest` instead of `unittest`.


## TDD workflow

`Red/Green/Refactor` is a TDD mantra - as Kent Beck says in his [book](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530). We will also hold on this concept. We will write small tests that fail, then we will write a minimal viable code that will pass the failing test, then we will refactor code and again the cycle of `Red/Green/Refactor`.


