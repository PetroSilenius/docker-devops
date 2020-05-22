FROM ubuntu

RUN apt-get update && apt-get install -y curl
WORKDIR /mydir
COPY search.sh .
CMD ["./search.sh"]
