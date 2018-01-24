CURRENT_PATH := $(shell pwd)
NAME := $(shell basename ${CURRENT_PATH})

all:
	docker build . -t duckzbug/${NAME}

run:
	docker run duckzbug/${NAME}

push:
	docker push duckzbug/${NAME}
