Pruebas Realizadas

Se probo con el computador cisco 10 

conecto pero no funciona el internet y l

Pruebas Realizadas

Resultados

Punto de Red	Categoría	Resultado	IP Obtenida	Velocidad

Punto 01	Cat 6	PASS	192.168.1.10	1000 Mbps
Punto 02	Cat 6	PASS	192.168.1.11	1000 Mbps
Punto 03	Cat 6	FAIL	N/A	N/A



---

Análisis de Resultados

Durante la ejecución de las pruebas en los puntos de red del laboratorio, se obtuvieron resultados mixtos, evidenciando tanto enlaces funcionales como fallas en el cableado.

Los puntos 01 y 02 presentan un estado PASS, lo que indica que cumplen con los estándares de certificación. Ambos obtuvieron dirección IP mediante DHCP y establecieron una velocidad de enlace de 1000 Mbps, lo que confirma un correcto funcionamiento tanto a nivel físico como lógico.

Por otro lado, el punto 03 presentó un resultado FAIL, lo que indica una falla en el cableado o en la conexión.


---

Análisis de Fallas

Punto 03:
Se detecta una posible falla en el mapa de cableado (Wiremap), lo que puede deberse a:

Pares cruzados en el conector RJ45

Mala terminación en el patch panel

Exceso de destrenzado en los pares


Además, considerando las imágenes del rack, se observa una alta densidad de cableado, lo que puede influir en errores de conexión o interferencias si no existe un adecuado ordenamiento.


---

Observaciones Generales

Los indicadores LED del switch muestran actividad en varios puertos, lo que confirma enlaces activos.

La verificación en el equipo muestra conectividad Ethernet habilitada.

El entorno presenta cableado funcional, pero con oportunidades de mejora en organización.
