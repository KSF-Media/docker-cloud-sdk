FROM google/cloud-sdk:latest

# Install gettext, contains the envsubst command, for env vars substitution
# Also install python3 and Jinja2, needed for Kubernetes templating
# Aswell as libyaml for pyaml and jinja2-cli for cli jinka tools
RUN apt-get install -y gettext python3-pip libyaml-dev
RUN pip3 install Jinja2
RUN pip3 install PyYAML
RUN pip3 install jinja2-cli
