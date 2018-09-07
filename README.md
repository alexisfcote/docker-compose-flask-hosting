Flask Docker Gunicorn Sample
============================

Sample Docker setup using Flask, Gunicorn, and Nginx. Static files can be hosted in static_host folder, and in each app*/static folder. app2 includes a redis database

# Setup

Use the ubuntu-setup.sh script to install all required dependencies
    $ ./ubuntu-setup.sh

#### Build

    $ docker-compose build

#### Run

    $ ./start.sh
