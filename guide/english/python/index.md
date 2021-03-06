---
title: Python
---
![alt text](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)

## What is Python?

<a href='https://www.python.org' target='_blank' rel='nofollow'>Python</a> is a general purpose programming language that is dynamically typed and interpreted. Python is known for its easy readability with great design principles. It was created by Guido van Rossum and released in 1991. Since then, the language has exploded in popularity.  

To learn more about Python, check out these pages on python.org:

<a href='https://www.python.org/doc/essays/blurb/' target='_blank' rel='nofollow'>What is Python?</a>

<a href='https://docs.python.org/3/faq/general.html' target='_blank' rel='nofollow'>Python FAQ</a>.

## Why Python?

> If you're new to programming, you've made the right choice. Python is the perfect beginners' language. It has a clear and simple syntax that will get you writing useful programs in short order. Python even has an interactive mode, which offers immediate feedback, allowing you to test out new ideas almost instantly.
If you've done some programming before, you've still made the right choice. Python has all the power and flexibility you'd expect from a modern, object-oriented programming language. But even with all of its power, you may be surprised how quickly you can build programs. In fact, ideas translate so quickly to the computer, Python has been called "programming at the speed of thought".
> - Michael Dawson

## Python 2 or Python 3

*   The two versions are similar. With knowledge of one, switching to writing code for the other is easy.
*   <a href='https://wiki.python.org/moin/Python2orPython3' target='_blank' rel='nofollow'>Python 2 or Python 3</a>
    *   <a href='https://www.python.org/dev/peps/pep-0373/' target='_blank' rel='nofollow'>Python 2.x will not be maintained past 2020.</a> 
    * 3.x is under active development. This means that all recent standard library improvements, for example, are only available by default in Python 3.x.
    *   The Python ecosystem has amassed a significant amount of quality software over the years. The downside of breaking backwards compatibility in 3.x is that some of that software (especially in-house software in companies) still doesn't work on 3.x yet.

## Installation

Most *nix based operating systems come with Python installed (usually Python 2, Python 3 in more recent ones). Replacing the system Python is not recommended and may cause problems. However, different versions of Python can be safely installed alongside the system Python. See <a href='https://docs.python.org/3/using/index.html' target='_blank' rel='nofollow'>Python Setup and Usage</a>.

Python doesn't ship with Windows. The installer and instructions can be found <a href='https://docs.python.org/3/using/windows.html' target='_blank' rel='nofollow'>here</a>.

Linux operating systems come with different versions of Python pre-installed. However to install Python 3.x on Linux, follow this <a href='https://docs.aws.amazon.com/cli/latest/userguide/awscli-install-linux-python.html' target='_blank' rel='nofollow'>link</a>

MacOS doesn't come with Python 3 (however Python 2.7 pre-installed by Apple), the installer and instructions can be found <a href='https://docs.python.org/3/using/mac.html' target='_blank' rel='nofollow'>here</a>

## Python Interpreter

The Python interpreter is used to run Python scripts.

If it is available and in Unix shell’s search path, it is possible to start it by typing the command `python`, followed by the script name. This will invoke the interpreter and run the script.

`hello_campers.py`

```python
print('Hello campers!')
```

From the terminal:

    $ python hello_campers.py
    Hello campers!

When multiple versions of Python are installed, calling them by version is possible, depending on the install configuration. In the Cloud9 IDE custom environment, they can be invoked like this:

    $ python --version
    Python 2.7.6
    $ python3 --version
    Python 3.4.3
    $ python3.5 --version
    Python 3.5.1
    $ python3.6 --version
    Python 3.6.2 
    $ python3.7 --version
    Python 3.7.1

## Python Interpreter Interactive Mode

Interactive mode can be started by invoking the Python interpreter with the `-i` flag or without any arguments.

Interactive mode has a prompt where Python commands can be entered and run:

    $ python3.5
    Python 3.5.1 (default, Dec 18 2015, 00:00:00)
    GCC 4.8.4 on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>> print("Hello campers!")
    Hello campers!
    >>> 1 + 2
    3
    >>> exit()
    $

## The Zen of Python

Some of the principles that influenced the design of Python are included as an Easter egg and can be read by using the command inside Python interpreter interactive mode:

    >>> import this
    The Zen of Python, by Tim Peters

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!


## Pros and Cons of Python
### Pros
- Easy to read, learn, and write.
- Interactive language with a module support for almost all functionality.
- Open Source: You can contribute to the community and help others with the functions you have developed.
- A lot of good interpreters and notebooks available for better experience like jupyter notebook.
- It is a very easy language to debug. To check if a small bit of code works or not, you can just open up the interpreter and test.
- There are multiple libraries available for Python, like numpy, pandas, etc., to make doing complex operations easy!
- Don't have to worry about range of data types.  For instance, in the C language, we have to specify data types such as `int`, `long int`, `long long int`.

