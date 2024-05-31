# Creating REST APIs

You will be able to:

- Create a simple web application using Flask.
- Access the REST API endpoints of your application through the browser

## Python

Python is a programming language that lets you work more quickly and integrate your systems more effectively.
Python is used in many application domains. It supports Web development with the help of frameworks such as Flask.
Python is widely used in scientific and numeric computing with the help of libraries such as SciPy for mathematics, science, and engineering.
Python is also a popular choice among the Artificial Intelligence and machine learning community.

## Flask

Flask is classified as a micro web framework as it does not require particular tools or libraries.
It was built with scalability and simplicity in mind.
Flask applications are known for being lightweight compared to other frameworks.
Since Flask is not opinionated about what database or template engine to use, it is a good choice for RESTful APIs.

## Task

- Create a RESTful API in Python
- Use Flask to host your REST API.

## Installation

For this module, you will need Python 3 and pip, which is the Python package manager.

Once you verify you have Python and pip, you can then proceed to install Flask with the pip install command.

```bash
python3 -m pip install flask
```

### hello.py

You create the hello.py file with the content shown.
You then run the Flask server to host this python file and the output will be displayed.

```bash
flask --app hello run
```

When you open this ‘hello world’ web application in the browser by navigating to 127 dot 0 dot 0 dot 1 and port 5000 (127.0.0.1:5000), you will see the response “Hello World”.

```browser
127.0.0.1:5000
```

### server.py

You create the server.py file with the content shown.

Run server.py to start a server which is listening at port 5000 and serving a REST API endpoint at the root / that returns the string Hello World!.

```bash
python3 sever.py
```

### product.py

You will now create a new python file with the name ‘products.py’ which will provide all endpoints for your products microservice.

You start with defining the imports and creating your default list of products.
You are not using any database to persist these products, so every time you restart the API, you start with the same list of products.
Next, you define the GET method to retrieve all the products. And this method implicitly returns ‘200’, which in HTTP means OK.

Flask is a micro web framework to host Python web applications, you can create your first RESTful API as a microservice using Python,
and you can host your first RESTful API using Flask.
