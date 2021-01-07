# Pasos iniciales para entender git, sus ramas y su forma de trabajar básica

## Iniciando 
Primero vamos a crear un esquema de carpetas para entender y hacer un simil entre carpetas y ramas   una carpeta >> una rama


>>Inician cambios por la rama 1
Creamos esta línea en la rama 1
$$ git checkout-b rama-1

Cree la carpeta uno

En este momento el commit está en la rama-1 
vamos a fusionar la rama main con la rama-1
$ git commit
$ git checkout main
$ git merge rama-1


Me cambio a la rama main y hago estos cambios en la linea 20 de archivo README y vamos a hacer lo miso en la rama 1 en la misma linea para ver que pasa.
Hago cambios en la misma linea 20 pero en la rama-1

### Resultado:
VsCode me preguntó que debo hacer:
- Aceptarlos cambios de Main
- Aceptarlos cambios de rama-1
- Aceptar los dos cambios
- Otra opción que no la revisé que era compararlos cambios, pendiente para el proximo merge


Vamos a ver que pasa mientras tanto en la rama-1 que la he dejado pendiente
En el mismo arhivo en las mismas lineas del archivo pero en la rama main estoy haciendo estos cambios rama-1
en teoría estoy escribiendo en las mismas lineas de los resultados veamos una vez más



Imediatamente despues de hacer el merge sobre un mismo archivo con conflicto en lineas tengo dos opciones 
$ git merge --abort
y me quedo con el estado incial antes de merge 
o
$ git add .
para aceptar los cambios y proceder.
Por esta vez los aceptaré 



# Vamos a trabajar a tres bandas o con tres ramas, para ver.
