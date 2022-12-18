# WISHBOT

Automate facebook birthday wishing process using Python.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is simple Lorem ipsum dolor generator.
	
## Technologies
Project is created with:
* Python version: 3.10.6
* Selenium version: 4.7.2
* Pyperclip module version: 1.8.2
* Python-dotenv module version: 0.21.0
	
## Setup

To install required packages run:
```
$ pip install -r requirements.txt
```

This will installs all the packages needed for the program.

## Usage

To run this project in linux:

```
$ git clone https://github.com/lasanthamudalige/automate-facebook-birthday-wishes.git
$ cd automate-facebook-birthday-wishes/
$ python3 main.py
```

To run this project in windows:

```
$ git clone https://github.com/lasanthamudalige/automate-facebook-birthday-wishes.git
$ cd automate-facebook-birthday-wishes/
$ python main.py
```


## Description:

This program
First this program look for username and password from the .env file form the local directory and and if found it will go to facebook home page an sign in. Then it will navigate to birthdays page and using aria-label it will add the wishing message to all input boxes.It will wait 10 seconds before closing.

