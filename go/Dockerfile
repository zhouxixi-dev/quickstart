FROM gcr.io/distroless/base-debian12

RUN go get -d -v ./...
RUN go build -o quickstart

COPY ./go/quickstart /

EXPOSE 8000
ENTRYPOINT ["/quickstart"]
