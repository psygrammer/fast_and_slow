
help:
	@echo "make"
	@echo "    build-gpu"
	@echo "        build image(gpu)"
	@echo "    build-cpu"
	@echo "        build image(cpu)"
	@echo "    push-gpu"
	@echo "        push gpu image to repo"
	@echo "    push-cpu"
	@echo "        push cpu image to repo"

build-gpu :
	docker build -t psygrammer/fast_and_slow:tf2.2-gpu ./jupyter-lab-tf2.2-gpu

push-gpu :
	docker push psygrammer/fast_and_slow:tf2.2-gpu
