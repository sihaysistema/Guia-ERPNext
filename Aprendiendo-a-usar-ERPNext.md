# Aprendiendo a usar ERPNext

## Modulo 1

### 1.0 Introducción
Este documento asume que usted tiene curiosidad de saber de qué se trata ERPNext y que está interesado en aprender como usarlo.

### 1.1 Resumen
ERPnext es un software que corre en una máquina con sistema operativo linux (en Virtualbox
 se puede correr en cualquier sistema oeprativo) o en un servidor. Lo puedes acceder con un avegador
 web. En este software ingresas registros sobre muchas cosas relacionadas a tu empresa u organización.

* Clientes
* Proveedores
* Ventas
* Contabilidad
* Inventario de Productos (Stock)
* Proyectos
* Manufactura
* Ventas al detalle

También incorpora ciertas funciones especificas del dominio de ciertas industrias o actividades

* Educacion
* Agricultura
* Salud
* Organizaciones sin Fines de Lucro

ERPNext cuenta con documentación básica, videos y un grupo de soporte que le puede apoyar mientras esta guía es completada.


### 1.2 Estructura
The following course or tutorial is divided into 5 modules, which will enable you to master ERPNext.

Modulo 1: Introduction a ERPNext
Modulo 2: Uso básico
Modulo 3: Uso intermedio
Modulo 4: Uso avanzado
Modulo 5: Convirtiéndose en experto

Este curso está dividido en 5 modulos. Cada módulo llevará el aprendizaje de lo más general 
a lo más específico, de la misma manera que hablamos de un barco en términos generales, 
cada módulo adicional irá explorando témas más específicos sobre el barco, como sistemas 
de propulsión, achique, navegación, tripulación, etc.  Hasta finalmente llegar al detalle
 de los componentes individuales como motores, bombas, brújula, funciones del capitán, etc.
Con esto, pueden ahondar cuanto sea necesario aprender a utilizar ERPNext.

A mi me gusta llevar un órden específico para poder mejor referirme a algún tema, por lo 
tanto lo he estructurado con numeración por niveles, separado por decimales. Cada módulo 
es el nivel 1, llevando solamente un numero entero. El nivel 2 lo representa el conjunto 
del numero de nivel uno, separado por un punto, y luego otro numero que inicia la cuenta 
ordinal del tema dentro del modulo.
Ustedes podrán referirse rápidamente a un tema específico por la numeración.
Cada sub-tema se separa por un punto decimal del numero que representa el tema padre, o principal.

### 1.3 Objetivos del Módulo 1
- Como acceder o instalar y configurar ERPNext
El usuario utiliza cualquier navegador web para poder gestionar todo lo relacionado con el sistema.

Esto puede correr localmente en una máquina Linux, o en un servidor virtual en cualquier 
sistema operativo.

Idealmente, puede correr en un servidor con una direccion de IP pública, para poder acceder
 al servicio desde cualquier dispositivo o lugar. (Ordenador, Smartphone, Tablet)

Este modulo se enfoca en aprender a instalarlo, configurarlo y usar esta instancia ya 
instalada de ERPNext, para satisfacer las necesidades de contabilidad y administración de una empresa.

### 1.4 Obtenga una Instancia de ERPNext

