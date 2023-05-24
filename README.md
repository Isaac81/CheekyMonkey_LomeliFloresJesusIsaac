# Universidad de Guadalajara - Centro Universitario de Ciencias Exactas e Ingenierías


## Departamento de ciencias computacionales
Computación tolerante a fallas - Sección D06
Profesor: *López Franco Michel Emanuel*
Alumno: *Lomelí Flores Jesús Isaac*

## Cheeky Monkey


### Introducción
<p align="justify">
Hasta el momento se han desarrollado algunos servicios de aplicaciones implementando tecnologías y herramientas que son de gran utilidad para desarrollar sistemas robustos tolerantes a fallas, sin embargo no se han propuesto a prueba en ambientes hostiles en los que se generen fallos de manera caótica, es por esta razón por la cual se desarrolla la presente práctica, para poder comprobar el funcionamiento de estas en un entorno como el descrito.
</p>

### Desarrollo

<p align="justify">
  Lo primero que se realizo fue la clonación del repositorio de cheeky monkey, seguido de la instalación de python en la version 3.8.9. Una vez instalado python y copiado el repositorio se procedió a instalar los requerimientos.
</p>

![Instalación de requerimientos](/Imagenes/Screenshot_106.png)

<p align="justify">
  Posteriormente se ejecutó el comando *kubectl get ns* para obtener los pods que serán ignorados por el juego para no destruirlos.
</p>

![Filtro de pods](/Imagenes/Screenshot_107.png)

<p align="justify">
  Una vez que se identifican cuales serán excluidos se ejecuta el juego detectando en este caso 20 pods.
</p>

![Ejecución del juego](/Imagenes/Screenshot_108.png)

<p align="justify">
  Cuando se comienzan a destruir cajas en el juego se muestra en la esquina superior izquierda el pod que ha sido destruido.
</p>

![Demostración](/Imagenes/Screenshot_110.png)

<p align="justify">
  Se puede verificar el estado de los pods para observar el caos generado con el juego, asi como la consola del propio juego.
</p>

![Verificación](/Imagenes/Screenshot_111.png)

![Verificación](/Imagenes/Screenshot_112.png)


## Conclusión

<p align="justify">
  Gracias a esta actividad se pudieron comprobar algunas cosas hechas en actividades anteriores, pues al poder someter a los pods a un ambiente hostil en el que se ocasionan fallas caóticamente se ponen a pruebas las tecnologías implementadas con anterioridad para crear tolerancia a fallas. Se aprecio el buen funcionamiento de dichas tecnologías para crear resiliencia y mantener los servicios de las aplicaciones funcionando correctamente.
</p>
