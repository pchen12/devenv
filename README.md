# devenv

~/dev
    /repos
    /var - where applications should write data

Cheat sheets:
- https://github.com/wsargent/docker-cheat-sheet


eval $(docker-machine env)

// pin Jenkins version to 2.7.4 for stability
docker run -p 8080:8080 -p 50000:50000 -v $HOME/dev/var/jenkins_home:/var/jenkins_home jenkins:2.7.4

// a change to set Github SSH keys
