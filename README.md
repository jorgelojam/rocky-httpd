# VirtualBox Rocky 8

En el caso de que exista ya una imagen descargada verificar:

```console
vagrant box list
```

Si existe puede eliminar de la siguiente manera:

```console
vagrant box  remove rockylinux/8 --box-version 7.0.0
```

Para funcionar debe ejecutar lo siguiente

```console
vagrant box add box-metadata.json
```
