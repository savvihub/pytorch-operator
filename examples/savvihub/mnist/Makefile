create:
	kubectl create -f yaml/namespace.yaml
	kubectl create -f yaml/pytorch_operator.yaml

delete:
	kubectl delete -f yaml/pytorch_operator.yaml
	kubectl delete -f yaml/namespace.yaml

reset: delete create