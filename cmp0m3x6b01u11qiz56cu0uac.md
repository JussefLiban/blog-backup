---
title: "ANÁLISIS DE EVACUACIÓN DE UN BUS DE DOS PISOS"
datePublished: 2026-05-11T02:58:23.031Z
cuid: cmp0m3x6b01u11qiz56cu0uac
slug: an-lisis-de-evacuaci-n-de-un-bus-de-dos-pisos

---

### Según la Experiencia del Incendio en el Terminal de Fiori (Lima-Perú)

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/sj9twv.jpg align="center")

El 31 de marzo del 2019, sucedió un lamentable incendio en un bus de dos pisos en el Perú, se adjunta videos en los precisos instantes en los que este bus se comienza a incendiar. Los peritajes preliminares han determinado que el incendio comenzó a las 7:45 de la noche y se originó en el sistema de aire acondicionado ubicado en la parte posterior del bus. Las personas fallecieron debido a que no pudieron escapar de las llamas y quedaron atrapadas en el estrecho pasadizo y la escalera que conecta el segundo y primer piso del vehículo.

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/cam2vb.jpg align="center")

En el video se observa que todo el primer piso ha sido evacuado y las personas del segundo piso no han podido hacerlo, como resultado de ello diecisiete personas han fallecido calcinadas y siete resultaron heridas. Los fallecidos fueron ocho adultos hombres, cinco mujeres y cuatro menores de edad, todos los cadáveres se encontraron situados en la parte posterior del bus, cercano a las escaleras que conducían al primer piso. Lo sorprendente es que a pesar de que este bus ha estado estacionado, el incendio fue identificado de forma inmediata y las personas se encontraban en estado conscientes o despiertos, no pudieron escapar del bus. Todos los que fallecieron estuvieron en la parte anterior al acceso de las escaleras, por lo que se supone que hubo una aglutinación en la escalera de escape, que como sabemos son muy angostas.

Con el fin de evaluar la seguridad a la vida en este tipo de escenarios a continuación les presento los resultados de una serie simulaciones de evacuación que he realizado a un bus de dos pisos de similares características al que sufrió el incidente, para ello he usado el software de simulación computacional de evacuación Pathfinder.

### Características Arquitectónicas del Bus

A continuación se detallan las características arquitectónicas fundamentales del diseño propuesto:

Capacidad de pasajeros Primer Piso: 18 Ocupantes

Capacidad de pasajeros Segundo Piso: 48 Ocupantes

Capacidad de Tripulación: 3 Ocupantes

Capacidad Total del Bus: 69 Ocupantes

Ancho de Pasillos: 0.56 m

Ancho de Escalera: 0.60 m

Altura de la Escalera: 2.0 m

Dimensiones de los Pasos / Contrapasos: 0.18 x 0.28 m

Dimensiones del habitáculo por pasajero: 0.45 x 0.75 m (0.15 m de respaldar) en el segundo piso y 0.60 x 0.75 m (0.15 m de respaldar) en el primer piso.

Dimensiones del Bus: 11.39 x 2.46 x 3.80 m

Numero de puertas de Salida: Una

Ancho de la Puerta de Salida: 0.80 m

### Características Arquitectónicas del Bus Analizado

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/lc1qto.jpg align="center")

### Vista de Ocupantes Segundo Piso (48 Pasajeros)

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/y6agtq.jpg align="center")

### Vista de Ocupantes Primer Piso (18 Pasajeros más 3 Tripulantes)

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/k688ya.jpg align="center")

### Posicionamiento Tridimensional de Ocupantes

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/j3o3x8.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/k3yxdd.jpg align="center")

### Configuración de escenario de Incendios

De acuerdo a un estudio de Qiao YAN (1) la potencia típica de un incendio inicial en un vehículo de este tipo se asume de 3MW, y el área de la fuente del incendio se establece en 0.5 m × 0.5 m. En la simulación de incendios, los parámetros de altura de humo, la concentración de gases tóxicos, la visibilidad, la temperatura y otros parámetros necesitan ser estudiados y analizados. Estudios relevantes han demostrado que más de 2/3 de las víctimas murieron como consecuencia del humo del incendio, por lo que la altura de la capa de humo es el factor clave que afecta a la evacuación.

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/a7vnhk.jpg align="center")

La Figuras mostradas son curvas que analizan la altura del humo en dos capas cuando se produce un incendio en un autobús de dos pisos. Como se puede ver, la altura de humo a los 85 segundos ha alcanzado la altura crítica de 1.5 m lo que provoca que en este tiempo los ocupantes no puedan escapar, por lo que el tiempo requerido de evacuación seguro (RSET) se establece en 85 segundos. Esto significa que todos los pasajeros requieren escapar del segundo piso de un autobús de dos pisos en menos de 85 segundos.

### Características de la Simulación de Evacuación Propuesta

La simulación propuesta se basa en los siguientes supuestos:

Tiempo de Reacción a la Evacuación: “0” Segundos

Dimensiones de los Ocupantes: 0.45 m de ancho de hombros / 1. 80 m de altura

Velocidad de Evacuación: 0.75 m/s

### Resultados de las Simulaciones de Evacuación

A continuación se muestra una secuencia de simulación en intervalos de 30 segundos. Los resultados arrojan que desde que todos los ocupantes deciden tomar la acción de evacuación, el tiempo de evacuación total del bus toma 154 segundos. Se observa además que el flujo se encuentra controlado por la escalera que conduce a los ocupantes del segundo piso al primero.

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/qs4ybg.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/nlhz9d.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/n3ulb4.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/miuvlz.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/ao3u6l.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/vo2kya.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/jdywhp.jpg align="center")

