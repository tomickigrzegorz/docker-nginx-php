Very fast way to run php in nginx environment without installing xampp. I use docker-compose.

### The first thing
Install the Docker manual can be found here ->
[Docker](https://www.docker.com/get-started).
Linux users must also install Docker Compose separately.

### Initialization

Before the first use, clone this repository and install node dependencies:

```
yarn
``` 

or 

```
npm install
```

### How to start the process of building the environment
In the created folder there is docker-compose.yml
Start the console and ...
```
$ docker-compose up 
```
All dependencies will be downloaded - nginx:latest and php:fpm

If you want to stop docker-compose
```
$ docker-compose down
```

### How to run the php code

Place your code in the "code" folder and go to address localhost:8080
