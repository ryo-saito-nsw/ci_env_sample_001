FROM gitlab/gitlab-runner:ubuntu-139fb059

RUN apt-get update && apt-get install -y g++ wget unzip
RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

