# SyTW2232-E18_aux
## Informe de práctica de Laboratorio #04. Ejercicios con el repositorio del proyecto

## Introducción

Antes de empezar a desarrollar código para el proyecto, vamos a realizar algunos ejercicios sobre el repositorio para aprender a trabajar en equipo. Para esto hemos creado un repositorio común para cada equipo en la organización de GitHub SyTW2223 al que hemos asignado un "Team" con perfil "Maintaner" con los miembros del equipo.

## Desarrollo
Los ejercicios a realizar van a ser 3:

### **2.1. Clonar el repositorio**

  Para realizar esta tarea debemos acceder a github y localizar el repositorio del grupo en SyTW223 en la dirección: ```https://github.com/SyTW2232/E??```, donde debe sustituir las ?? por el identificador de cada grupo. Una vez localizado el repositorio deberemos hacer clic en el boton de color verde con la palabra “code” y copiar la dirección ssh del repositorio. Luego abrimos una terminal que tenga git y ejecutamos el siguiente comando para clonar dicho repositorio:

```
$ git clone git@github.com:alu0101328447/SyTW2232-E18_aux.git
```

  Después de la ejecución del anterior comando aparecerá una copia del repositorio en la máquina local.

### **2.2. Ejercicios de merge entre ramas**

Para realizar pruebas de uso de ramas, haremos una serie de ejercicios:
* Listar las ramas existentes
* Crear una nueva rama: $ git branch nueva_rama
* Crear un fichero de prueba en la nueva rama y comprobar que solo se crea en esa rama:
* Guardar los cambios realizados en la rama y hacer commit:
* Realizar merge de las ramas que hemos creado

### **2.3. Pruebas con la aplicación bitnami**
  Para esta tarea clonaremos la aplicación de bitnami que se despliega en Azure, fuera del repositorio E?? y copiaremos el código en nuestra rama desarrollo para aplicar cambios. Haremos pruebas de modificaciones con ramas distintas cada uno de los miembros del equipo: 

* Modificamos algunos ficheros de código de la app desde la rama desarrollo y guardamos los cambios.
* Hacemos función de la rama desarrollo en la rama doc para tener los ficheros de código modificados previamente y añadiremos algunos comentarios a ciertas funciones.
* Por último hacemos una función de doc en la rama main, trayendo el código resultante comentado y realizamos un push al repositorio remoto.





