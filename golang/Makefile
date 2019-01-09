build:
	@docker build -t golang-sandbox .

run:
	@docker run --mount src=`pwd`,target=/app,type=bind -it golang-sandbox go run /app/main.go
