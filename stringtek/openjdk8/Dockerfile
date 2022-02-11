FROM openjdk:8
MAINTAINER stringtek
WORKDIR /app
RUN ["wget","https://raw.githubusercontent.com/eficode/wait-for/master/wait-for"]
COPY --from=hengyunabc/arthas:latest /opt/arthas /opt/arthas
