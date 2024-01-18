## Si le da más dinero a la empresa, entonces invierte más en publicidad en ese plan 

Trabajamos como analista para el operador de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de los planes genera más ingresos para poder ajustar el presupuesto de publicidad.

Realizamos un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Son datos de 500 clientes de Megaline conformado por: quiénes son los clientes, de dónde son, qué tarifa usan, así como la cantidad de llamadas que hicieron y los mensajes de texto que enviaron, todo en el 2018. 

Nuestro trabajo fue analizar, el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos.

## Tabla de conteidos del proyecto

* [1 Incialización.](#Capítulo_1)
    * [1.1 Cargar los datos](#Sección_1_1)
* [2 Exploración de bases de datos](#Capítulo_2)
    * [2.1 Planes](#Sección_2_1)
        * [2.1.1 Corregir los datos](#Sección_2_1_1)
        * [2.1.2 Enriquecer los Datos](#Sección_2_1_2)
    * [2.2 Usuarios](#Sección_2_2)
        * [2.2.1 Corregir los datos](#Sección_2_2_1)
        * [2.2.2 Enriquecer los Datos](#Sección_2_2_2)        
    * [2.3 Llamadas](#Sección_2_3)
        * [2.2.1 Corregir los datos](#Sección_2_3_1)
        * [2.2.2 Enriquecer los Datos](#Sección_2_3_2)
    * [2.4 Mensajes](#Sección_2_4)
        * [2.2.1 Corregir los datos](#Sección_2_4_1)
        * [2.2.2 Enriquecer los Datos](#Sección_2_4_2)        
    * [2.5 Internet](#Sección_2_5)
        * [2.2.1 Corregir los datos](#Sección_2_5_1)
        * [2.2.2 Enriquecer los Datos](#Sección_2_5_2)
    * [2.6 Estudiar las condiciones de los planes](#Sección_2_6)
    * [2.7 Unir bases de datos](#Sección_2_7)
* [3 Estudiando el comportamiento del usuario](#Capítulo_3)
    * [3.1 LLamadas](#Sección_3_1)
    * [3.2 Mensajes](#Sección_3_2)
    * [3.3 Internet](#Sección_3_3)
    * [3.4 Patrones de Consumo](#Sección_3_4)
    * [3.5 Prueba de hipotesis nula](#Sección_3_5)
* [4 Conclusión general](#Capítulo_4)


## Paqueteria Utilizada

`pandas`
`numpy`
`math` 
`matplotlib.pyplot`
`scipy - stats` 

## Resultados
La información anterior nos ayudo a ver que el plan que se debería darle mayor publiciad es el surf, ya que aunque es un paquete de costo pequeño (20 dólares), los usarios realmente terminan consumiendo más allá de su plan y de una manera desmedida, habiendo quién sobrepase hasta los 200 dólares, tal como lo pudimos observar en las boxplot del gasto por plan.


