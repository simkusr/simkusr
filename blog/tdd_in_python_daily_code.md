# TDD in Python daily code


Any developer that is working longer than 1 year as a professional has heard the term [TDD](https://en.wikipedia.org/wiki/Test-driven_development), but in case you haven't heard or don't know what it is, then please read about [Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development) before continuing reading. I will not provide the description of `TDD` in this blog post.

I will asume that you are a [Python](https://www.python.org/) developer and you know at least basics of how it works, if not, please checkout this blog post at [freeCodeCamp](https://www.freecodecamp.org/news/learning-python-from-zero-to-hero-120ea540b567/) which provids a good foundation.


## Testing library selection

The first thing we will do - we will select a tool with which we will work daily. `Python` has it's own built in [unittest](https://docs.python.org/3/library/unittest.html) library that allows to write tests. This is a great library which is a very simillar to [Java JUnit](https://junit.org/junit5/). But we will work with a different one - [pytest](https://docs.pytest.org/en/6.2.x/).
