### Helm Lab - ITI - DevOps - Smart Village
###### by Hadi.Al.Atlly@gmail.com

#### Description

- Helm3 Hands On where custom chart 'App/app-chart' is used to deploy the app as a package
- and this is done by jenkins mutibranch pipeline
- jenkins is installed useing the official chart after some small modifications
- jenkins slave is based on a custom made docker image
  **'hadilotfy/jenkins-ubuntu-slave:v3'**
- the slave pod has helm installed on it, docker (which is connected to its worker node docker.sock)

#### Technologies Used:

* Helm
* Jenkins
* Git, GitHub
* Bash scripting
* Nginx Web Server
* Docker, DockerHub
* Kubernetes (Minikube)

#### File structure:

![Alt text](Screenshots/file-tree.png?raw=true "File Tree")
