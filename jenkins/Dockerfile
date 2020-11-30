# Author: Anil Saravade
# Copyright: Copyright (©) 2020. SwapStyle. All rights reserved.

FROM jenkins/jenkins
MAINTAINER swapsstyle
USER root
RUN apt-get update && apt-get -y install rsync git subversion wget zip unzip jq
RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
