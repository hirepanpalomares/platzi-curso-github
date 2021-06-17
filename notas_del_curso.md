# ¿Por qué usar un sistema de control de versiones como Git?

Git es un sistema de control de versiones donde se van guardando los cambios que se realizan a un archivo o conjunto de archivos, que especifica donde, cuando y porque se cambio cierta parte de los archivos. Un archivo de texto plano es un archivo donde no se le puede agregar negritas, imagenas, arrastrar archivos etc. Comandos de GitHub:

### git init
Inicializa repositorio

### git add *file*
Agrega archivos al repositorio

### git add .
Agrega absolutamente todos los archivos en los que realizaste los cambios

### git commit -m "mensaje"
Agrega los cambios que has realizado y lo manda al sistema de control de versiones

### git status
Con este ves el estado de tu reporsitorio, cuales archivos han cambiado

### git show
Muestra todos los cambios historicos hechos, incluyendo cuales han sido las lineas de cualquier archivo que hayan cambiado, cuando y quien los hiso

### git log archivo.txt
Historial de cambios de un archivo


# Instalacion de Windows:
* Configuracion de openSSL
* Emulador de terminal de linux
* Instalar Git
* Instalar Git bash

#### Dato curioso: Cuando entras a una pagina segura "https" lo que se hace es usar openSSL(solo Mac y Linux) de linux para intercambiar unas llaves de criptografia y no solo contrasenas par aque toda la conexion este completamente cifrada.

#### MinGW64: Emulador de la consola de linux en Windows

# Instalacion en Mac

* Solo instalar Git desde el webpage

* Mac esta basado en un kernel que se llama BSD
* Linux está basado en Linux


# Instalacion en Linux

* con gestor de paquetes *apt-get*
```bash
sudo apt-get update
sudo apt-get install git
```

# Editores de código, archivos binarios y de texto plano
* **Archivo de Texto (.txt)**  Texto plano normal y sin nada especial. Lo vemos igual sin importar dónde lo abramos, ya sea con el bloc de notas o con editores de texto avanzados.
* **Archivos RTF (.rtf)** Podemos guardar texto con diferentes tamaños, estilos y colores. Pero si lo abrimos desde un editor de código, vamos a ver que es mucho más complejo que solo el texto plano. Esto es porque debe guardar todos los estilos del texto y, para esto, usa un código especial un poco difícil de entender y muy diferente a los textos con estilos especiales al que estamos acostumbrados.
* **Archivos de Word (.docx)** Podemos guardar imágenes y texto con diferentes tamaños, estilos o colores. Al abrirlo desde un editor de código podemos ver que es código binario, muy difícil de entender y muy diferente al texto al que estamos acostumbrados. Esto es porque Word está optimizado para entender este código especial y representarlo gráficamente.


# Configurar git en tu repositorio local

Con ```git config```  
```git config --list``` son tus configuraciones locales por defecto de tu git

Con --global configuras las variables globales
```
git config --global user.email "tu@email.com"
git config --global user.name "Tu Nombre"
```

Despues de configurar el usuario y nombre ya se puede hacer este commit


