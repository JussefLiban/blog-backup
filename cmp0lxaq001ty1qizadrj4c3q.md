---
title: "SIMULACIONES DE EVACUACIÓN PARA EL ANÁLISIS DE LA SEGURIDAD EN EDIFICACIONES COMPLEJAS"
datePublished: 2026-05-11T02:53:13.996Z
cuid: cmp0lxaq001ty1qizadrj4c3q
slug: simulaciones-de-evacuaci-n-para-el-an-lisis-de-la-seguridad-en-edificaciones-complejas

---

A continuación les presento los resultados de diversas simulaciones de evacuación realizadas a una edificación muy compleja en la cual he usado el software Pathfinder. Este análisis es parte de mi proyecto de maestría para culminar el grado de Master en Ciencias de Ingeniería de Protección contra incendios en la Universidad de California (Calpoly).

Luego de varios meses trabajando este modelo para convertirlo en 3 dimensiones, he logrado correr satisfactoriamente diversas simulaciones que evalúan varias hipótesis. Ha sido un trabajo bastante complicado por la falta de experiencia trabajando simulaciones, sin embargo el logro ha sido entender mejor el proceso de trabajo y el comportamiento de los evacuantes en función de las hipótesis establecidas por los estudios vigentes, entre ellos el método hidráulico de la SFPE.

Esta edificación hipotética tiene las siguientes especificaciones:

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/kwrk1p.jpg align="center")

*   4 sótanos de estacionamiento con una capacidad de 600 autos en un área total 9000 m^2. El Aforo según NFPA 101 es 499 ocupantes, el cual representa el 10% de la ocupación total de la edificación.
    
*   1 sótano y 2 niveles superiores (piso 1 y 2), de un centro comercial compuesto de 254 tiendas dedicadas a la venta de artículos electrónicos y computadoras en un área total de 5700 m^2. El Aforo según NFPA 101 es 1698 ocupantes, el cual representa el 33% de la ocupación total de la edificación.
    
*   2 niveles (pisos 3 y 4) ocupados por un centro educativo en un área total de 3650 m^2 que incluyen un restaurante con vista al mar. El Aforo según NFPA 101 es 1389 ocupantes, el cual representa el 27% de la ocupación total de la edificación.
    
*   26 niveles de apartamentos residenciales (piso 5 al 30) compuesto de 16 unidades de vivienda por piso y un total de 416 viviendas (piso 5 y 30) en un área total de 26700 m^2. El Aforo según NFPA 101 es 1274 ocupantes, el cual representa el 25% de la ocupación total de la edificación.
    
*   1 nivel de área recreativa residencial (Piso 31) compuesto de un gimnasio, área de parrillas, sala de fiestas, etc. El Aforo según NFPA 101 es 283 ocupantes, el cual representa el 5% de la ocupación total de la edificación.
    

El total de ocupantes llegaría a 5143 y se dividen según se muestra en el siguiente gráfico.

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/k8hiur.jpg align="center")

Bajo estos parámetros, el diseño arquitectónico se hizo suponiendo el cumplimiento de todos los requisitos de la norma NFPA 101, que incluyen la implementación de 11 escaleras de evacuación que sirven a las diversas áreas y 11 salidas de escape directas a la vía pública, según los requisitos establecidos por la norma NFPA 101. Asimismo se estimó un tiempo de evacuación teórico de 15 minutos usando el método cálculo de Pauls.

### SIMULACIONES REALIZADAS

Se hicieron las siguientes simulaciones:

### Simulación 1:

La carga de ocupantes es el aforo establecido por la norma NFPA 101 en todos los niveles, se asume simultaneidad total. Los evacuantes evacúan por la salida que implica menor costo o esfuerzo, pero escogiendo sólo entre las salidas que se encuentran dentro de su entorno, sin pensar en rutas alternas complicadas.

Resultados del análisis:

Número de Ocupantes: 5143

Tiempo de Evacuación Total: 31 Minutos

Tiempo de Atasco Mayor: 29 Minutos

Distancia de Mayor Recorrido: 295 Metros

Se descubre que el cuello de botella se produce en la torres de vivienda y en particular en la escalera del sector este. Se observa que el tiempo de atasco y las distancias de recorrido son muy altas, razón por la cual se analiza la posibilidad de optimizar la elección de los ocupantes con respecto a la salida a tomarse, a fin de evitar atascos en las salidas más usadas.

### Simulación 2:

La carga de ocupantes es el aforo establecido por la norma NFPA 101 en todos los niveles, se asume simultaneidad total. Los evacuantes evacúan por la salida que implica menor costo o esfuerzo, sin limitar las decisiones sobre como escoger la forma más rápida de salir.

