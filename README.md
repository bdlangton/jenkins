# How to run Jenkins

This should keep the same volume even if the container stops, restarts or gets
removed.

docker run -d --restart always -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home
jenkins/jenkins:lts
