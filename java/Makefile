build:
	@docker build -t java-sandbox .

run:
	@docker run --mount src=`pwd`,target=/app,type=bind -it java-sandbox sh -c 'cd /app && javac Main.java && java Main'
