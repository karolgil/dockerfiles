FROM lachlanevenson/k8s-kubectl

ENTRYPOINT []
CMD ["sh", "-c", "kubectl proxy -p 8000 --address=$(hostname -i) --disable-filter=true --reject-methods='POST,PUT,PATCH,DELETE'"]
