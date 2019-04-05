# Docker_app
<p>Creating and Deploy a web app using docker and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.</p>

<h1>Docker</h1>-<br/>
Docker is an operating-system-level virtualization mainly intended for developers and sysadmins. Docker makes it easier to create<br/>
and deploy applications in an isolated environment. A Dockerfile is a script that contains collections of commands and instructions<br/> 
that will be automatically executed in sequence in the docker environment for building a new docker image.<br/>

Docker is a cutting-edge solution to this problem. It provides us with containers that have all the virtualization capabilities we<br/>
need, while also being more lightweight than the traditional virtual machines.<br/>


<h1>Docker Images</h1>-<br/>
Docker is based on the concept of building images which contain the necessary software and configuration for applications. We can also build distributable images that contain pre-configured software like an Apache server, Caching server, MySQL server, etc. We can share
our final image on the Docker HUB to make it accessible to everyone.

<h1>Docker Containers</h1>-<br/>
An image can be considered a class definition. We define its properties and behavior. Containers are instances created from this class.
We can create multiple instances of the same image. The docker ps command prints the list of containers running on the machine.


<h1>Docker Compose</h1>-<br/>
Using terminals and remembering commands is not very practical for creating application containers and getting started quickly. Docker Compose uses YAML files to configure and run containers. This means that we can ship our application Dockerfile to build the environment and use a docker-compose.yml to run the containers.

The first step is to install Docker Composer on our machine. Follow the instructions in the Docker documentation before proceeding with 
the following steps.

The docker-compose.yml file allows us to configure multiple services inside the same file, and specify after that if the image needs to
be built or if we can use a predefined image.

