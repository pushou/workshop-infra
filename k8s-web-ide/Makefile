VERSION=v1.0.2
all: build
build:
	docker build --pull -t luxas/k8s-web-ide:$(VERSION) .

push: build
	docker push luxas/k8s-web-ide:$(VERSION)
