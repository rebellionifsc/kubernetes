all: delete create


delete:
	kubectl delete -f Deployment.yaml
	kubectl delete -f Service.yaml
	kubectl delete -f Configmap.yaml


create:
	kubectl create -f Configmap.yaml
	kubectl create -f Service.yaml
	kubectl create -f Deployment.yaml
