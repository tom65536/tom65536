## Python-Programming Next Steps

This collection of Python and software development ressources is directed at Python programmers
who have just learned the basics and are about to dive into larger projects.

### Make sure you know the Language

You have probably learned all about loops, `if`-statements, variables and functions.
You might have heared about classes or even have written a couple of classes yourself.

Make sure you also learn about some other aspects as well which you might have neglected so far:

* Exception Handling (`try`, `except`, `finally`, ...)
* Ressource Handling (`with`-statement)
* Functional Programming (list comprehensions, map, reduce, iterators, lambdas, ...)

How well do you actually know your primitives? Did you know that the `for`-loop may have
an `else` branch?

The better you know the language features the more efficient you become in writing down
your code. You are not forced into workarounds when you know the most appropriate language
idioms.

Two Python guides that lead you beyond the very basics I have found here:

1. [Advanced Computer Programming in Python](https://advancedpythonprogramming.github.io/)
   by Karim Pichara and Christian Pieringer, available as web-book and print edition
2. [A Python Book: Beginning Python, Advanced Python, and Python Exercises](https://www.davekuhlman.org/python_book_01.pdf) by Dave Kuhlman


### Don't reinvent the wheel

Many problems you will encounter have been solved by many programmers in the past.
Python offers a huge standard library. Some modules (especially networking, os, data formats)
you will discover as the obvious solution once it comes to that very specific problem.
However, there are some modules I recommend to explore before you start writing your next
piece of code because you should keep them in mind when it comes to every day problems like
sorting, selecting, data structures, iterating etc.

Become acquainted with at least these standard library modules:

* [`re`](https://docs.python.org/3.9/library/re.html)
  -- Regular expression operations
* [`collections`](https://docs.python.org/3.9/library/collections.html)
  -- Container datatypes
* [`enum`](https://docs.python.org/3.9/library/enum.html)
  -- Support for enumeration
* [`abc`](https://docs.python.org/3.9/library/abc.html)
  -- Abstract Base Classes
* [`itertools`](https://docs.python.org/3.9/library/itertools.html)
  -- Functions creating iterators for efficient looping
* [`functools`](https://docs.python.org/3.9/library/functools.html)
  --  Higher-order functions and operations on callable objects
* [`unittest`](https://docs.python.org/3.9/library/unittest.html)
  -- Unit testing framework



## Best Practices
* Milestones, Development branches, Issues
* [Semantic Versioning](https://semver.org/)
* [Keep a ChangeLog](https://keepachangelog.com/)
* Python Style Guide [PEP8](https://www.python.org/dev/peps/pep-0008/)
* [Clean Code](https://clean-code-developer.de/)
  - SOLID
  - DRY
  - Composition over Inheritance
  - [Naming Conventions](https://www.freecodecamp.org/news/clean-coding-for-beginners/)
* GoF Design Patterns
 - [Design Patterns in Python](https://python-patterns.guide/)
 - https://refactoring.guru/design-patterns/python
* [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
* https://docs.python-guide.org/writing/structure/#structure-of-code-is-key

Start writing typed code from the beginning. Read the documentation
of these modules and the corresponding PEPs mentioned there:
* [`typing`](https://docs.python.org/3.9/library/typing.html)
  -- Support for type hints
* [`types`](https://docs.python.org/3.9/library/types.html)
  --  Dynamic type creation and names for built-in types


## Tooling
* bumpversion
* nox
* pre-commit
* whey, flit
* formatting
  - black
  - isort
* linting
  - flake8
  - mypy
  - import-lint
  - mccabe
* testing
  - (x)doctest
  - pytest
* doc
  - sphinx



## src layout
https://docs.pytest.org/en/6.2.x/goodpractices.html

Documenting
https://realpython.com/documenting-python-code/
