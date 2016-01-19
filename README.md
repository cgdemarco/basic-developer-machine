# km77.com

## Pasos Base (arrancar la aplicación)

Ir al directorio base del proyecto usando una consola

```
cp Vagrantfile.dist Vagrantfile

vagrant up
```

Una vez terminado (la primera vez tarda un buen rato) se puede abrir en un navegador este enlace: [10.0.0.200](http://10.0.0.200)


### Entrar en la máquina
```
vagrant ssh
cd /vagrant/
```

### Antes del commit (desde la consola interna de la máquina)
```
composer precommit
```


### ¿Cómo cierro?
```
vagrant halt
```
