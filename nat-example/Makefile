help:
	@echo "Usage: make [target]"
	@echo ""
	@echo "Targets:"
	@echo "  help   Show this help message"
	@echo "  build  Build the docker image"
	@echo "  up     Start the docker container"
	@echo "  down   Stop the docker container"
	@echo ""

build:
	@echo "Building..."
	@docker build --tag linux-node .

up:
	@echo "Starting..."
	@docker compose up --detach

down:
	@echo "Stopping..."
	@docker compose down -v