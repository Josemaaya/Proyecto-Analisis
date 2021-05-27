

`	  	`***Correlativo No. 001 Versión No. 01***   

**Documento de Especificaciones, Requerimientos y Criterios de**   **Aceptación de Software**   
**


1. **DATOS GENERALES DEL SOLICITANTE:**   
**


**Lugar y fecha:**   

|<p>Ubicación:   </p><p>**(Región Geográfica)**   </p>|<p>Zacapa.   </p><p>   </p>|
| :- | :- |
|<p>Dirección: (Unidad  </p><p>Administrativa)   </p>|` `Universidad Mariano Galvez   |
|<p>Fecha:   </p><p>   </p>|26 de Abril de 2021   |
**   

**Sistema, Aplicación o Programa:**     

|Nombre:    |Sistema de servicios “Almacén El Ahorro”  |
| :- | :- |
|Módulo:   |Administracion  |
|Componente:  |Compra y venta de productos   |
**   

1. **FUNCIONALIDAD GENERAL REQUERIDA (OBJETIVOS Y ALCANCE  - concretos, medibles, realizables):**   
**


|<p>Creación sistema Validaciones con las siguientes características:   </p><p>A. **Menú principal**   </p><p>B. **Sub menús**   </p><p>C. **Roles de usuario**   </p><p>D. **Menú panel de control ( usuario administrador )**   </p>|
| :- |
**   
**




(Marque con una ‘X’ los cuadros, para desmarcar presione la tecla ‘Q’.)   

`  	`**Tipo de FuncionalidadRequerida:***   	   

|CREAR:   |MODIFICAR O SUPRIMIR:   |
| :- | :- |
|x  |<p>Nueva funcionalidad a través de la</p><p> </p><p>elaboración de nuevo módulo.   </p>|x  |La funcionalidad actual de algún proceso automático, debido a modificaciones en cálculos, políticas o reglas establecidas.   |
|x  |<p>Un nuevo proceso automático.   </p><p> </p>|||
|x  |<p>Un nuevo reporte.   </p><p> </p>|x  |La presentación de información en Reportes.   |
|x  |<p>` `Otro:  </p><p>Especifique)   </p>|   	  ||
**   

1. **REQUERIMIENTOS DEL NUEVO COMPONENTE:**   
**


En esta sección se deberá conformar un grupo de personas involucradas para especificar a detalle las condiciones técnicas y la funcionalidad esperada para el nuevo componente a 

desarrollar. Por favor incluya los siguientes tipos:   

- Técnicos:(Plataforma, Lenguajes de Programación, Base de Datos, Capacidad de proceso de la PC, Interconexión con otros Sistemas, Multiusuario,  etc.).   
- Seguridad:(Contraseñas, Restricciones, Bitácoras, Privilegios, Accesos y perfiles de usuario).   
- Integridad de Datos:(Validación, fechas, cantidades, campos obligatorios).   
- Presentación: (Orden de campos en pantallas y reportes).   
- Desempeño. (Velocidad de proceso, capacidad de respuesta, carga de trabajo, volumen de datos esperados).   



- Funcionalidad Esperada: (Detalle del proceso, fórmulas, cálculos, restricciones).   
- Administración: (entradas y salidas de información, mensajes, alarmas).  Otros: (Requerimientos de otro tipo).   



|**Tipo de Requerimiento** |**Descripción, Justificación o detalles a tomar en cuenta**  |
| :- | :-: |
|Funcionalidad 1 Crear Cuentas Clientes*  |<p>Registro de clientes en un formulario para un base de datos incluyendo los siguientes parámetros. Teniendo un código único mediante llave primaria para cada uno.  </p><p>  </p><p>- *Nombre del cliente*  </p><p>- *Correo electrónico*  </p><p>- *Contraseña*  </p><p>- *DPI*  </p><p>- *Nit*  </p><p>- *Teléfono*  </p><p>- *Dirección*  </p><p>- *Fecha de nacimiento*  </p><p>- *Genero*  </p><p>  </p>|
|Funcionalidad 2 Registro de productos  |<p>Registro de productos disponibles para “Almacén El Ahorro” para que los clientes puedan disponer de una vista de los productos posibles a adquirir. Los productos se registrarán de la siguiente manera.  </p><p>  </p><p>- *Código único*  </p><p>- *Nombre del producto*  </p><p>- *Descripción*  </p><p>- *Proveedor/Distribuidor*  </p><p>- *Cantidad en Stock*  </p><p>- *Precio de venta*  </p><p>- *Precio de compra*  </p><p>- *Fecha de caducidad*  </p><p>*  </p>|
|<p>Funcionalidad 3  </p><p>Organizar los productos según su  caso  </p>|<p>Organizar los productos disponibles en categorías según su caso, esto para llevar un mejor orden de lo que se quiere vender y que los clientes tengan una vista simple de los productos.  </p><p>  </p>|
| |<p>- *Correlativo de Categoría*  </p><p>- *Tipo*  </p><p>*  </p>|
|Funcionalidad 4 Ventas  |Realizar ventas por medio del sistema en donde el cliente pueda acceder a la visualización del contenido de los productos y poder hacer una compra por medio de este.  |
|Funcionalidad 5 Proveedores  |<p>Registro de proveedores y las fechas en las que estos tiene previsto arribar el almacén para satisfacerlo con sus productos.  </p><p>  </p><p>- *Código de proveedor*  </p><p>- *Nombre proveedor*  </p><p>- *Contacto directo*  </p><p>- *Número de teléfono*  </p><p>- *Correo electrónico*  </p><p>- *Fecha programada de llegada mensual*  </p><p>- *Código de producto a vender*  </p><p>  </p>|
|Funcionalidad 6 Reportes  |<p>Realizar reportes de los productos, por código de producto, por proveedor, y por nombre  </p><p>Realizar reportes de los clientes por código de cliente, por dpi, por nombre y por número de teléfono  </p><p>Realizar reporte de ventas por número de factura, cliente, producto y cantidad de productos vendidos  </p><p>Realizar reporte de los proveedores por código, contacto directo, nombre de proveedor.  </p>|
|Funcionalidad 7 Creación de facturas  |<p>El sistema deberá ser capaz de crear una factura única dando como parámetro los siguientes datos.  </p><p>  </p><p>- *Numero único de factura*  </p><p>- *Nombre del cliente*  </p><p>- *Nit del cliente*  </p><p>- *Dirección*  </p><p>- *Productos adquiridos*  </p><p>- *Cantidad de productos*  </p><p>- *Precio unitario*   </p><p>- *Precio total*  </p><p>  </p>|
**    
**