Los resultados demuestran que el tiempo requerido de evacuación seguro (RSET) es de 85 segundos mientras que el tiempo disponible de evacuación seguro (ASET) es 154 segundos, superándose ampliamente los tiempos de sostenibilidad de cerca de 40 ocupantes del bus.

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/751dpl.jpg align="center")

Si el supuesto de que el lapso de tiempo entre la detección del incendio por parte de los ocupantes y la toma de acciones de decidir evacuar hasta el tiempo en que se alcancen los niveles de insostenibilidad de los ocupantes es de 85 segundos, existe la posibilidad de que cerca de 40 ocupantes puedan salir afectados por el incendio (desde asfixia, quemaduras, hasta la pérdida de la vida), según se observa en el siguiente gráfico que muestra el número de ocupantes ubicados en el segundo piso al segundo 85.

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/garn2d.jpg align="center")

Para acelerar el tiempo de evacuación se propone instalar dos toboganes de evacuación en el segundo piso, estos toboganes actuarían automáticamente en tanto el piloto decida detener el bus y activar la extensión de los toboganes. Los toboganes estarían ubicados en la parte delantera y posterior del vehículo.

Bajo los mismos parámetros anteriormente seleccionados, a continuación se muestra una secuencia de simulación en intervalos de 10 segundos. Los resultados arrojan que desde que todos los ocupantes deciden tomar la acción de evacuación, el tiempo de evacuación total del bus toma 56 segundos. Se observa además que el flujo ya no se encuentra controlado por la escalera que conduce a los ocupantes del segundo piso al primero, ya que tan sólo un ocupante (el último en evacuar del bus), decide usar la escalera en vez de los toboganes.

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/oyjaqy.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/v1aucs.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/zuvctn.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/5pxg4q.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/3msurx.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/c60vir.jpg align="center")

![Análisis de Evacuación de un Bus de Dos Pisos](https://files.catbox.moe/phcvgb.jpg align="center")

### Conclusiones

Se concluye que el tiempo requerido de evacuación seguro (RSET) es de 85 segundos mientras que el tiempo disponible de evacuación seguro (ASET) es 154 segundos, superándose ampliamente los tiempos de sostenibilidad de cerca de 40 ocupantes del bus.

### Videos

Relación de videos complementarios:

Finalmente se asume que uno de los toboganes se encuentra afectado por el incendio (experiencia similar a la del incendio del terminal de Fiori). Bajo los mismos parámetros anteriormente seleccionados, a continuación se muestra una secuencia de simulación en intervalos de 20 segundos. Los resultados arrojan que desde que todos los ocupantes deciden tomar la acción de evacuación, el tiempo de evacuación total del bus toma 103 segundos. Se observa además que el tobogán delantero sigue siendo el método preferido de evacuación de los ocupantes del segundo piso.

### Conclusiones

*   Las curvas de altura del humo muestran que un incendio de 3MW generaría que se alcance una altura crítica del humo de 1.5 m en 85 segundos, lo que provoca que en este tiempo los ocupantes no puedan escapar.
    
*   En tal sentido se ha establecido que el tiempo requerido de evacuación seguro (RSET) se ha fijado en 85 segundos.
    
*   Bajo este escenario los resultados demuestran que para un bus típico de una sola vía de escape, el tiempo disponible de evacuación seguro (ASET) es 154 segundos, superándose ampliamente los tiempos de sostenibilidad de cerca de 40 ocupantes del bus.
    
*   Si el supuesto anterior es correcto, existe la posibilidad de que cerca de 40 ocupantes puedan salir afectados por el incendio (desde asfixia, quemaduras, hasta la pérdida de la vida).
    
*   Para acelerar el tiempo de evacuación se propuso instalar dos toboganes de evacuación en el segundo piso.
    
*   Bajo los mismos parámetros de la primera simulación, los resultados del tiempo de evacuación total arrojan que se logra evacuar el bus en 56 segundos. Se observa además que el flujo ya no se encuentra controlado por la escalera que conduce a los ocupantes del segundo piso al primero.
    
*   Finalmente se asume que uno de los toboganes se encuentra afectado por el incendio (experiencia similar a la del incendio del terminal de Fiori). Los resultados arrojan un tiempo de evacuación total de 103 segundos. Se observa además que el tobogán delantero sigue siendo el método preferido de evacuación de los ocupantes del segundo piso.
    
*   El uso de toboganes de evacuación es una medida efectiva y económica que permitiría extender notablemente las probabilidades de subsistencia de los evacuantes de un bus ante un incendio de 3 MW de potencia.
    

### Videos

Para ver los videos explicativos de este estudio entrar al siguiente enlace:

%[https://www.youtube.com/watch?v=kdMp5GtKIFs] 

### Bibliografía

(1) Qiao YAN, Xin WU\*, Zi-han TU, and Ya-wen PENG, Evacuation Analysis and Optimization of Double-Deck Bus, 2018 2nd International Conference on Energy and Power Engineering (EPE 2018), ISBN: 978-1-60595-550-6

(2) Daniel Alvear Portilla, Orlando Abreu Menéndez, Arturo Cuesta Jiménez, Notas Educativas del Curso de Simulación de Evacuación a Universidad de Cantabria (Curso 2018-2019)-

**SIN FORMACIÓN NO HAY SALVACIÓN**