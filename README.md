#   Fuente Regulable 

Una fuente regulable simple, con el Circuito Integrado LM317, que está diseñado para un rango de 1,25V - 28V.

El proyecto fue desarrollado en KiCAD.

Por el momento solo está el esquema, en los proximos días se agregará el diseño de la PCB.

#   Diseño

El diseño de esta fuente está basado en el punto 9.2 de la hoja de datos https://www.ti.com/lit/ds/symlink/lm317.pdf con algunas modificaciones:

-   Se agregó un LED en la entrada para señalización
-   Existe un punto en la entrada para alimentación de otros dispositivos como instrumentos de medición.

Hay que tener en cuenta, que el disipador para el LM317 no se encuentra en el esquema, pero es imperativo colocar uno, ya que al usar toda su potencia, puede llegar a calentarse bastante.