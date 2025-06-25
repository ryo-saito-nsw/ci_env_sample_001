FROM gitlab/gitlab-runner:ubuntu-139fb059

RUN apt update && apt install -y \
    wget curl unzip git g++ cmake lcov \
    g++-aarch64-linux-gnu qemu-user

RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

