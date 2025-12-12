FROM ubuntu:latest

RUN apt-get update -y

RUN apt-get install git -y

WORKDIR ./app

COPY ./app

EXPOSE 80

CMD ["bash"]


