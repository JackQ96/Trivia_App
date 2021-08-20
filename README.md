# Trivia App
### Stack: Python / FLask / PostgreSQL / React

Hello and welcome to my Trivia App. This application was created for a project whilst completing a Udacity Full Stack Web Development Nano Degree.

This app is designed to play like a virtual pub quiz, where you can choose specific categories, or alternatively let the random generator choose for you. There is also the option to play the quiz, where you will be asked 10 questions (based on the categories you choose) and then at the end you will receive a final mark based on your performance.

## Endpoints
1) Display questions - Using GET requests we can retrieve questions stored within our postgres database. This can either be done by searching for all, searching for a specific ID, or alternatively if you know a partial string of a question, you can start typing it into the search field and the question will show.
2) Delete questions - Using the DELETE method, Allows the user to delete questions they do not believe to be suitable.
3) Add questions - Using POST requests we can add new questions to the quiz, with required fields in place that require both the question and answer text are present.


## Getting Setup

### Installing Dependencies

#### Python 3.7

Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

#### Virtual Enviornment

I recommend working within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organaized. Instructions for setting up a virual enviornment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### PIP Dependencies

Once you have your virtual environment setup and running, install dependencies by naviging to the `/backend` directory and running:

```bash
pip install -r requirements.txt
```

This will install all of the required packages we selected within the `requirements.txt` file.

##### Key Dependencies

- [Flask](http://flask.pocoo.org/)  is a lightweight backend microservices framework. Flask is required to handle requests and responses.

- [SQLAlchemy](https://www.sqlalchemy.org/) is the Python SQL toolkit and ORM we'll use handle the lightweight sqlite database. You'll primarily work in app.py and can reference models.py. 

- [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/#) is the extension we'll use to handle cross origin requests from our frontend server. 



#### Installing Node and NPM

This project depends on Nodejs and Node Package Manager (NPM). Before continuing, you must download and install Node (the download includes NPM) from [https://nodejs.com/en/download](https://nodejs.org/en/download/).

#### Installing project dependencies

This project uses NPM to manage software dependencies. NPM Relies on the package.json file located in the `frontend` directory of this repository. After cloning, open your terminal and run:

```bash
npm install
```


## Database Setup
With Postgres running, restore a database using the trivia.psql file provided. From the backend folder in terminal run:
```bash
psql trivia < trivia.psql
```


## Running the server

From within the `backend` directory first ensure you are working using your created virtual environment.

To run the server, execute:

```bash
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```


## Running Your Frontend in Dev Mode


Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits.<br>

```bash
npm start
```




