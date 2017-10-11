FROM google/cloud-sdk:latest

# Install gettext, contains the envsubst command, for env vars substitution
# Also install python3 and Jinja2, needed for Kubernetes templating
RUN apt-get install -y gettext python3-pip
RUN pip3 install Jinja2
