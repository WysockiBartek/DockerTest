FROM golang:1.17
WORKDIR /app
RUN mkdir /app/files
COPY . /app
#RUN go get -d -v ./...
#RUN go install -v ./...

CMD ["go", "run", "quest2.go"]
