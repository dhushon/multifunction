Critical step... 
GOOS=linux GOARCH=amd64 CGO_ENABLED=0 go build -o main main.go
zip receiver.zip main
then upload via console or serverless framework

caution: have to make sure that console lambda function runtime handler matches executable!
