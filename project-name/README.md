wget https://github.com/wardviaene/jenkins-course/blob/master/scripts/install_jenkins.sh



bash install_jenkins.sh

docker run -p 8080:8080 -p 50005:50005   -d --name jenkins_1234 jenkins/jenkins:lts
docker run  jenkins/jenkins:lts
<!-- docker run -p 8080:8080 -p 50000:50000 -v /var/jenkins_home:/var/jenkins_home -d --name jenkins jenkins/jenkins:lts -->
docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts
