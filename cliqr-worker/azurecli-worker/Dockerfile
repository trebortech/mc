FROM cliqr/worker:latest
MAINTAINER Robert Booth "rbooth@saltstack.com"

RUN curl --silent --location https://rpm.nodesource.com/setup_4.x | bash -
RUN yum install -y nodejs python-pip
RUN npm install azure-cli -g
RUN azure config mode arm
