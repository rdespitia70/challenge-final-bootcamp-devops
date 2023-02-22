# challenge-final-bootcamp-devops

1. Inicialmente ejecutamos todo en local para validar que todo funcione, para posterior continuar con los otros

Construyendo imagenes:
![](challenge-final-rdem/docs/docs-evidence/build-images-docker-local.png)

Imagenes construidas:
![](challenge-final-rdem/docs/docs-evidence/imagenes-construidas.png)

Subida de imagenes a dockerhub
![](challenge-final-rdem/docs/docs-evidence/imagenes-en-dockerhub.png)

Docker push:
![](challenge-final-rdem/docs/docs-evidence/docker-push.png)

Historial de los comandos ejecutados:
```
 5968  docker tag ms-frontend:1.0 rdespitia70/ms-frontend:1.0
 5969  docker tag ms-products:1.0 rdespitia70/ms-products:1.0
 5970  docker tag ms-shopping-cart:1.0 rdespitia70/ms-shopping-cart:1.0
 5978  docker push rdespitia70/ms-frontend:1.0
 5979  docker push rdespitia70/ms-products:1.0
 5980  docker push rdespitia70/ms-shopping-cart:1.0
```

Lanzamos ahora el docker run y hacemos pruebas:
Docker run:
![](challenge-final-rdem/docs/docs-evidence/docker-run.png)

Pruebas:
![](challenge-final-rdem/docs/docs-evidence/test1.png)

2. Construccion de kubernetes template

template1.yaml
![](challenge-final-rdem/docs/docs-evidence/template1.png)

```
kubectl apply -f template1.yaml
```