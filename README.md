# dicomweb-pacs
DICOM PACS powered by Go and React

Backend app: [dicomweb-pacs-api](https://github.com/harmakit/dicomweb-pacs-api)  
Frontend app: [dicomweb-pacs-front](https://github.com/harmakit/dicomweb-pacs-front)  

---

## Installation

### Get Docker Compose
Find out how to install it for your machine on [official Docker page](https://docs.docker.com/compose/install)

### Get project files

```shell
$ git clone https://github.com/harmakit/dicomweb-pacs.git
$ cd dicomweb-pacs
$ git submodule update --init
```  

### Run Docker Compose containers
```shell  
$ docker compose up
```  

### Run database migrations

``` shell 
$ docker compose -f docker/docker-compose.yml exec api ./main migrate
```  

---

## Start using the app
Open [http://localhost:49200/](http://localhost:49200/) to access the app

---  

## To receive updates run
```shell
$ git submodule update --remote --merge
```
