FROM java:8

MAINTAINER Yang Zheng <zhengyang4k@gmail.com>

WORKDIR /tmp

RUN wget -q -O gradle.zip https://services.gradle.org/distributions/gradle-2.6-bin.zip
RUN unzip gradle.zip -d /usr/share/
RUN mv /usr/share/gradle-* /usr/share/gradle
RUN ln -s /usr/share/gradle/bin/gradle /usr/bin/gradle
