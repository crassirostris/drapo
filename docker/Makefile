all: container push

container:
	sudo docker build ../src/web -t gcr.io/crassirostris-personal/drapo

push:
	sudo gcloud docker push gcr.io/crassirostris-personal/drapo
