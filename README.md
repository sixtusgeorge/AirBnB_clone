# 0x00. AirBnB clone - The console

The goal of the project is to deploy on our server a simple copy of the [AirBnB Website](https://www.airbnb.com/). We are not to implement all the features of the website, only some of them to cover all fundamental concepts of the higher level programming track. This is part of ALX SE certification projects.

At the end of the project, we will have a complete web application composed by:

* A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
* A website (the front-end) that shows the final product to everybody: static and dynamic
* A database or files that store data (data = objects)
* An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them)


## Steps

We will build this application step by step.

Each step will link to a concept:

**The Console**
- create your data model
- manage (create, update, destroy, etc) objects via a console / command interpreter
- store and persist objects to a file (JSON file)

**Web static**

- learn HTML/CSS
- create the HTML of your application
- create template of each object

**MySQL storage**

- replace the file storage by a Database storage
- map your models to a table in database by using an O.R.M.

**Web framework - templating**

- create your first web server in Python
- make your static HTML file dynamic by using objects stored in a file or database

**RESTful API**
- expose all your objects stored via a JSON web interface
- manipulate your objects via a RESTful API

**Web dynamic**
- learn JQuery
- load objects from the client side by using your own RESTful API


### Command interpreter

The project makes use of the python cmd model to manage the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object


### Execution

**Our shell will work like this in interactive mode:**

<code>
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
</code>

**But also in non-interactive mode:**

<code>
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
</code>


**how to start it**
> ./console.py


**How to use it**
<code>
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

help quit
Quit command to exit the program


(hbnb)
(hbnb)
(hbnb)
(hbnb) quit
guillaume@ubuntu:~/AirBnB$ 
</code>

# concepts

1. [Packages](https://docs.python.org/3.4/tutorial/modules.html#packages)
2. [AirBnB Website](https://www.airbnb.com/)


# Resources

1. [cmd module](https://docs.python.org/3.8/library/cmd.html)
2. [cmd module in depth](http://pymotw.com/2/cmd/)
3. [uuid module](https://docs.python.org/3.8/library/uuid.html)
4. [datetime](https://docs.python.org/3.8/library/datetime.html)
5. [unittest module](https://docs.python.org/3.8/library/unittest.html#module-unittest)
6. [args/kwargs](https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/)
7. [Pyrhon test cheatsheet](https://www.pythonsheets.com/notes/python-tests.html)
8. [cmd module wiki page](https://wiki.python.org/moin/CmdModule)
9. [Python unittest](https://realpython.com/python-testing/)


# Tasks


