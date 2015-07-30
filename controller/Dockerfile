FROM debian:jessie
ADD static /static
COPY . /app
RUN chmod 777 /app
WORKDIR /app
EXPOSE 8080
ENTRYPOINT ["/app"]
