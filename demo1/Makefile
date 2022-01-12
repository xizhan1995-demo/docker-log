

image_name:=demo1

run: | image rm
	docker run -dit --rm --name demo $(image_name)
rm:
	docker rm -f demo
image:
	@echo 构建镜像
	docker build -t $(image_name) .

