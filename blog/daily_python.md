# Simplify your work

In todays IT world we have so many things to do and often we do the same things. So why not automate it?


## Python to the rescue

Python is a versatile programming language (don't be afraid of word `programming` it's not that scarry). This programming language is easy to read and understand what it does even for those that do not have any programming experience.

For example:

```python
name = "Rolandas"

if name == "Rolandas":
    print(f"Hello {name}")
else:
    print("Hello world!")
```

This example first of all defines variable `name` and assigns a value `Rolandas`. Then it does a `if/else` condition where we check if `name` is equal `"Rolandas"`, if this is `true` then it will `print` a `Hello Rolandas`, but if the `name` is not equal `false` to `Rolandas` then this code will print `Hello World!`.


> To learn more you can start with official [Beginner's Guide to Python](https://wiki.python.org/moin/BeginnersGuide).

## Let's do TODO

A TODO list is both useful and a good start on working with Python.

What we need first is to understand how this TODO list should work, right? I imagine that it should have 4 features:

0. Open app
1. Add item
2. Modify item
3. Remove item

There is also a 4th item that is very necessary for a TODO list app, it's saving changes made to the content, so that next time when you will open your app it would show last time modified data.


### Let's start with item #0 - opening the app

Before opening the app, we need to think how it should look, should it be a web app, desktop app or a terminal? The most user friendly might be a web application, but it needs a runing server to work, which might be too much at the moment, the terminal looks easy, you don't need to do anything just type in some commands and you are in your app, while te easiest looks a desktop app, you just click two times on a desktop icon and it works!

#### Desktop app

To create a desktop application we need first to create a directory that will contain all of our code.

> I'm using unix based OS, but I will also give Windows OS examples later

First we need to create a directory


```bash
cd dev
mkdir todo_app
cd todo_app
```

