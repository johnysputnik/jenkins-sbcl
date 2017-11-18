# jenkins-sbcl
A Jenkins docker build with sbcl and quicklisp

~~~~
docker build -t jc/jenkins .

docker run -d -p 8080:8080 -p 50000:50000 --volume=$HOME/docker/jenkins_home:/var/jenkins_home jc/jenkins
~~~~
