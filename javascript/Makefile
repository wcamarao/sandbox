build:
	@docker build -t javascript-sandbox .

run:
	@docker run --mount src=`pwd`,target=/app,type=bind -it javascript-sandbox node /app/main.js
