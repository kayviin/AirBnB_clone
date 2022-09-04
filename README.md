<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Airbnb Clone</h3>

<div align="center">


</div

---

<p align="center"> AirBnB project
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Authors](#authors)

## About <a name = "about"></a>

This is a Airbnb clone projects that will be build with the aim to learn and apply concepts of high level programming and software engineering in general

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Python3

### Installing

Clone this repository

```
git clone git@github.com:callistus406/AirBnB_clone.git
cd AirBnB_clone
./console.py
```

## 🔧 Running the tests <a name = "tests"></a>

This project uses the python unittest model 

#### Run all unit tests
`python3 -m unittest discover tests`

#### Run a test from a specific file
`python3 -m unittest tests/tespytestt_models/test_base_model.py`

## Usage <a name="usage"></a>

You can run the schell (in an interactive or non-interactive mode) to manipulate your models.
You can start it from running the console.py file:

```
$ ./console.py
```

The following commands are supported:

### create: 
  Creates a new instance of BaseModel, saves it (to the JSON file) and prints the id. 
  Ex: 
  ```
  $ create BaseModel
  ```

### show: 
  Prints the string representation of an instance based on the class name and id. 
  Ex: 
  ```
  $ show BaseModel 1234-1234-1234.
  ```

### destroy:
  Deletes an instance based on the class name and id (save the change into the JSON file). 
  Ex:
  ```
  $ destroy BaseModel 1234-1234-1234.
  ```

### all:
  Prints all string representation of all instances based or not on the class name. 
  Example to show all instances
  ```
  $ all
  ```

  Example to show all instances of BaseModel only
  ```
  $ all BaseModel
  ```

### update:
  Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file). 
  Ex: 
  ```
  $ update BaseModel 1234-1234-1234 email "alxSchool@gmail.com"
  ```

### quit:
  Quit the shell 


## Built Using <a name = "built_using"></a>

- [Python](https://www.python.org/) - Programming language

## ✍️ Authors <a name = "authors"></a>

- [@callistus406](https://github.com/callistus406) - Ukaobasi Callistus
- [@Kayviin](https://github.com/kayviin) - Chuka Okodike
