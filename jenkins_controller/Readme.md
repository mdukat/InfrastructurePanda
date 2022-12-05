# Build
```
docker build -t jenkins-custom:latest .
```

# Run
```
docker run --name jenkins -p 8880:8080 -p 50000:50000 -d -v /home/panda/InfrastructurePanda/jenkins_controller/casc.yml:/usr/share/jenkins/ref/casc.yml -v /home/panda/jenkins:/var/jenkins_home jenkins-custom
```
