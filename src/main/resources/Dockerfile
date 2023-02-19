FROM sombralibre/gitclient AS gitclone

ARG url=https://github.com/dayangwx/hello-docker.git

ARG appName=hello-docker

RUN git clone $url

RUN cd $appName && ls -l

