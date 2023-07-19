
# Orders-service

Se realiza el build de la aplicacion con maven
luego se construye el container image y realiza push al ECR

Se necesita la creacion de secrets 

cat ~/.kube/config | base64   copiamos el stdout y lo  guardamos como KUBE_CONFIG_DATA  

# Secrets: 

- AWS_ACCESS_KEY_ID_DESA
- AWS_SECRET_ACCESS_KEY_DESA
- AWS_SESSION_TOKEN_DESA

# Variables git

- CLUSTER_NAME

Estos los uso en Testing/Desarrollo para deploy contra el AWS de GROLAND

En Producción usamos los secrets de Ignacio Greco y levantamos en ese otro LAB??
