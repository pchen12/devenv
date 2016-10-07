# devenv

~/dev
    /repos
    /var - where applications should write data


docker run -p 8080:8080 -p 50000:50000 -v $HOME/dev/var/jenkins_home:/var/jenkins_home jenkins
