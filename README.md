# ConjuntoMandelbrot
El objetivo de la práctica es modificar el programa de cálculo del conjunto de
Mandelbrot para dividir el cálculo del mismo entre ‘n’ procesos. Para ello se pide:
Añadir un spinner en el programa para configurar el número de trabajadores
que se encargarán de realizar el cálculo del conjunto de Mandelbrot.
 Modificar el comportamiento del método pintaMandelbrot para que:
 Reparta el trabajo entre los ‘n’ procesos. Este reparto se recomienda que
sea en horizontal o en vertical, es decir, divida panel.getWith() o
panel.getHeitght() entre el número de procesos.
 Cree ‘n’ procesos, indicándole a cada uno todos los valores necesarios
para el cálculo. Entre estos valores se encontrarán: los valores de x1, y1,
x2, y2, para conocer qué parte del conjunto se está pintando, los valores
coordenadas de pantalla que le corresponde calcular, etc.
 Lance la ejecución de los ‘n’ procesos.
 Espere a que los procesos terminen.
 Pinte en el panel los valores calculados por todos los procesos.
 Crear un proceso que se encargue de pintar una parte del conjunto que le
indicará el programa principal cuando lo cree.
El link es: https://github.com/SANTiiAL67/ConjuntoMandelbrot
