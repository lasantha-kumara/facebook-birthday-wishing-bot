# WISHBOT

Automate facebook birthday wishing process using [Python](https://www.python.org/) and [Selenium](https://www.selenium.dev/).

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Usage](#usage)

## General info
This is an automation project to wish people on their birthdays in facebook. 
* This program will solve day to day birthday wishing process by automating it.
	
## Technologies
Project is created with:
* Python version: 3.10.6
* Selenium version: 4.7.2
	
## Setup

To clone and run this application, you'll need [Git](https://git-scm.com) installed on your computer.\
From your command line run:

```
# Clone this repository
$ git clone https://github.com/lasanthamudalige/automate-facebook-birthday-wishes.git

# Go into the repository
$ cd automate-facebook-birthday-wishes/

# To install all dependencies
$ pip install -r requirements.txt

# To create an env file
$ touch .env

# To open the env file
$ open .env
```

After opening the .env file add below 2 lines to the file and save it.

```
FACEBOOK_EMAIL="your_facebook_email"
FACEBOOK_PASSWORD="your_facebook_password"
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

