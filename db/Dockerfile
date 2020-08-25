FROM ubuntu

RUN apt-get update

# install mongoDB

RUN apt-key  adv --keyserver hkp://keyserver.ubuntu.com:80 --recv D68FA50FEA312927

RUN echo "deb https://repo.mongodb.org/apt/ubuntu xenial/mongodb-org/3.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.2.list

RUN apt-get update

RUN apt-get install -y mongodb-10gen

RUN mkdir -p /data/db

EXPOSE 27017

CMD ["--port 27017"]
