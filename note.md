docker-compose run --rm app bun create next-app --ts tmp\
		&& mv tmp/* . && mv tmp/.* .\
		&& rm -r tmp