### Cons
- Being open source, many different ways have developed over the years for the same function. This sometimes creates chaos for others to read someone else's code.
- It is a slow language. So, a very bad language to use for developing general algorithms.
- Python is dynamically typed, so the errors in code only show up after running an application.
- Python is not the best langauge to use if your project requires efficient memory management.
- White space can confuse beginners, as spaces may change depending on the program.

## Documentation

<a href='https://docs.python.org/3/' target='_blank' rel='nofollow'>Python is well documented</a>. These docs include tutorials, guides, references and meta information for language.

Another important reference is the Python Enhancement Proposals (<a href='https://www.python.org/dev/peps/' target='_blank' rel='nofollow'>PEPs</a>). Included in the PEPs is a style guide for writing Python code, <a href='https://www.python.org/dev/peps/pep-0008/' target='_blank' rel='nofollow'>`PEP 8`</a>.

## Debugging

Inline `print` statements can be used for simple debugging:

> **... often the quickest way to debug a program is to add a few print statements to the source: the fast edit-test-debug cycle makes this simple approach very effective.**
> 
> --<a href='https://www.python.org/doc/essays/blurb/' target='_blank' rel='nofollow'>Executive Summary</a>

Python also includes more powerful tools for debugging, such as:

*   logging module, <a href='https://docs.python.org/3/library/logging.html' target='_blank' rel='nofollow'>_logging_</a>
*   debugging module, <a href='https://docs.python.org/3/library/pdb.html' target='_blank' rel='nofollow'>_pdb_</a>

Just note that these exist for now.

## Hello World!

Going back to the docs, we can read about the <a href='https://docs.python.org/3/library/functions.html#print' target='_blank' rel='nofollow'>`print`</a> function, a <a href='https://docs.python.org/3/library/functions.html' target='_blank' rel='nofollow'>_built-in function_</a> of the <a href='https://docs.python.org/3/library/index.html' target='_blank' rel='nofollow'>Python Standard Library</a>.

    print(*objects, sep=' ', end='\n', file=sys.stdout, flush=False)

The built-in functions are listed in alphabetical order. The name is followed by a parenthesized list of formal parameters with optional default values. Under that is a short description of the function and its parameters are given. Occasionally, an example is provided.

The <a href='https://docs.python.org/3/library/functions.html#print' target='_blank' rel='nofollow'>`print`</a> function in Python 3 replaces the <a href='https://docs.python.org/2/reference/simple_stmts.html#print' target='_blank' rel='nofollow'>`print`</a> statement in Python 2.

    >>> print("Hello, World!")
    Hello, World!

A function is called when the name of the function is followed by `()`. For the 'Hello, World!' example, the print function is called with a string as an argument for the first parameter. For the rest of the parameters, default values are used.

The argument that we called the `print` function with is a `str` object or _string_, one of Python's [_built-in data types_](https://docs.python.org/3/library/stdtypes.html#text-sequence-type-str).
Also the most important thing about python is that you don't have to specify the data type while declaring a variable Python's compiler will do that itself, based on the type of value assigned.

The `objects` parameter is prefixed with a `*`, which indicates that the function will take an arbitrary number of arguments for that parameter.

## Things you can do with python
As stated python is a general purpose language. You can use it to do anything you like but one of the major uses of python is in machine learning and artificial intelligence. It is also a popular language in web development with some amazing frameworks like [Django](https://www.djangoproject.com/) and [flask](http://flask.pocoo.org/). It is also a popular scripting language. With its easy to read syntax it is becoming one the most popular programming languages growing rapidly in different fields.

## Want to learn more?

Free Code Camp has some great resources. The web is a big place, there's plenty more to explore:

* [Python Practice Book](http://anandology.com/python-practice-book/index.html)
* [Think Python](http://greenteapress.com/thinkpython/html/index.html)
* [Practical Business Python](http://pbpython.com/)
* [Real Python](https://realpython.com)
* [Full Stack Python](https://www.fullstackpython.com/)
* [Learn the Basics on codecademy](https://www.codecademy.com/learn/learn-python)
* [Computer science using Python on edX](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-11)
* [Intro to Computer Science CS101 on Udacity](https://www.udacity.com/course/intro-to-computer-science--cs101)
* [List of more resources for learning python on Awesome Python](https://awesome-python.com)
* [Interactive Python - How to Think Like a Computer Scientist](http://interactivepython.org/runestone/static/thinkcspy/index.html)
* [Everyday Python Project](http://interactivepython.org/runestone/static/everyday/index.html)
* [Python Developer’s Guide](https://devguide.python.org)
* [Learn Python the Hard Way book](https://learnpythonthehardway.org/python3)
* [Introduction to Python Programming on Udacity](https://www.udacity.com/course/introduction-to-python--ud1110)
* [Profiling in Python](https://docs.python.org/2/library/profile.html)
* [Python for Everybody Specialization](https://www.coursera.org/specializations/python)
