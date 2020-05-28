# Part 1
In this part I wish to get the working environment setup to make sure all are on the same page.
The aim is to ensure all have a working environment and the necessary tooling setup to get started.

By the end of this I hope to have:

- A working development environment.
- Solid tooling to work with Python.
- A first Hello World.

## Installing Python.
For the sake of this course, I will **not** consider the legacy version Python 2.
In the case of Linux, Python usually is installed or just one `apt get install python3`.

Sadly the installation experience of Python under Winderp is not quite as smooth.
I have no real experience with working with Python on Winderp, so I can only really offer some pointers.

You have the option of installing Python by heading over to [Python's website](https://www.python.org/) and downloading their installer.
Their installer unfortunately only really dumps Python on your disk and it's up to the user to integrate it into the system.
 
Another option is to install Python using a pre-packaged version like [Anaconda](https://www.anaconda.com/). 
Whilst it does all the things - like installing the most common addons  and adding python to your `PATH` - it also comes with bloat.

Your next option might be to be le fancy and use such an environment as WSL.

Any will probably do just fine.
Just know that there is - as so often with Python - no singular true way to do things.

At the end of this you should be able to open up a terminal and type in `python` and be greeted with a python prompt. 

## Editors
Editor flame wars are rampant and I don't really care to dive into them.
Whilst it is totally possible to write Python with something like Notepad, eventually you will hamper your ability to manage more complex code without help.

This is where an IDE comes in.
It has an understanding of Python's syntax, can colour highlight your code and will possibly guide you along your journeys.

PyCharm usually is fairly smart dealing with Python.
Others will argue VsCode is the bees knees.

I don't care about your tools of choice.

## Git
You are hacking away and realize you have maneuvered yourself into a corner.
This is where git comes in.

Git is a tool to help manage your code base.
A safety net to undo your sins.
A tool to save your hard work and - if you choose to - share your code with others.

Winderp's installation experience here is also rather lacking too, whilst most *NIX like systems ought to have it installed or at arm's length.

I am really unclear what to recommend under Winderp, but have heard [success can be achieved](https://gitforwindows.org/) - your mileage may vary.

## Interpreters
Let's keep this short.
The [Python REPL](https://docs.python.org/3/tutorial/interpreter.html) is neat, but primitive.

[IPyhton](https://ipython.org/) very much is like the IDE - but in REPL form.
If ever I recommend a tool - this is the one.