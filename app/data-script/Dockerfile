FROM alpine
WORKDIR /opt
COPY import.sh .
COPY mydatabase.sql .
RUN apk update 
RUN apk add mysql-client
CMD ["sh", "import.sh"]
