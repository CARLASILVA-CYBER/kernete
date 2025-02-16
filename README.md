O ConfigMap é um conjunto de configurações que podem ser usadas por aplicações dentro do Kubernetes.

Para editar directament no meu terminal, ConfigMap ou Secret depois de criado

kubectl edit configmap minha-config
kubectl edit secret minha-secret


Para remover ou eliminar ConfigMap ou Secret

kubectl delete configmap minha-config
kubectl delete secret minha-secret



É interessante perceber como ligar as variáveis a um Pod para que a aplicação leia os valores dinamicamente, em vez de os embutir no código.
