FROM golang:alpine

RUN mkdir -p /app
WORKDIR /app

COPY . /app

ENTRYPOINT ["go"]
CMD ["run", "./main.go"]
