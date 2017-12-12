# Lambeth Data Analysis

This project was the culmination of geting annoyed with a local council, and a desire to play with a number of Python data science libraries and visualisation frameworks.

## Getting Started

This project makes use of the [opinionated Docker images provided by Jupyter](https://github.com/jupyter/docker-stacks).  Specifically the data science notebook. 

Start the notebook by simply running.

```
docker compose up
```

or alternatively

```
#For Windows using a MinGW shell
winpty docker run -it --rm -p 8888:8888 -v /$PWD:/home/jovyan jupyter/datascience-notebook

#For Mac/Linux
docker run -it --rm -p 8888:8888 -v $PWD:/home/jovyan jupyter/datascience-notebook
```

There may be a cople of additional libraries that are required in addition to the datascience-notebook.  These can be installed using a terminal within the notebook using conda as a package manager.

### Prerequisites

* Docker
* Docker Compose

## Built With

* [Docker/Docker Compose](https://www.docker.com/) - Used for managing the environment. 
* [Jupyter](http://jupyter.org/) - Notebook server.  The Jupyter docker image used contains loads of great python resources

## Acknowledgments

* Some data was acquired from the [FixMyStreet site](https://www.fixmystreet.com/)