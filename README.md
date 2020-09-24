

### Instalar Visual Code en Debian 10
Instalar dependencias.
```sh
$ sudo apt install software-properties-common apt-transport-https
```
Descargamos la llave GPG del repositorio.
```sh
sudo wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
```

Introducimos el repositorio correspondiente
```sh
$ sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
```
Actualizamos los paquetes
```sh
$ sudo apt update
```
Instalamos Visual Code.
```sh
$ sudo apt-get install code
```

