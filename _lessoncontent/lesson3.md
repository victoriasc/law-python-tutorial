---
layout: page
title: "Lesson 3"
description: "Basic Syntax of Python"
---
## Getting started with Python

### Basic syntax
Like using any language (e.g. english with punctuation and word order) Python has basic syntax you need to use to get your code to work. In fact it is through this syntax that the *interpreter* knows how to run code. 

#### Key examples

{% highlight python %}
# if you want to add a *comment* to your code (aka something that does run) add a hash tag

# make sure to indent your code (e.g. with loops and conditionals)
if a > 3:
    print("high")

# Code is most useful when it's generalisable making variables your best friends
# A variable is kind of like a container - the contents may change but the label stays the same
a = 26
print(a)
a = a + 6
print(a)
# you'll notice that if you want to allocate data to that label you use an `=`
{% endhighlight %}


### Basic Functions
Most functions look like this `add()`
Think of them a bit like maths functions - You tend to put something into them (e.g. 2 and 3) and get something out (5)

#### Printing 
One of the most useful functions is `print()`. Use it any time you want an output to be printed after running the code
{% highlight python %}
print("Hello, World")
{% endhighlight %}

#### Maths functions
An exception to the `function()` format are mathematical expressions. There are some functions that carry across their notation from maths 

Examples include:
{% highlight python %}
# plus
a = 1 + 2
# minus 
b = a - 2
# multiplication 
c = b*a
# division 
d = b/a
# greater than and less than 
a > b # greater or equal a >= b
b < a # less than or equal a <= b

# equals
a == b # not equal a != b

# or
if (a | b > 3):
    # and 
    if (a & b > 3):
        print(c)

# if you add, subtracting or multiplying to the same variable you can also simplify it
a += 1 # this is: a = a + 1

# There are even more (but here are probably the most useful ones)
{% endhighlight %}