`  	`*Documento de Especificaciones, Requerimientos y Criterios de Aceptación de Software -DERCAS-   	Página*  PAGE   \\* MERGEFORMAT *4 de*  NUMPAGES   \\* MERGEFORMAT *4*   


#
**Analisis Incremental “Almacen El Ahorro”**

**Metodología y razonamiento:**

Para la realización del sistema requerido en el DERCAS, se seleccionó realizar su respectivo análisis por medio del modelo incremental. El modelo de desarrollo incremental es el ciclo de vida del desarrollo de software, en el que el proyecto se divide en una serie de incrementos, y cada incremento proporciona parte de las funciones que satisfacen las necesidades de todos los proyectos. A los requisitos se les asigna prioridad y se entregan en los incrementos correspondientes según el orden de prioridad. En algunas versiones de este modelo de ciclo de vida, cada subproyecto sigue el "modelo mini-V", con sus propias fases de diseño, codificación y prueba.

![MODELOS DE PROCESO – INGENIERÍA DEL SOFTWARE](https://github.com/Josemaaya/Proyecto-Analisis/blob/main/Imagenes/Aspose.Words.54e10a5c-5959-429f-8da1-5bcf4a0070ec.002.png)

**Ventajas del método:**

- Utilizando el modelo incremental, debido a la realización de parte de la función, reduce el tiempo de desarrollo inicial. 
- También tiene un impacto favorable en los clientes, a saber, la entrega anticipada de las partes operativas del software.
- Este modelo proporciona todas las ventajas del modelo en cascada de retroalimentación, solo reduciendo sus desventajas al rango de cada incremento. 
- En comparación con el modelo en cascada, los productos se pueden entregar a los clientes más rápidamente.
- Al reducir el tamaño del incremento, los cambios se pueden acomodar más fácilmente. 
- Debido a su versatilidad, se requiere una planificación cuidadosa a nivel gerencial y técnico.



**Antelación de preparación del proyecto**

El proyecto “Sistema Almacén El Ahorro” se realizará en nombre clave PIO, el cual servirá de prefijo entre los programadores para referirse al proyecto mencionado. Para este proyecto, se realizará una antelación de planeación de 3 fases las cuales se desglosarán en sus respectivos apartados y secciones en el análisis incremental.

**Información General del proyecto:**

- **Nombre:** Sistema Almacén El Ahorro
- **Nombre en clave:** PIO
- **Fases:** 3 fases incrementales
- **Duración por fase:** 1 semana por fase
- **Duración general:** 3 semanas
- **Fechas establecidas**: Inicio 10 de mayo, Final 29 de mayo de 2021.


**Generalidades Fases Incrementales**

- Fase 1: Fase Analítica

Descripción:  La primera fase incremental se le denomina como analítica y busca realizar tanto el análisis incremental del sistema como las reuniones necesarias con el cliente para plantar las bases del sistema y el planteamiento del problema

Duración: 1 semana

- Fase 2: Fase Desarrollo

Descripción: La segunda fase incremental llevara el nombre de desarrollo, en ella se busca crear todo el desarrollo tanto de la base de datos como del programa para el usuario, es posible que esta fase se extienda en un margen de error de 3 a 4 días máximos realizándose en conjunto con la fase de post-desarrollo.

Duración: 1 semana (Margen de error: +4 días Max).



- Fase 3: Fase Post-Desarrollo

Descripción: La tercera fase incremental se nombra como fase de post-desarrollo, en ella se realizarán dos a tres presentaciones al cliente sobre las versiones finales del producto para que nos pueda proveer feedback sobre la satisfacción que esta se le está proporcionando, también servirá para realizar pruebas en base de datos para observar su integridad

Duración: 1 semana


**Desarrollo y detalles de las fases incrementales**

- **Fases del modelo incremental:** (comunicación, planeación, modelado, construcción, despliegue).

**Fase Incremental 1: Fase Analítica**

**Inicia:** 10 de mayo.

**Finaliza:** 16 de mayo.

- **Comunicación (2 días):**

Día 1:

El día 10 de mayo se realizará la presentación del DERCAS al desarrollador el cual deberá de analizar cuidadosamente y realizara un listado de dudas o sugerencias las cuales serán presentadas el día dos de la fase de comunicación al cliente.

Día 2:

El día 11 de mayo se presentarán las ideas planteadas por el programador al cliente y se llegara a un acuerdo con respecto al sistema.

- **Planeación (2 días):**

Día 1:

El día 12 de mayo se realiza un plan de trabajo por medio de un análisis incremental del sistema que servirá de principal y fundamental apoyo para la realización del proyecto.

Día 2:

Se realizará un repositorio en git para la asignación de tareas y problemas a resolver dependiendo de la magnitud plantada en el DERCAS antes presentado.

- **Modelado (1 día):**

Día 1:

Se realizará el calendario general de la fase de desarrollo puesto que se necesita modelar los días y las tecnologías en las que se van a trabajar para el margen de error planteado con anterioridad sea reducido drásticamente.** Se realizarán los casos de uso que el sistema será capaz de llevar a cabo para aclarar ideas de posibles problemas que puedan surgir no tomados en cuenta.

- **Construcción (1 día):**

Día 1:

Desarrollo del diagrama entidad relación de la base de datos para plantear el problema y las tablas que se desean resolver y fabricar.

- **Despliegue (1 día):**

Día 1:

Se subirá todo lo realizado y trabajado al repositorio de git del proyecto PIO, esto con el fin de actualizar el plan de trabajo allí realizado y llevar un control bien organizado.
















**Fase Incremental 2: Fase Desarrollo**

**Inicia:** 17 de mayo.

**Finaliza:** 23 de mayo.

- **Comunicación (1 día):**

Día 1:

El día 17 de mayo se realizará una reunión con el cliente acerca de lo trabajado en la primera semana y se le presentará el producto final del desarrollo de la fase analítica.

- **Planeación (1 día):**

Día 1:

El día 18 de mayo se realizarán las tablas de las bases de datos y se revisara el desarrollo del diagrama ER para replantar y planear bien la estructura final de la base de datos con las tablas ya creadas.

- **Modelado (1 día):**

Día 1:

Se realizarán las clases con las que se van a trabajar en pseudocódigo acerca del IDE a utilizar y las funcionalidades del programa que ira conectado a la base de datos.

- **Construcción (3 días):**

Día 1:

Se realizarán las relaciones en la base de datos y así mismo se realizarán todos los requisitos para que su integridad no sea comprometida.

- Inserts
- Vistas
- Secuencias
- Procedimientos almacenados
- Triggers

Día 2:

Se realizará la conexión con la base de datos y los formularios que servirán en el programa para que el usuario pueda llenar datos y consultar productos y hacer ventas.



Día 3:

Se realizar toda la programación en los formularios creados el día anterior para que puedan funcionar y obtener los datos necesarios para que estos se los puedan pasar a la base de datos por medio de procedimientos almacenados.

- **Despliegue (1 día):**

Día 1:

Se subirá todo lo realizado y trabajado al repositorio de git del proyecto PIO, esto con el fin de actualizar el plan de trabajo allí realizado y llevar un control bien organizado.























**Fase Incremental 3: Fase Post-Desarrollo**

**Inicia:** 24 de mayo.

**Finaliza:** 29 de mayo.

- **Comunicación (1 día):**

Día 1:

El día 24 de mayo se realizará una prueba general del funcionamiento de la base de datos y así considerar puntos extras que no se tomaron en cuenta a la hora de la realización de la fase analítica y el posible alcance que esta quiere llegar.

- **Planeación (1 día):**

Día 1:

El día uno de la etapa de planeación se realizará la primera presentación al cliente sobre el funcionamiento de la base y esta será tomada en cuenta para proveer sugerencias post producción para agregar.

- **Modelado (1 día):**

Día 1:

Se realizará un diagrama de casos de uso para presentación del usuario del sistema y de los empleados para el cliente.

- **Construcción (2 días):**

Día 1:

Se realizará un pentesteo en la base de datos para corroborar que exista una integridad favorable de los datos y no haya filtraciones en las diversas tablas creadas en la fase de desarrollo

Día 2:

De surgir imprevistos en las pruebas o errores no tomados en cuenta con anterioridad, se realizarán los cambios necesarios para que la integridad no quede comprometida.

- **Despliegue (1 día):**

Día 1:

Se hará la presentación final del proyecto el día sábado 29 de mayo al cliente.



