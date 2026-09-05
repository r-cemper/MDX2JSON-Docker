## MDX2JSON in Docker
The PR for integration in Docker was ignored.   
This is a safe environment for testing and trying.
Some test data have been prepared.
### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory    
```
$ git clone https://github.com/r-cemper/MDX2JSON-Docker.git
```
To build and start the container run:  
```
$ docker compose up -d && docker compose logs -f
```
To open IRIS Terminal do:
```
$ docker-compose exec iris iris session iris
USER>
```
or using **iterm**
```
http://localhost:42773/iterm/
```
IRIS System Management Portal
```
http://localhost:42773/csp/sys/UtilHome.csp
```
### How to use it  
This presents OEX package [MDX2JSON](https://openexchange.intersystems.com/package/MDX2JSON) using the actual IPM module    
All user documentation is found there in the [original repo](https://github.com/intersystems-community/Cache-MDX2JSON/blob/master/README.md)  
