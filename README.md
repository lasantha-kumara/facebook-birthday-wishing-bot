# WISHBOT

Automate facebook birthday wishing process using Python.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Usage](#usage)

## General info
This project is simple Lorem ipsum dolor generator.
	
## Technologies
Project is created with:
* Python version: 3.10.6
* Selenium 
	
## Setup

To clone and run this application, you'll need [Git](https://git-scm.com) installed on your computer. From your command line:

```
# Clone this repository
$ git clone https://github.com/lasanthamudalige/automate-facebook-birthday-wishes.git

# Go into the repository
$ cd automate-facebook-birthday-wishes/

# To install all dependencies
$ pip install -r requirements.txt
```

## Usage

To run this project in Linux/Unix:

```
$ python3 main.py
```

To run this project in Windows:

```
$ python main.py
```

## License 
This project is open source and available under the [MIT License](https://github.com/lasanthamudalige/automate-facebook-birthday-wishes/blob/main/LICENSE).

## Description:

This program
First this program look for username and password from the .env file form the local directory and and if found it will go to facebook home page an sign in. Then it will navigate to birthdays page and using aria-label it will add the wishing message to all input boxes.It will wait 10 seconds before closing.

