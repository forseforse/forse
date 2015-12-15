# forse
A python/flask clone of [forse.herokuapp.com](http://forse.herokuapp.com)

## Run

`docker-compose up`

The web app listens to

`http://[docker-machine-ip]:5000`

To detect the docker-machine ip, just run

`docker-machine ip default`

## Run without docker

Create a python virtualenv and activate it

```
virtualenv forse-venv
cd forse-venv
source bin/activate
```

Clone this repo

`git clone git@github.com:forseforse/forse.git`

Install the dependencies

`pip install -r webapp/requirements.txt`

Run the webapp

`python webapp/forse.py`
