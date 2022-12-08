### Preparation

Place the certs in data/nginx/certs

Edit data/nginx/jenkins-gitlab.conf: change the domains and the names of the cert and key files

In addtion to that, the correct domain names must be edited in the docker-compose.yml


    docker-compose up -d


You should get an nginx server that provides 2 https pages, one for gitlab and one for jenkins.

To be continued...