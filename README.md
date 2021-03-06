![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/mmiscool/fc-docker)

# FC-Docker Run FreeCAD in a docker and make it accessible via the web browser

Included in this package is a docker file that builds a FreeCAD environment that is accessible from the web browser. Rendering is done on the server side for everything.

# Building and running
To build and run this project clone this repository.
You must have docker installed. On Ubuntu use the following command
```sudo apt install docker-ce```
In the repository directory run the following script.
```./build-run.sh```

After that script is run you should be able to visit http://localhost/ too see the application. 
Running this script will also start up a Cloud9 IDE environment accessible at http://localhost:8181/ use "username" and "password" to log in to it. 
I use Cloud9 for my IDE as all development done on this project so far was done on a Chromebook!
Feel free to use it if you wish. If not don't worry about it. 


# external_dependencies
Right now there is an external_dependencies folder. Items in this folder are from other projects.
A build system that fetches these files from there source projects will be implemented.
Respect the licences included with the packages in the external_dependencies folder. 

# Contributing to this project. 
This project is release under AGPL-3.0 licence. If you wish to use the code any thing you do with it including server side management systems must be made open source under the same licence. This applies to any any one who is hosting cloud services to the general public. Any modifications made must be shared. 
https://www.gnu.org/licenses/agpl-3.0.en.html

Because I am not a perfect GPL fan boy and do wish to possibly monetize this project at some point and commercially licence it under a commercial licence. It is necessary to sign a Contributor License Agreement.

