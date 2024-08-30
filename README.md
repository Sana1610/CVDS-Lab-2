# Lab 2
## Presentado por
Santiago Alberto Naranjo Abril
## Respuestas
- El parametro package en Maven hace referencia a una de las etapas del ciclo de vida
que recorre Maven en un programa y es el encargado de empaquetar el codigo fuente en un
archivo ejecutable como por ejemplo un .Jar
- $ mvn exec:java -Dexec.mainClass="edu.eci.cvds.App" es el comando que utilizamos para poder
ejecutar la mainClass desde la consola de comandos y le agregamos -Dexec.args para que reciba
un argumento, en nuestro caso usamos $ mvn exec:java -Dexec.mainClass="edu.eci.cvds.App" -Dexec.args="Santiago"
para que el programa nos salude, en el caso que sea un argumento compuesto dependiendo de
como este creado el codigo se modificara o no el comando utilizado
- En nuestro caso como todos nuestros objetos son figuras me parecio mas sencillo hacer
un simple factory aprovechando el uso del switch-case tal como lo dijo el enunciado del laboratorio
y realmente ninguna es mejor o peor ya que depende de las necesidades del programa, ya que este
era un programa de baja complejidad lo mejor era usar el patron mas sencillo de implementar
- Al momento de ejecutar sin parametros el codigo manda el msg "Parameter of type RegularShapeType is required."
- Al ejecutarlo con "qwerty" y "pentagon" dice que el "Parameter 'pentagon' is not a valid RegularShapeType"
en el caso del "qwery" es por que no esta definido dentro del programa mientras que en el caso de "pentagon"
falla por que el programa no esta teniendo en cuenta la entrada de mayusculas
- Al ejecutarlo con "Hexagon" el programa funciona correctamente y dice
"Successfully created a Hexagon with 6 sides."

