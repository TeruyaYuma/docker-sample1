FROM ubuntu:20.04
RUN apt-get update -y && \
    apt-get install -y nginx
ENV TESTENV="teruya"
CMD ["nginx", "-g", "daemon off;"]
