build:
	@docker build -t python-sandbox .

run:
	@docker run --mount src=`pwd`,target=/app,type=bind -it python-sandbox python app/main.py