Resultados del análisis:

Número de Ocupantes: 5143

Tiempo de Evacuación Total: 31 Minutos

Tiempo de Atasco Mayor: 29 Minutos

Distancia de Mayor Recorrido: 353 Metros

Se observa que los resultados se mantienen pero la distancia de recorrido se incrementa aún más, esto como consecuencia de dejar que los ocupantes escojan libremente las salidas más alejadas como medio de acortar el tiempo de escape. Asimismo se observa que el cuello de botella se mantiene en la escalera del sector este.

Se descubre que el centro comercial evacua en aproximadamente 5 minutos, y el educativo en 9 minutos, y aparentemente éste último afecta el flujo de los evacuantes de los pisos superiores, ya que ambos usan escaleras comunes que sirven a ambos tipos de ocupantes. Esto haría que los ocupantes de las viviendas se demoren 25 minutos en evacuar las instalaciones y como conclusión aparente debería haberse diseñado escaleras exclusivas y especiales para los ocupantes de la zona residencial.

Para verificar si los ocupantes de los pisos más bajos están ralentizando la evacuación de los ocupantes de los pisos más altos, se procede a realizar dos simulaciones que reducen el número de ocupantes en los primeros pisos, la primera de ellas al 25% y la segunda de ellas al 0%.

### Simulación 3:

Igual a la Simulación 2, pero reduciendo la carga de ocupantes al 25% del aforo establecido por la norma NFPA 101 en los sótanos y pisos 1 al 4 (estacionamiento, área comercial y educativa), pero manteniendo el 100% de ocupantes en los niveles de vivienda ubicados en el piso 5 al 30 y el 100% de ocupantes en el área recreativa en el piso 31.

Resultados del análisis:

Número de Ocupantes: 2451

Tiempo de Evacuación Total: 31 Minutos

Tiempo de Atasco Mayor: 29 Minutos

Distancia de Mayor Recorrido: 292 Metros

Se observa que el tiempo de evacuación no mejora, se procede a evaluar el retiro total de los ocupantes de los pisos inferiores, para ver si éstos tienen influencia en el tiempo de evacuación de los ocupantes de los pisos superiores.

### Simulación 4:

Igual a la Simulación 2, pero reduciendo la carga de ocupantes al 0% del aforo establecido por la norma NFPA 101 en los sótanos y pisos 1 al 4 (estacionamiento, área comercial y educativa), pero manteniendo el 100% de ocupantes en los niveles de vivienda ubicados en el piso 5 al 30 y el 100% de ocupantes en el área recreativa en el piso 31.

Resultados del análisis:

Número de Ocupantes: 1566

Tiempo de Evacuación Total: 31 Minutos

Tiempo de Atasco Mayor: 29 Minutos

Distancia de Mayor Recorrido: 292 Metros

Se concluye que los ocupantes de los pisos inferiores no ejercen ninguna influencia en el tiempo de evacuación de los ocupantes de los pisos superiores. En tal sentido se tienen que evaluar otros métodos de reducir el tiempo de evacuación como por ejemplo el incremento de una escalera adicional.

### Simulación 5:

Igual a la Simulación 2, pero incorporando una tercera escalera en la zona más demandada (Pisos del 5 al 31).

Resultados del análisis:

Número de Ocupantes: 5143

Tiempo de Evacuación Total: 17 Minutos

Tiempo de Atasco Mayor: 16 Minutos

Distancia de Mayor Recorrido: 462 Metros

El tiempo de evacuación mejora notablemente con la incorporación de una tercera escalera, sin embargo se incrementa la distancia de mayor recorrido a 462 metros, lo que implica que algunos ocupantes han recorrido distancias excesivas para evacuar el edificio.

Para evaluar el efecto que tienen las escaleras de los pisos superiores sobre el tiempo de evacuación, se procede a simular la evacuación quitando una escalera.

### Simulación 6:

Igual a la Simulación 2, pero quitando una escalera en la zona más demandada (Pisos del 5 al 31).

Resultados del análisis:

Número de Ocupantes: 5116

Tiempo de Evacuación Total: 57 Minutos

Tiempo de Atasco Mayor: 56 Minutos

Distancia de Mayor Recorrido: 347 Metros

Se observa que se incrementan notablemente los tiempos de evacuación y de atasco, llegando a casi 1 hora de espera para poder evacuar o superar la congestión.

Hasta el momento todas las evacuaciones se han simulado con un tiempo de respuesta inmediato y simultáneo, es decir sin considerar un tiempo de pre evacuación, se procede a evaluar el efecto que tiene incorporar un tiempo de pre evacuación en el tiempo total de evacuación.

### Simulación 7:

