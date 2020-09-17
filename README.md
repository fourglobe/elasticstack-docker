# Elastic stack with docker and empty app.

This repository is before start develop an application.

## Folder Tree
```
.
├── README.md
├── docker-compose.yml
└── elasticstack
    ├── elasticsearch
    │   ├── Dockerfile
    │   └── config
    │       ├── elasticsearch.yml
    │       ├── jvm.options
    │       └── log4j2.properties
    ├── filebeat
    │   ├── Dockerfile
    │   └── filebeat.yml
    └── kibana
        ├── Dockerfile
        └── config
            └── kibana.yml
```

## If Django

you want to develop Django application with elasticsearch and kibana or some product from elastic or not.

### Fist creates a develop environment.

install pipenv, virtualenv, anaconda ... etc. this is not required. but You have to install it for your health.

install pipenv

OSX
```
brew install pipenv
```

done.

Linux
```
apt install pipenv
```
... or ... Um.... 

Windows
```
Good Luck!
```

### Create Python virtual environment. (pipenv)

```
pipenv --python 3.8 # python 3.8
```

### Run virtual environment.

```
pipenv shell # very simple command. so I love pipenv
```

### Create django project

```
pipenv install django
```

`pipenv install django` command is done. you will check file Pipfile or Pipfile.lock

enjoy project

TODO: Golang or Java? or Node? or some SSR?

I don't know...