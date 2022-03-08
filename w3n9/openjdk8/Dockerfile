FROM openjdk:8
MAINTAINER w3n
WORKDIR /app
RUN ["wget","https://raw.githubusercontent.com/eficode/wait-for/master/wait-for"]
RUN ["chmod","+x","./wait-for"]
COPY ./skywalking-agent /opt/skywalking-agent
COPY --from=hengyunabc/arthas:latest /opt/arthas /opt/arthas
