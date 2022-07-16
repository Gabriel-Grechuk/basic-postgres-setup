# Basic Prosgres Setup

## Required packages
* `docker`
* `docker compose`

## Usage
### To start the postgres
Clone the repo and run the script `./run.sh`
``` shell
$ git clone https://github.com/Gabriel-Grechuk/basic-postgres-setup.git
$ cd basic-postgres-setup
$ ./run.sh
```
or, if it requires permissions
``` shell
$ sudo ./run.sh
```

### Stop the docker instance
``` shell
$ ./stop.sh 
```
or
``` shell
$ sudo ./stop.sh
```

### To remove the docker image.
``` shell
$ ./remove.sh
```
or
``` shell
$ sudo ./remove.sh
```

