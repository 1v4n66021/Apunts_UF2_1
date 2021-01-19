# Apuntes UF1 - 1

### OBJETIVOS DE LAS PRUEBAS

- Se pueden destacar dos objetivos:
    -  Comprobar si el software no hace lo que debe hacer
    -  Comprobar si el software hace lo que no debe hacer
- Para la realización de estas pruebas es necesarios un framework

### FRAMEWORK
## ¿Que es un framework?
Un framework es un entorno de trabajo que nos permite disponer de bibliotecas o clases en un mismo entorno, haciendo asi que sea mas facil la concepcion del programa.
Estos estan compuestos (por lo general) por:
- Herramientas comunes
- Bibliotecas
- Un conjunto de las mejores prácticas y suposiciones

Ademas, nos permite unificar el proceso de desarrollo entre desarrolladores.

### PRUEBAS
Existen distintas formas de pruebas;

## Forma de las pruebas
- Las **pruebas dinámicas**: Estas requieren de la ejecución de la aplicacion, estas pruebas nos permiten medir el comportamiento de la aplicación.
- Las **pruebas estáticas**: Estas se realizan sin la ejecucion del código, simplemente se examina el código fuente en busca de errores.

Estas pruebas siguen unas estrategias, dos de estas son:

- **Caja negra**: En esta estrategia se estudia el sistema desde fuera, el objetivo es verificar la funcionalidad.
    - Se estudia el sistema desde fuera
    - No se tienen en cuenta los detalles internos de funcionamiento
    - Se proporcionan entradas y se estudian las salidas
    - Se trabaja sobre la interfaz
    - ...
- **Caja blanca**: En esta, en cambio, se examina el código fuente y su ejecucion, el objetivo es verificar la estructura.
    - Se examina el código fuente y su ejecución
    - Se comprueban los flujos entre unidades
    - También los flujos de ejecución dentro de cada unidad
    - ...
![Estrategias de Prueba](http://jamj2000.github.io/entornosdesarrollo/3/assets/caja_blanca-caja_negra.png)

Ademas, las pruebas se pueden distingir entre dos tipos:
- **Funcionales**: Evaluan el cumplimiento de los requisitos.
    - Pruebas unitarias
    - Pruebas de regresión
    - Pruebas de intergración
    - Pruebas de humo
    - Pruebas del sistema
    - Pruebas alfa y beta
    - Y pruebas de aceptación
- **No funcionales**: Evaluan aspectos adicionales como rendimiento, seguridad, ...
    - Pruebas de usabilidad
    - Pruebas de rendimiento
    - Pruebas de stress
    - Pruebas de seguridad
    - Pruebas de compatiblidad
    - Pruebas de portabilidad
    - ...

Dentro de estas pruebas podemos encontrar dos tipos de mecanismos;

### Mecanismos de prueba

- **Manual**: Este es realizado por personal de la empresa o externo.
- **Automático**: Este, en cambio, es realizado mediante software, que, ejecuta el código de forma automatizada y compara los resultados obtenidos y los resultados esperados.

### INTEGRACIÓN

## Formas de integración
- Integración Big Bang
- Integración Descendente
- Integración Ascendente
- Integración Continua (CI)

### COBERTURA DEL CÓDIGO

- Es una medida que indica el porcentaje de código que ha sido ejecutado durante las pruebas
- Se recomienda que sea lo más cercano a 100%
- Si este es del 100% significa que se ha ejecutado todo el código durante las pruebas
- Si es menor, entonces existe código fuente que no se ha ejecutado durante las pruebas.
- La cobertura se uede realizar tando desde el IDE como desde un servicio web.

### CALIDAD

## CONTROL DE CALIDAD

Se mide la calidad de un producto, para ello es necesario realizar las pertinenes pruebas.

Algunas de estas pruebas són:

-**QA**, este es un conjunto de actividades que garantizan la calidad en los procesos en los cuales se ha desarrolado el producto.
-**QC** es un conjunto de actividades para garantizar la calidad de los productos.

Ademas, tambien existen los factores de calidad, estos factores de calidad se pueden agrupar en 3 ámbitos:

- Operación del producto
    - Corrección
    - Fiabilidad
    - Eficiencia
    - Seguridad
    - Facilidad de uso
- Revisión del producto
    - Mantenibilidad
    - Flexibilidad
    - Facilidad de prueba
- Transición del producto
    - Portabilidad
    - Reusabilidad
    - Interoperatividad
