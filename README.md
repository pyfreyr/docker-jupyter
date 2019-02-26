Docker Image for Jupyter Notebook https://jupyter.org/


## Supported tags and respective `Dockerfile` links

- `3.6`, `3.6-bionic` ([3.6/bionic/Dockerfile](https://github.com/pyfreyr/docker-jupyter/blob/master/3.6/bionic/Dockerfile))
- `3.7`, `3.7-bionic` ([3.6/bionic/Dockerfile](https://github.com/pyfreyr/docker-jupyter/blob/master/3.7/bionic/Dockerfile))

## How to use this image

    $ docker run -it -p 8888:8888 -v $PWD/notebooks:/notebooks pyfreyr/jupyter:3.6-bionic
