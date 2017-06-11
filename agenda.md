
Docker Workshop 

Docker is an operating system (OS) level virtualization technology and provides a format to express applicable dependencies. Since the OS is shared, system resource usage is much more efficient that Virtual Machines (VM). Once the application is isolated, fine grained resource allocation is made using OS primitives. The application is packaged as a Docker image, which is instantiated as a container on execution.

The workshop is conceptualized with the intent to highlight "containers as the building block of immutable infrastructure".

The agenda of the HANDS-ON workshop focusses on:

Architecture
* Docker Architecture and what it enables 
* Control flow between dockerd, containerd 
* Docker on Windows 2016 server

Registry 
* Docker Registry architecture 
* Work with Dockerhub registry
* Work with Local Docker registry

Daemon
* Configuring 'dockerd'
* Configuring 'containerd'
* Configuring Local Docker Registry

Dockerfile 
* Dockerfile syntax, do's and dont's 
* Windows Dockerfile 
* Best practices for writing Dockerfile 
* Docker Multi-Stage Builds
* Builder pattern vs* Multi-stage builds

Images
* What's in a Docker image
* Inspecting images and layers
* Testing Docker Images 

Meta data
* Docker object labels
* Custom metadata 

Docker Networking
* Overlay networking 
* Key important concepts in Docker networking design
* Common issues and pitfalls
* How to troubleshoot

Powershell
* How to use Powershell with Docker 
* Inspection and Logging

Service Management 
* systemd based container management 
* Daemon options
* usage of HTTP/HTTPS proxy 

Linking
* Linking Containers
* Ambassador Pattern 
* Discussion about #3120

Docker on Windows
* Docker and NanoServers
* Docker and Windows Server Core
* Hyper-V isolation levels
* Powershell script code

Data Volume
* Data Volume Containers 
* Containers and Filesystems 
* Using Device Mapper Storage Driver 

Security
* Securing Docker using TLS 
* Setting up secure Local Registry 

Debugging
* Debugging and Troubleshooting Containers
* Approaches & Practices
* Tools


Bonus 
* Architecture highlights of the Moby project
* From Docker to Moby Project and Back
* LinuxKit 
* Infrakit 
* Containerd revisted 
* Understand what is the actual opportunity with containers



What will NOT be covered 
* the history of docker* 
* basics of shell scripting, powershell* 
* basics of JSON, golang templates.


Please bring a laptop 
* that has atleast 50 GB of free disk space* 
* have administrator rights on the machine 
* properly functioning WLAN NIC 
* have applied the latest patches and upgrades 
* be able to run docker natively (no VM business)

