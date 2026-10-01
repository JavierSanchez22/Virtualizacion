# Actividad: Configuración de un Servicio en Kubernetes

## 1. Captura del Navegador (Servicio Nginx)

![Captura de Nginx](images/nginx-browser.png)

## 2. Salida del comando `kubectl get svc`

```bash
NAME            TYPE        CLUSTER-IP      EXTERNAL-IP   PORT(S)        AGE
kubernetes      ClusterIP   10.96.0.1       <none>        443/TCP        16m
nginx-service   NodePort    10.111.252.36   <none>        80:31481/TCP   5m20s
```
