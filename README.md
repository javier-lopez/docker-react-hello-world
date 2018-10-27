About
-----

Sample react app featuring docker integration

Usage
-----

    #development
    $ ./setup.sh [docker-compose-file]

Access http://localhost:3000

Dependencies
------------

- [docker](https://www.docker.com/)
- [docker-compose](https://docs.docker.com/compose/)

Autogeneration
--------------

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

    $ docker run -it --rm --user "$(id -u):$(id -g)" \
      -v "${PWD}":/usr/src/app -w /usr/src/app \
      jlpz/create-react-app create-react-app docker-react-hello-world

And added:

- **docker-compose.yml**
- **setup.sh**