Igual a la Simulación 2, pero incorporando un tiempo de pre evacuación de 1 a 7 minutos en distribución estadística lineal.

Resultados del análisis:

Número de Ocupantes: 5143

Tiempo de Evacuación Total: 33 Minutos

Tiempo de Atasco Mayor 28 Minutos

Distancia de Mayor Recorrido 319 Metros

Como era de esperarse los resultados se mantienen, ya que debido al atasco que se produce en las escaleras, el tiempo de evacuación no se ve alterado por la incorporación de un tiempo de pre evacuación.

Se procede a evaluar finalmente el mismo caso anterior pero reduciendo los ocupantes a sólo los pisos de vivienda.

### Simulación 8:

Igual a la Simulación 2 pero se aplica un criterio de necesidad de evacuación nocturna, es decir el edificio sólo lo ocupan los moradores de la zona de vivienda, se incorpora un tiempo de pre evacuación de 1 a 7 minutos en distribución estadística lineal.

Resultados del análisis:

Número de Ocupantes: 1284

Tiempo de Evacuación Total: 28 Minutos

Tiempo de Atasco Mayor: 23 Minutos

Distancia de Mayor Recorrido: 245 Metros

Los resultados se mantienen, el tiempo de pre evacuación no influye en el tiempo de evacuación

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/bu3wuf.jpg align="center")

### CONCLUSIONES

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/1vahwi.jpg align="center")

*   Se concluye que los ocupantes de los pisos inferiores no ejercen ninguna influencia en el tiempo de evacuación de los ocupantes de los pisos superiores.
    
*   Se concluye que el tiempo de evacuación está controlado netamente por las escaleras que abastecen a las viviendas.
    
*   La normativa vigente como la norma NFPA 101, contempla factores tales como la distancia de viaje a la escalera, la distancia entre escaleras, los corredores sin salida, las rutas comunes de viaje, entre otros factores, sin embargo ninguno de estos factores se relacionan con las características verticales del edificio, con el número de ocupantes totales que se encuentran en una edificación, con el número de ocupantes totales que se sirven de las escaleras, con la distancia vertical que tienen que recorrer los ocupantes para evacuar el edificio y con la altura del edificio.
    

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/tinf56.jpg align="center")

*   Esta conceptualización es consistente con las exigencias normativas impuestas en lo códigos y que están relacionadas con la protección de las escaleras como medio de defensa ante los incendios, los cuales incluyen dotar a las escaleras de resistencia al fuego y al humo, limitar las aberturas y penetraciones, y prohibir el almacenaje de materiales combustibles dentro de la escalera.
    
*   Sin embargo, al observarse que la mayor parte del tiempo, los ocupantes se encuentran dentro de las escaleras, debería haber un cierto grado de razonabilidad para evaluar estos tiempos y sus implicancias en edificaciones muy altas y altamente pobladas, donde estos tiempos pueden convertirse en insostenibles. Por ejemplo en edificios de oficinas, call centers o edificios de reuniones públicas.
    
*   En las simulaciones realizadas se observa que las colas para ingresar a la escalera se forman no sólo en la puerta de acceso en todos los pisos sino que esta cola es retroalimentada por la que se forma dentro de la propia escalera. Esto se debe a que a medida que se incrementa la densidad de ocupantes dentro de la escalera, se reduce la velocidad de evacuación vertical, impidiendo que el flujo permita que nuevos ocupantes se incorporen a la escalera.
    

### Cambio de uso a Edificaciones altamente pobladas en los pisos superiores

Para evaluar los efectos de edificaciones altamente pobladas y las implicancias que tienen en la seguridad de los ocupantes, cambiaremos la simulación actual para asemejarla a una edificación de oficinas, con un promedio de 1 ocupante por cada 10 m^2 según lo establecido por la norma NFPA 101 para este tipo de ocupaciones.

### Simulación 9:

Igual a la Simulación 8 pero se considera un ocupante cada 10 m^2 según lo establecido para edificaciones de oficinas, se incorpora un tiempo de pre evacuación de 1 a 7 minutos en distribución estadística lineal.

### Resultados del análisis:

Número de Ocupantes: 2227

Tiempo de Evacuación Total: 28 Minutos

Tiempo de Atasco Mayor 25 Minutos

Distancia de Mayor Recorrido 324 Metros

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/yhot52.jpg align="center")

