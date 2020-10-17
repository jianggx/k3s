kubectl create -f namespace.yml
kubectl create -f service.yml
kubectl create -f deployment.yml

注： 默认的docker hub连接太差，导致镜像下载失败，可利用国内镜像解决，本处使用hub-mirror.c.163.com/library/nginx 