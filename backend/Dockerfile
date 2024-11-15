# backend/Dockerfile

FROM golang:1.20

WORKDIR /app

RUN go install github.com/githubnemo/CompileDaemon@latest

COPY go.mod ./

RUN go mod tidy

COPY go.sum ./

RUN go mod download

COPY . .

EXPOSE 8080

CMD ["CompileDaemon", "--build=go build -o /app/server main.go", "--command=/app/server"]
