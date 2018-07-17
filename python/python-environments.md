[Back to the Python Index](README.md)

### Terminology
**Dependencies**

  > [placeholder]

**Deprecated**

  > [placeholder]

**Local Machine**

  > [placeholder]


### Why Isolated Python Environments?
You will hear about making "virtual environments" or "isolated Python environments" nearly everywhere when working in Python. It is a common practice that you will use to "isolate" dependencies for a given project.

What does that mean though? Well lets say you were building a Django or a Flask application. The very first dependency of your project is going to be Django or Flask. Ask yourself this, Are you only ever going to make just 1 Django or Flask application? Probably not. You will likely make a few dozen if you really like it.

So because of this, if we didn't use this thing called Python environments, we would run into an issue later on. Maybe one of the projects I previously built was a Django version 1.8 project and this new one I am trying to build, I want it to be in Django version 2.0 project. I would surely run into some errors if I attempt to run code from Django 1.8 that might be deprecated in version 2.0 of Django. But I dont want to have to keep re-installing Django 1.8 or 2.0 each time I want to run my project on my local machine, to work on it. So we "isolate" our dependencies for a given project into its very own environment, that in most cases isn't shared between unrelated projects.

#### Documentation Resources

* **[Virtual Environments](https://docs.python.org/3/tutorial/venv.html)**
    
**Third Party Packages**

* **[VirtualEnv](https://virtualenv.pypa.io/en/stable/)**
* **[VirtualEnv Wrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)**