Para comprobar en qué medida se ve afectado el tiempo de evacuación conforme se incrementa el número de ocupantes, a continuación realizaremos simulaciones progresivas incrementando la carga de ocupantes, partiendo de un promedio de 1 ocupante cada 30 m^2 a 1 ocupante cada 5 m^2, este último caso lo consideramos un límite plausible para una edificación de oficinas altamente ocupadas, según lo establecido por la norma NFPA 101, que considera un ocupante cada 4.65 m^2 para call centers o zonas de lectura de bibliotecas. En todos los casos se incorpora un tiempo de pre evacuación de 1 a 7 minutos en distribución estadística lineal y se evalúan dos opciones, dos escaleras conectadas a una única salida de evacuación (caso típico considerado por la normativa NFPA 101 y el RNE) y dos escaleras conectadas a múltiples salidas de evacuación (caso atípico que sólo puede lograrse en terrenos que ocupan varias calles anexas al terreno). Los resultados de estos análisis se muestran en el apéndice, y los siguientes gráficos y tablas resumen los principales resultados.

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/pfbvim.jpg align="center")

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/hhg1l6.jpg align="center")

### ANALISIS DE TIEMPOS PARA QUE EL ULTIMO OCUPANTE TOME LA ESCALERA

Dos escaleras conectadas a múltiples salidas de evacuación

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/i7ru6w.jpg align="center")

### ANALISIS DE TIEMPOS PARA QUE EL ULTIMO OCUPANTE TOME LA ESCALERA

Dos escaleras conectadas a una única salida de evacuación

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/wbx2h6.jpg align="center")

### TIEMPO MAYOR PARA QUE EL ULTIMO OCUPANTE TOME LA ESCALERA

Dos escaleras conectadas a múltiples salidas de evacuación

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/rrh1yj.jpg align="center")

### TIEMPO MAYOR PARA QUE EL ULTIMO OCUPANTE TOME LA ESCALERA

Dos escaleras conectadas a una única salida de evacuación

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/cqvvbp.jpg align="center")

Las conclusiones de este estudio son las siguientes:

*   El aumento de más de una salida para un edificio con dos escaleras reduce el tiempo de evacuación en aproximadamente un 20%.
    
*   Existe un incremento en el tiempo de evacuación con respecto al número de ocupantes, pero la relación no tiende a ser directamente proporcional, sino con un crecimiento creciente de acuerdo al número de ocupantes.
    
*   Los tiempos de atasco en el acceso a las escaleras crecen de la misma forma que el incremento en los tiempos de evacuación, el incremento en el número de ocupantes o el incremento densidad de ocupantes, y llegan a tiempos que pueden poner en peligro la sostenibilidad de los evacuantes de la edificación, sobre todo porque en las edificaciones no residenciales no existen vestíbulos previos, ni áreas de refugio. Siendo que la sostenibilidad de los ocupantes depende del ingreso a la caja de escaleras, esta situación se considera crítica.
    
*   Los tiempos de atasco mayor se producen el sector medio inferior de la edificación y se concentran en los pisos 4 al 13.
    
*   Los tiempos de atasco son decrecientes con respecto a la altura
    
*   Los tiempos de atasco se reducen en un 20% a 25% cuando se cuenta con más de una salida al exterior.
    

### CONSIDERACIONES FINALES

La consideración más significativa de este análisis es entender la importancia de incorporar en los diseños de edificaciones complejas, a los software de simulación de evacuación, que permiten evaluar deficiencias en los diseños que no son descubiertas por los métodos prescriptivos y por la normativa vigente. Se debe tomar en cuenta que este análisis no es concluyente ni puede generalizarse a todas las edificaciones, ya que sólo corresponde al caso que hemos estudiado, estudios posteriores en otras edificaciones y/o geometrías permitirían validar los hallazgos encontrados.

### APENDICE DE RESULTADOS

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/a0ro0t.jpg align="center")

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/398ex2.jpg align="center")

### DETALLE DE LOS CRITERIOS DE DISTRIBUCION DE OCUPANTES EN LAS INSTALACIONES DE ACUERDO A LAS DIVERSAS SIMULACIONES REALIZADAS

### PARAMETROS BÁSICOS DE LAS SIMULACIONES REALIZADAS

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/tnnndz.jpg align="center")

### RESULTADOS OBTENIDOS EN LAS SIMULACIONES REALIZADAS

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/aimd4l.jpg align="center")

### RESULTADOS OBTENIDOS

### ANALISIS PROGRESIVO DE DENSIDADES

### Dos escaleras conectadas a una única salida de evacuación

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/alrhs2.jpg align="center")

### RESULTADOS OBTENIDOS

### ANALISIS PROGRESIVO DE DENSIDADES

### Dos escaleras conectadas a múltiples salidas de evacuación

![Simulaciones de Evacuación para el Análisis de la Seguridad ](https://files.catbox.moe/rh21is.jpg align="center")

**SIN FORMACIÓN NO HAY SALVACIÓN**