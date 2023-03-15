Odoo 16
=========

odoo-16-template is a dockerized version of Odoo Community 16

## Prerequisites

Make sure to have docker and docker-compose installed in your system.

## Installation

Start by pulling the code from the repository

```bash
git clone https://github.com/esaCodeBJ/odoo-16-template.git
```

> Note that you only need to run this command once

## Running the system


You have to run this command only one time, for building the system an lauching it

```bash
docker-compose up -d --build
```


To launch the system, in the project directory, just do :

```bash
docker-compose start
```

To stop the system, in the project directory, just do :

```bash
docker-compose stop
```

To delete all the created containers do :

```bash
docker-compose down
```

To delete all the created containers, volumes and images do

```bash
docker-compose down -v --rm all
```

# Author

* [Expédit Sourou ALAGBE](https://github.com/esaCodeBJ)