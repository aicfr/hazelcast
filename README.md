# Hazelcast 2.5.1 + mancenter
## lancement de l'image

```cmd
docker run -d -p 5701:5701 -p 8080:8080 -p 9001:9001 aicfr/hazelcast
```

## Description des ports

* 5701 : Port du nœud Hazelcast
* 8080 : Management Center (admin/admin)
* 9001 : Console d'administration de Supervisord