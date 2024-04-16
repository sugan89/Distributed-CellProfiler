user = suganyasivaguru
project = distributed-cellprofiler
tag = 2.1.0_4.2.4_cellpose

.DEFAULT_GOAL: build
build:
	docker build -t $(user)/$(project):$(tag) . 
	docker login -u $(user)
	docker push $(user)/$(project):$(tag)
	echo "Your new docker registry is ready at: $(user)/$(project):$(tag)"