#### 1.4.1 Cuenta de prueba en erpnext.com
La forma más rápida y facil es aperturando una cuenta en [erpnext.com](https://www.erpnext.com)
Media vez haya completado la configuración de este método, vaya al Módulo 2
#### 1.4.2 - Instalación local en cualquier sistema operativo - VirtualBox
La segunda forma más fácil es descargando una imagen virtual pre-instalada para usar con VirtualBox.
Descargue VirtualBox desde [aquí](https://www.virtualbox.org/)
Siendo ERPNext un software de licencia 
[Licencia de código abierto](https://es.wikipedia.org/wiki/Licencia_de_c%C3%B3digo_abierto),
 se puede descargar directamente desde este sitio y utilizar para cualquier propósito permitido en la licencia:
[https://erpnext.com/download](https://erpnext.com/download)
Corre VirtualBox, importa la aplicación e inicia el servidor.
Asegurese de configurar las tarjetas virtuales de redes de la maquina virtual adecuadamente.
Yo utilizo una conexion de puente a mi conexión WiFi existente en una MAC, para que obtenga una IP
de mi router. De esta manera, puedo acceder con una dirección local mediante mi navegador.

## Módulo 2: Uso Básico

En este módulo conoceremos como operar el programa, como configurar lo más básico e importante,
 como encontrar ayuda a preguntas específicas y exploraremos el concepto de los 
 Tipos de Documentos o DocTypes. El resto del modulo será la exploratoria inicial de los 
 módulos del programa para
 
 * Contabilidad
 * Recursos Humanos
 * Almacén o Inventario
 * Compras
 * Ventas
 * CRM (Gestión de Clientes)
 * Manufactura
 * Proyectos
 * Bienes (Activos)
 * Sitio Web

### 2.0 Objetivos del Módulo 2

- Operacion básica del marco Frappé/ ERPNext
- Configurar ERPNext para el manejo de productos y servicios para la compra o venta
- Configurar las cuentas contables, y categorias de productos y servicios
- Administrar proveedores y clientes
- Hacer un ciclo de compra (Desde cotizar, hasta Pagar)
- Hacer un ciclo de venta (Desde obtener una iniciativa, hasta recibir el pago del cliente)
- Administrar inventarios

### 2.1 Operación Básica
#### 2.1.1 Como Hacer login ([Video 002](https://youtu.be/Znj-Fy_BRwA))
#### 2.1.2 Configure su usuario ([Video 003](https://youtu.be/tdKe0_IM1DA))
##### 2.1.2.0 Configure iconos del escritorio de trabajo ([Video 004](https://youtu.be/ZJu6lH4DGh4))
##### 2.1.2.1 Agregue usuario (Video 005)
#### 2.1.3 El marco de Frappé ([Video 006](https://youtu.be/DjkP1ie9D3k))
* Imagenes
* Archivos Adjuntos
* Asignaciones
* Etiquetas
* Usuarios
* Compartiendo
* Momento de creación y edición
* Comentarios
* Botones de acción específicos por tipo de documento
* El botón de **Hacer** (Make)
* Duplicacion de documentos
	Considero esta característica particular de ERPNext una de las más útiles para transacciones
	diarias, porque permite copiar datos desde un tipo de documento existente como una orden de compra
	y crear una nueva con los mismos productos, solo para cambiar montos y fechas o cualquier otro
	parametro para ajustarse a esa nueva instancia particular del documento nuevo.
	
##### 2.1.3.1 Doctypes o tipos de documentos. Principales y de apoyo (Video 007)
Example: Un tipo de documento principal es uno como Artículo o Factura de Venta. Un tipo de documento
de apoyo es un Atributo de Articulo o un Articulo de Factura de Venta.

* Usuario
* Articulo
* Precio de Articulo
* Personalizando (Agregando campos a la medida)
* Secuencias y series

#### 2.1.4 Dónde encontrar soporte y ayuda (Video 008)
[Documentacion](https://erpnext.org/docs/user/manual)
[Canal de Videos YouTube (Inglés) - en](https://www.youtube.com/c/erpnext)
[Canal de Videos YouTube en Español - es](https://www.youtube.com/playlist?list=PLp25mpSQVMLcpSEVkQmuH0piDVeHIEIX8)
[Foro de discusión (Inglés) - en](https://discuss.erpnext.com/)
[Capítulos](https://erpnext.org/chapters)

### 2.2 Modulos del programa
#### 2.2.1 - Cuentas Contables
##### 2.2.1.1 - Compañía (Video 009)
##### 2.2.1.2 - Centros de costo (creando centros de costo) (Video 010)
##### 2.2.1.3 - Plan de cuentas o arbol de cuentas (creando cuentas) (Video 011)
##### 2.2.1.4 - Partida contable (Asiento contable) (Video 012)
##### 2.2.1.5 - Partida de Apertura (Video 013)
#### 2.2.2 - Recursos Humanos
##### 2.2.2.1 - Empleados (Video 014)
##### 2.2.2.2 - Sucursal (Video 015)
##### 2.2.2.3 - Departamento (Video 016)
##### 2.2.2.4 - Puesto (Video 017)
#### 2.2.3 - Almacén o Inventario
##### 2.2.3.1 - Grupos de productos (creando grupos) (Video 018)
##### 2.2.3.2 - Bodegas (Video 019)
##### 2.2.3.3 - Artículos o productos (Video 020)
	La importancia de la casilla de verificación "Mantener Stock" o no!
#### 2.2.4 - Compras
##### 2.2.4.1 - Agregar un proveedor (Video 021)
##### 2.2.4.2 - Modificar proveedores  (Video 022)
##### 2.2.4.3 - Ingresar cotizaciones de proveedores  (Video 023)
##### 2.2.4.4 - Ingresar una compra (Video 024)
##### 2.2.4.5 - Realizar una compra con cotización, orden de compra, recibo de compra, factura y pago  (Video 025)
#### 2.2.5 - Ventas
##### 2.2.5.1 - Agregar un cliente  (Video 026)
##### 2.2.5.2 - Modificar clientes  (Video 027)
##### 2.2.5.3 - Ingresar cotizaciones para clientes  (Video 028)
##### 2.2.5.4 - Realizar una venta  (Video 029)
##### 2.2.5.5 - Ciclo completo - Realizar una venta con cotización, orden de venta, nota de entrega, factura, cobro y pago  (Video 030)
#### 2.2.6 - CRM (Manejo de Recursos: Clientes)
##### 2.2.6.1 - Uso del modulo de CRM para incrementar las ventas y la atención al cliente  (Video 031)
##### 2.2.5.2 - Iniciativas y Oportunidades (Video 032)
##### 2.2.5.3 - Campañas (Video 033)
#### 2.2.7 - Manufactura
##### 2.2.7.1 - Listado de materiales (Video 034)
	Para manufactura o subcontratación
#### 2.2.8 - Proyectos
##### 2.2.8.1 - Proyecto interno con tareas y progreso (Video 035)
#### 2.2.9 - Bienes
##### 2.2.7.2 Categoria de Bienes o Activos (Video 036)
##### 2.2.7.1 Creando un Bien o Activo (Video 037)
#### 2.2.10 - Sitio Web
##### 2.2.10.1 - Creando una Pagina Web (Video 038)
### 2.3 Conclusión Modulo 2

En este módulo hemos aprendido lo más importante de ERPNext.
Vimos la operativa básica del programa: hacer login, configurar su usuario, configurar sus iconos del escritorio, seleccionar su idioma, acceder al menu de configuración del programa en donde agregamos un usuario.
También conocimos el importantisimo marco Frappé, que es lo que hace tan poderoso a ERPNext,
 con sus tipos de documentos principales y de apoyo, y su funcionalidad que permite asignar 
 documentos a otros usuarios, adjuntar archivos a estos documentos, compartir documentos 
 individuales cuyos permisos estan restringidos a ciertos usuarios, llevar seguimiento 
 cronológico de las actividades realizadas sobre un DocType y sus autores así como los 
 comentarios que se pueden colocar directamente al DocType.  También vimos donde encontrar 
 soporte y ayuda.

Luego iniciamos nuestra exploracion de los modulos de contabilidad, creando una compañía,
creando los centros de costo, creando cuentas contables y conociendo como se crean partidas contables.
Vimos el módulo de recursos humanos donde creamos el primer empleado.  Luego pasamos al 
modulo de bodegas o almacén, donde aprendimos la importancia de agrupar productos, vimos
un ejemplo de un esquema de codificacion, creamos un par de bodegas y luego aprendimos a
crear articulos. El artículo es la base más importante del sistema ERPNext.

Posteriormente pasamos a conocer el modulo de compras donde creamos un proveedor, modificarlo,
 hacer la primera cotizacion, luego una compra directa, y finalmente una compra mas formal con 
 cotizacion, orden de compra, recibo de compra, factura y pago

Luego vimos lo mismo solamente que en el modulo de Ventas, en donde agregamos un cliente,
 modificamos un cliente, ingresamos una cotización al cliente, luego realizamos nuestra primer
 venta directa, y luego realizamos una venta mas formal.

Por ultimo vimos el modulo de CRM o manejo de clientes, que nos permite mejorar la atencion
al cliente, crear campañas publicitarias, y rastrear las iniciativas hasta que se convierten 
en clientes.

## Módulo 3: Uso Intermedio

TK #Pendiente de escribir procedimiento
1.5.2 - Instalación en servidor remoto