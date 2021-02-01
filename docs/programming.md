---
authors:
    - Tom Gregory
date: 2020-09-23
---

# Computer Programming

You should already be familiar with at least one object-oriented programming language. [Java][java] and [Python][python] are useful languages for this purpose.

[java]:https://go.java/student-resources/
[python]:https://www.python.org/about/gettingstarted/

## During the MSIS program
During your time in the MSIS program you will use R, PHP, Javascript and possibly other computer languages. You will learn about RPA, which uses many concepts from programming. The more languages you learn, the better you will understand how computer languages work, why a particular language might be more appropriate for a given task, and why different languages use different idioms.

*[RPA]: Robotic Process Automation

You are encouraged to practice with Python, as that is what a majority of our incoming students studied. However, many of these exercises can be completed in any programming languages.

## Major concepts

**You should be able to write simple programs** in at least one programming language. (It doesn't matter which one.) Using the code of the program you wrote, you should also be able to do the following:

1. Explain variable _**types**_ in the programming language you learned.
2. Use _**control structures**_ like `if` statements and loops  to control a program's flow.
3. Build one or more functions or object methods that accept parameters and have return types.
4. Explain _**encapsulation**_, and why code is often organized into objects and classes.
    1. Explain the difference between a _**class**_ and an object _**instance**_.
    2. Explain _**inheritance**_ and _**polymorphism**_, and demonstrate these concepts with a class diagram.
    3. Explain the difference between static and instance methods of an object.
5. Explain the importance of _**serializing**_ data.

## Resources

There are many great resources for learning basic programming. Learning on your own can be a challenge, but the best advice is to _write software_. Even professional programmers do this when learning a new language. [^sevenlang]

[^sevenlang]: For example, see the book _Seven Languages in Seven Weeks_, by Bruce Tate, Pragmatic Bookshelf (2010), ISBN-13: 978-1934356593 [[Amazon]](https://www.amazon.com/Seven-Languages-Weeks-Programming-Programmers/dp/193435659X/)

Most of the resources listed here are for Python, but you should be able to find similar resources for any programming language. When looking for Python resources, make sure it covers Python 3 and not Python 2.

There are many ways to learn Python, from online tutorials, online learning companies like [Data Camp][datacamp] and [Code Academy][codeacademy], and even [EdX courses][edx].

[datacamp]:https://www.datacamp.com/courses/intro-to-python-for-data-science
[codeacademy]:https://www.codecademy.com/catalog/language/python
[edx]:https://www.edx.org/learn/python

The site [learnpython.org](https://www.learnpython.org) has some great interactive lessons. [Google has a free Python course][google-python] too. If you prefer videos, Mosh Hamedani has a very popular ["Python for Beginners" video on YouTube][mosh-yt]. On the down side, these courses don't have good coverage of object-oriented concepts like objects, classes, and instances.

[Python.org][python-learn] and [WikiBooks][wikibooks] both have great references for anyone learning Python, but they focus on specific topics rather than on building projects. As you practice Python, the ["LearnPython" Reddit][reddit-learn] can help with specific concepts.

[mosh-yt]:https://www.youtube.com/watch?v=kqtD5dpn9C8
[google-python]:https://developers.google.com/edu/python/
[python-learn]:https://docs.python.org/3/tutorial/index.html
[wikibooks]:https://en.wikibooks.org/wiki/Python_Programming
[reddit-learn]:https://www.reddit.com/r/learnpython/wiki/faq

Tested and highly-reviewed books for learning Python:

  * _Python Crash Course, 2nd Ed._, Eric Matthes, No Starch Press (2019), ISBN-13: 978-1593279288 [[Amazon]](https://www.amazon.com/Python-Crash-Course-2nd-Edition/dp/1593279280/)
  * _Learn Python in One Day and Learn It Well (2nd Ed)_, Jamie Chan, CreateSpace Independent Publishing Platform; 2nd Edition (2017), ISBN-13: 978-1546488330 [[Amazon]](https://www.amazon.com/Learn-Python-One-Well-Hands/dp/1546488332/)
  * _Practical Programming: An Introduction to Computer Science Using Python 3.6 (3rd ed.)_, Paul Gries, Jennifer Campbell, Jason Montojo, Pragmatic Bookshelf (2017), ISBN-13: 978-1680502688 [[Amazon]](https://www.amazon.com/Practical-Programming-Introduction-Computer-Science-dp-1680502689/dp/1680502689/)
  * _Learn Programming in Python with Cody Jackson_, Cody Jackson, Packt Publishing (2018), ISBN-13: 978-1789531947 [[Amazon]](https://www.amazon.com/Learn-Programming-Python-Cody-Jackson/dp/1789531942/)

## Object-oriented programming

Once you have some experience with Python (or whatever programming language you chose), it's important to make sure you also understand object-oriented programming concepts. The following tutorials cover OOP concepts in Python:

* ["Object-Oriented Programming (OOP) in Python 3"][oop-amos], by David Amos
* Data Camp's ["Python Object-Oriented Programming (OOP): Tutorial"][oop-dc]
* [Bernd Klein][oop-klein] has a good tutorial on OOP in Python

*[OOP]: Object-Oriented Programming
[oop-amos]:https://realpython.com/python3-object-oriented-programming/
[oop-dc]:https://www.datacamp.com/community/tutorials/python-oop-tutorial
[oop-klein]:https://www.python-course.eu/python3_object_oriented_programming.php

To get an even better understanding of object-oriented application design, we recommend [_Head First Object-Oriented Analysis and Design_][hfooad], by Brett D. McLaughlin, Gary Pollice, and Dave West. It's written in an unusual (but effective!) style, and the book is a much easier read than you might expect for it's size. The only downside for Python learners is that the book is written all in Java. However, the concepts translate to any OOP language, and once you understand Python you'll be able to grok the code in this book.

[hfooad]:https://www.amazon.com/Head-First-Object-Oriented-Analysis-Design-dp-0596008678/dp/0596008678/

## Practice
Here is a small list of programs or scripts you could write. These can be accomplished as simple command-line applications, or built in a slightly more complex way as web applications. You are encouraged to be comfortable with both methods.

* **Mortgage interest calculator.** Ask the user for an interest rate, loan term, and amount financed. Print out both the interest paid over the life of the loan and total amount the lessee will pay.
* **Unit conversion.** Ask the user for a temperature in Fahrenheit. Print output in Celsius. For a bigger challenge, also ask the user for the input and output units. _This exercise can be repeated using liquid measures (quarts, gallons, liters), weight measures (pounds, kilograms, stone), distance measures (feet, yards, miles, meters), etc._
* **Calculator.** Allow the user to enter a mathematical equation. Output the answer. For greater difficulty, correctly support order of operations (2 + 3 * 4 = 14).
* **Read a file** Given a file with a list of words as input, filter the file to remove duplicates, and return the list sorted alphabetically.
* **TODO list (using a database)** Write a TODO list app. Store future todos and completed items in a database. (Good databases to use for this project include SQLite and MySQL.)
* **Consume a web service.** Write a program that uses a free web service. There are several lists of free web service APIs available online ([like this one](https://github.com/public-apis/public-apis)). Here are some specific examples:
    - Calculate the distance between two ZIP codes [https://www.zipcodeapi.com/API](https://www.zipcodeapi.com/API) (Requires free signup for API key)
    - Fetch a random person, and print their name and email address [https://randomuser.me](https://randomuser.me)
    - Return movies details based on a title search. [https://www.omdbapi.com](https://www.omdbapi.com) (Requires free signup for API key)
