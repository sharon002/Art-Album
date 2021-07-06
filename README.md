# Personal gallery

#### By [sharonkemboi](https://github.com/sharon002/Art-Album.git)


## Description
This is an online platform where I display my photos for others to see.A user can click on an image to view the image details and also a  user can copy an image link. 

#### Github link
https://github.com/sharon002/Art-Album.git


#### Link to live site


## Setup and installations
* Clone Project to your machine
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.8 manage.py runserver`
* Access the live site using the local host provided


#### Prerequisites
1. [Python3.8](https://www.python.org/downloads/)

2. [virtualenv](https://virtualenv.pypa.io/en/stable/installation/)
3. [pip](https://pip.pypa.io/en/stable/installing/)

#### Technologies used
    - Python3.8
    - HTML
    - Bootstrap 3
    - Heroku
    - Postgresql
    - Django 2.0

#### Clone the Repo and rename it to suit your needs.
```bash
git clone https://github.com/sharon002/Art-Album.git
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```

#### Create and activate the virtual environment
```bash
python3.8 -m virtualenv virtual
```

```bash
source virtual/bin/activate
```

#### Setting up environment variables
Create a `.env` file and paste paste the following filling where appropriate:
```
SECRET_KEY=''
DEBUG=True
DB_NAME='gallery'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.8 manage.py check
python manage.py makemigrations news
python3.8 manage.py sqlmigrate news 0001
python3.8 manage.py migrate
```

#### Run the app
```bash
python3.8 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)


## Bugs
#### Known bugs
There are no known bugs at the moment 




## Support and contact details
Contact [sharon kemboi](sharonjep2016@gmail.com) for further help/support

### License
[MIT LICENSE](LICENCE)

Copyright (c)2021 **sharon kemboi**
