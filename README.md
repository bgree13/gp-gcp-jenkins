# gp-gcp-jenkins
Deploy Jenkins image to GCP using Terraform and Puppet

This repository assumes that you have deployed the Administrative containers using  https://github.com/Orasi/gp-cicd-kickstart
The docker-compose.yml file will deploy the following containers:

* [Jenkins](https://hub.docker.com/r/jenkins/jenkins)
* [Artifactory](https://github.com/jfrog/artifactory-docker-examples/tree/master/docker-compose)
* [Puppet](https://github.com/puppetlabs/puppet-in-docker-examples)
* [Gogs](https://hub.docker.com/r/gogs/gogs)


#### 1. You should then be able to access each of the applications at the URL's below on any modern browser

* [Jenkins](http://localhost:8080)
* [Artifactory](http://localhost:8081)
* [Puppet](http://localhost:8102)
* [Gogs](http://localhost:3000)
