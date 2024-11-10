# GESTIÓN DEL RESTAURANTE  
**The Original Beef of Chicagoland**

**Fecha:** 10_11_24  
**Nombres y Apellidos:** Akasha Karam, Adriana Sanchez, Set Catalan y Óscar Fernandes  

## Índice

0. [Introducción](#introducción)  
1. [Nosotros](#nosotros)  
2. [Módulo de Empleados](#módulo-de-empleados)  
3. [Módulo de Ventas](#módulo-de-ventas)  
4. [Módulo de Compras en Odoo](#Módulo-de-Compras-en-Odoo)  
5. [Módulo de Puntos de Venta](#módulo-de-puntos-de-venta)  
6. [Módulo de Eventos](#módulo-de-eventos)  
7. [Módulo de Calendario](#módulo-de-calendario)  
8. [Módulo de Gastos en Odoo](#Módulo-de-Gastos-en-Odoo)  
9. [Módulo de Planificación](#módulo-de-planificación)  
10. [Licencias de Odoo](#licencias-de-odoo)  
11. [Comparativa de ERP](#comparativa-de-erp)  
12. [Problemas Encontrados](#problemas-encontrados)  


## Introducción

En este proyecto se presenta la historia de Carmy, un joven chef que desea transformar un restaurante de baja calidad, **The Original Beef of Chicagoland**, en un restaurante de lujo. Tras trabajar en un restaurante de alta gama, Carmy decide asumir la gestión del negocio familiar, que se encuentra en una situación complicada, ofreciendo principalmente sándwiches de calidad baja.

El objetivo de Carmy es mejorar todos los aspectos del restaurante, desde el servicio hasta la calidad de los productos, para finalmente renombrarlo como **The Bear**. Para ello, se enfrenta a varios retos, como gestionar la clientela, controlar los pagos y administrar a su equipo de trabajo.

Con el fin de optimizar la gestión, Carmy decide solicitar nuestra ayuda. Hemos implementado módulos de Odoo que facilitarán la administración del restaurante. Este enfoque integral permitirá a Carmy gestionar eficientemente el restaurante y llevar a cabo la transformación necesaria para cumplir con su visión de negocio.

## Módulos Documentados

- **Empleados (A):** Gestión del personal, contrataciones y control de horarios.  
- **Ventas (B)** Control de las ventas y la rentabilidad.  
- **Compras (C):** Gestión de inventarios y proveedores.  
- **Puntos de venta (D):** Optimización del proceso de ventas y atención al cliente.  
- **Eventos (A):** Organización de eventos especiales en el restaurante.  
- **Calendario (B)** Planificación de reservas y eventos.  
- **Costos (C):** Control de los costos operativos.  
- **Planificación (D):** Estrategias a corto y largo plazo para el crecimiento del negocio.  

# Nosotros

Mi nombre es Akasha y fui responsable de crear y configurar Odoo para este proyecto. Instalé todos los módulos necesarios y configuré los módulos de **Ventas** y **Calendario** para el restaurante.

Mi trabajo consistió en:
- Configurar los módulos para que se adaptaran a las necesidades del restaurante.
- Documentar cómo funciona el sistema, explicando cada proceso de forma clara.
- Incluir capturas de pantalla para ayudar a entender mejor cómo se usan los módulos de Ventas y Calendario.
- Crear una rama para mí desde la terminal utilizando el comando `git checkout -b akasha`. Este comando crea una nueva rama y automáticamente cambia a ella.

Soy Óscar y he configurado los módulos de **Compras** y **Costos**.

Lo que he realizado:
- Documentar una demonstración del módulo de Comprar, con un ejemplo de producto.
- Documentar una demonstración del módulo de Costos.
- Añadir las capturas de pantalla de Odoo para ayudar en la compreensión de ambos módulos.

# Módulo de Empleados

#### Para crear la ficha de un empleado en Odoo, sigue estos pasos.

1. Accede a Odoo: Inicia sesión como administrador.

![alt text](/img_empleado/empleado_1.png)

2. Accede a la sección de Empleados: Encuentra el botón de "Empleados" y haz clic en él.
![alt text](/img_empleado/Empleado_2.png)

3. Crear un nuevo empleado: Haz clic en "Nuevo" para abrir un nuevo formulario.
![alt text](/img_empleado/Empleado_3.png)

4. Completa la información necesaria: Rellena todos los campos requeridos, como nombre, posición de trabajo, número de teléfono de trabajo, dirección de correo electrónico, etc.
![alt text](/img_empleado/Empleado_4.png)

5. Guardar los cambios: Después de completar toda la información, guarda los cambios.
![alt text](/img_empleado/Empleado_5.png)
![alt text](/img_empleado/Empleado_6.png)


# Módulo de Ventas 

En Odoo, el módulo de ventas (*Sales*) es fundamental para gestionar el proceso de ventas de una empresa. Permite la creación, seguimiento y administración de presupuestos y pedidos de clientes de manera organizada. Con este módulo, puedes:

### Funcionalidades principales

- **Crear presupuestos y órdenes de venta**: Los representantes de ventas pueden generar presupuestos rápidamente, que luego pueden convertirse en órdenes de venta si el cliente los aprueba.
  
- **Gestión de clientes y productos**: El módulo permite almacenar toda la información relevante sobre los clientes y productos. Esto incluye precios, disponibilidad de inventario y condiciones de pago, facilitando el proceso de ventas.

- **Automatización del flujo de trabajo**: Desde la confirmación de un pedido hasta la entrega y facturación, el módulo automatiza tareas, lo que optimiza el tiempo y reduce errores.

- **Análisis y reportes**: Odoo proporciona análisis de ventas, que ayudan a identificar tendencias, realizar previsiones y tomar decisiones estratégicas.

### Crear una factura de venta

Para crear una factura de venta:

1. Haz clic en **"Crear"**. En el campo **Cliente**, selecciona al empleado que comprará el producto.

![Crear una factura de venta](/imagen_ventas_calendaio/Hacer%20Factura%201.JPG).

2. En la sección de productos, busca "macarrones" en la lista de productos o añádelo manualmente si no está registrado. Ingresa la cantidad de macarrones que el empleado está comprando. Odoo calcula automáticamente el total del presupuesto en función del precio y la cantidad del producto.

![Crear una factura de venta](/imagen_ventas_calendaio/Hacer%20Factura%202.JPG).

### Acciones disponibles con las facturas

- **Opciones principales**:
  - **Crear factura**: Genera una factura para el pedido, que puedes gestionar en contabilidad.
  - **Enviar por correo electrónico**: Envía el pedido al cliente ![Enviar por correo electrónico](/imagen_ventas_calendaio/Envio%20por%20email.JPG).
  - **Vista previa**: Visualiza el pedido como lo vería el cliente ![Vista previa](/imagen_ventas_calendaio/Vista%20previa.JPG).
  - **Cancelar**: Cancela el pedido si es necesario ![Cancelar](/imagen_ventas_calendaio/Cancelar.JPG).

- **Estados del pedido**:
![Estados del pedido](/imagen_ventas_calendaio/Estado%20de%20pedido.JPG).
  - **Presupuesto**: Aún sin confirmar.
  - **Presupuesto enviado**: Enviado al cliente, no confirmado.
  - **Pedido de venta**: Confirmado como venta 

- **Información del pedido**:
![Información del pedido](/imagen_ventas_calendaio//Info%20del%20pedido.JPG).
  - **Número de pedido**: Identificador único.
  - **Cliente**: Nombre del cliente.
  - **Fecha de pedido**: Fecha de creación.
  - **Lista de precios**: Tarifa de precios aplicada.
  - **Condiciones de pago**: Términos de pago 

### Líneas del pedido

Las líneas del pedido incluyen productos o servicios, con detalles como cantidad, precio unitario, impuestos (ej. 21%) y el importe total.

### Opciones adicionales
![Opciones adicionales](/imagen_ventas_calendaio/Opciones%20adicionales.JPG).

- **Agregar un producto**: Añade más productos al pedido.
- **Agregar una sección**: Organiza productos en categorías.
- **Agregar una nota**: Incluye notas adicionales.
- **Catálogo**: Accede al catálogo para seleccionar productos adicionales.

# Módulo de Compras en Odoo

El módulo de Compras en Odoo está diseñado para gestionar de manera eficiente el proceso de adquisición de productos y servicios de la empresa. Permite desde la creación y envío de órdenes de compra hasta la recepción de productos y el pago a los proveedores.

## Opciones del Módulo de Compras

Al entrar en el apartado de compras de Odoo, puedes ver diversas opciones como pedidos realizados, productos disponibles, informes. 

## Realización de Pedidos

Para realizar un pedido, sigue estos pasos:

Haz clic en el botón "Nuevo".

![alt text](<Image Compra/Nuevacompra.png>)

Al crear un nuevo pedido, agrega el producto deseado, por ejemplo, Queso.

![alt text](<Image Compra/Agregar.png>)

Especifica la: cantidad, precio unitario, impuestos aplicables, importe total.

![alt text](<Image Compra/Pedidodecompra.png>)
![alt text](<Image Compra/Queso.png>)

Los pedidos pueden configurarse para que se realicen automáticamente en ciertos períodos, lo que facilita la gestión de compras recurrentes.

Al realizar el pedido, tienes la opción de crear una factura para el pedido gestionado.

![alt text](<Image Compra/Factura.png>)

## Gestión de Proveedores

Odoo también incluye un apartado para gestionar proveedores, con funciones detalladas que permiten organizar y controlar la relación con tus proveedores.

![alt text](<Image Compra/Proveedor.png>)

# Módulo de Puntos de Venta

---

Con el módulo puntos de venta puedes controlar las ventas de los diferentes locales de tu empresa.

Para utilizarlo, primero debes añadir los diferentes puntos de venta.

Para hacerlo, debes pulsar el botón "Nuevo".

![alt text](img/Punt_de_venda(1).png)

<br>

Y después poner un nombre descriptivo para cada punto de venta.

![alt text](img/Punt_de_venda(2).png)

<br>

Una vez creados los puntos de venta, haz clic en el botón "Kanban".

![alt text](img/Punt_de_venda(3).png)

<br>

Y selecciona el botón donde dice "Abrir caja registradora".

![alt text](img/Punt_de_venda(4).png) 

<br>

Para comenzar una apertura, debes indicar una cantidad de apertura en la caja.

![alt text](img/Punt_de_venda(5).png) 

<br>

Una vez estés dentro, puedes seleccionar los productos que vendas o los servicios que ofrezcas.

![alt text](img/Punt_de_venda(6).png) 

<br>

Y puedes ponerles el valor que desees.

![alt text](img/Punt_de_venda(7).png) 

<br>

También puedes indicar el método de pago, ya sea en efectivo, con tarjeta o a cuenta del cliente.

![alt text](img/Punt_de_venda(8).png)

<br>

Por último, se generará un tiquet con los detalles de la venta.

![alt text](img/Punt_de_venda(9).png)

<br>

Arriba a la izquierda, tienes este botón que te sirve para añadir más cajas registradoras en caso de que lo necesites.

![alt text](img/Punt_de_venda(10).png) 

<br>

Para finalizar la sesión, debes hacer clic en el botón de las tres líneas y donde dice "Cerrar caja registradora".

![alt text](img/Punt_de_venda(11).png)

<br>

Eso te mostrará un resumen de la venta diaria.

![alt text](img/Punt_de_venda(12).png)


# Módulo de Eventos

#### Para crear un evento en Odoo, sigue estos pasos.

1. Accede a la sección de eventos: Encuentra el botón de "Eventos" y haz clic en él.
![alt text](/img_Eventos/1.png)

2. Crea un nuevo evento: Haz clic en el botón "Nuevo".
 ![alt text](/img_Eventos/2.png)

3. Rellena la información del evento: Completa los campos obligatorios como el nombre del evento, la fecha y la ubicación. También puedes agregar detalles adicionales como el horario, las sesiones, etc.
![alt text](/img_Eventos/3.png)

4. Configura las opciones de venta de entradas: En la sección de Ventas, puedes configurar la venta de entradas, establecer precios y condiciones especiales.

5. Publica y promociona el evento: Utiliza la integración con el sitio web de Odoo para publicar el evento y promocionarlo.

6. Gestiona los asistentes: Configura notificaciones y recordatorios para los asistentes, y gestiona las inscripciones y los pagos.
![alt text](/img_Eventos/4.png)

![alt text](/img_Eventos/5.png)

# Módulo de Calendario

El módulo de Calendario es esencial para gestionar reuniones, citas y eventos dentro de una organización. Este módulo permite organizar y coordinar el tiempo de los empleados de forma eficiente, facilitando la colaboración y la programación de actividades. A continuación, se explican sus principales características:

## Gestión de eventos y citas

### Crear eventos y citas
Se pueden programar eventos y citas en el calendario, especificando la fecha, la hora, el lugar y los participantes. 

1. Haz clic en el botón **Crear** en la esquina superior izquierda para crear un nuevo evento. Luego, introduce el título, fecha, hora, lugar y añade los participantes al evento.

![Crear Evento](/imagen_ventas_calendaio/Evento.1.JPG).

2. Las citas también se pueden gestionar desde la sección de citas ubicada en la barra superior.

![Crear Cita](/imagen_ventas_calendaio/Citas.JPG).

### Invitación a usuarios
Es posible invitar a otros empleados o incluso a clientes a eventos específicos, quienes recibirán notificaciones para confirmar su asistencia a través de SMS o correo electrónico. Al crear eventos, hay una opción que permite invitar a empleados o clientes.

![Invitar a usuarios](/imagen_ventas_calendaio/invitacion%20a%20usuario.JPG).

### Sincronización con otros calendarios
El módulo permite sincronizar eventos con otros calendarios externos como **Google Calendar** y **Outlook**, centralizando la información de programación.

![Sincronización con otros calendarios](/imagen_ventas_calendaio/Sincronizar%20calendario.JPG).

- Ve a **Configuración > Sincronización**. Desde allí, puedes conectar tu calendario de Odoo con Google Calendar o Outlook para la sincronización de eventos.

## Visualización 

### Vistas de calendario
El calendario se puede ver en diferentes formatos, como vista diaria, semanal, mensual o por año, facilitando la organización de la agenda.

![Vistas de calendario](/imagen_ventas_calendaio/Vista.JPG).

## Automatización de recordatorios

### Recordatorios automáticos
Los usuarios pueden configurar recordatorios automáticos que envían notificaciones antes de cada evento, ayudando a que los participantes estén preparados a tiempo.

![Recordatorios automáticos](/imagen_ventas_calendaio/Recodatorio.JPG).

# Módulo de Gastos en Odoo

El módulo de Gastos en Odoo ayuda a gestionar y controlar los gastos de los empleados. Permite registrar, aprobar y reembolsar los gastos de manera fácil, ayudando a llevar un seguimiento claro de los recursos.

## Gestión de Gastos

Puedes registrar un gasto indicando los detalles importantes, como el tipo de gasto, la cantidad, y agregar un recibo o factura como comprobante. Haz clic en el botón “Nuevo” para registrar un nuevo gasto. Luego, completa el tipo de gasto, la cantidad, la fecha, y añade una copia del recibo si es necesario, además del empleado relacionado y por si ha sido pagado por él mismo o por una compañia.

![alt text](<Image Gastos/Gastos.png>)
![alt text](<Image Gastos/Ejemplogasto.png>)

## Aprobación de Gastos

Una vez registrado el gasto, puedes enviarlo para aprobación. Dependiendo de la configuración, puede necesitar la aprobación de un gerente. Para enviar el gasto a aprobación, selecciona el gasto registrado y haz clic en “Enviar al gerente”.

![alt text](<Image Gastos/GastoGerente.png>)

Al gerente le aparecera la opción de aprobar.

![alt text](<Image Gastos/Aprobar.png>)

## Reembolso de Gastos

Después de que un gasto es aprobado, se puede iniciar el reembolso. Los empleados pueden ver el estado del reembolso en el sistema.

![alt text](<Image Gastos/Crearpago.png>)

## Informes de Gastos

Odoo ofrece informes sobre los gastos, permitiendo ver datos como el tipo de gasto, departamento, empleado, y más.

![alt text](<Image Gastos/Informe.png>)

# Módulo de Planificación

---

Con el módulo de planificación puedes organizar a tus trabajadores para saber qué hacen y cuándo lo hacen.  
Este módulo te ayudará mucho a organizarte a ti y a tus empleados.

Para utilizar el módulo, primero debemos crear y asignar turnos a los empleados.

Para hacerlo, debes pulsar el botón "Nuevo" situado a la izquierda.

![alt text](img/Planificació(1).png)

<br>

Se nos abrirá esta pestaña:

![alt text](img/Planificació(2).png) 

<br>

Aquí podemos seleccionar qué empleado hará el turno, qué rol desempeñará, cuándo lo hará y el tiempo que estará realizando el turno.

![alt text](img/Planificació(3).png) 

![alt text](img/Planificació(4).png) 

<br>

Después de asignar los turnos a los empleados, puedes gestionarlos con diferentes formatos:

En el formato diagrama de Gantt

![alt text](img/Planificació(5).png) 

<br>

En el formato calendario

![alt text](img/Planificació(6).png) 

<br>

En el formato lista

![alt text](img/Planificació(7).png) 

<br>

En el formato kanban

![alt text](img/Planificació(8).png) 

<br>

Y en el formato gráfica.

![alt text](img/Planificació(9).png)


## Licencias de Odoo

Odoo ofrece varios tipos de licencias que permiten diferentes niveles de acceso y opciones de personalización para los usuarios. Las principales son:

- **Odoo Community (Gratuita):** Versión de código abierto que permite el uso de funciones básicas, ideal para pequeñas empresas con necesidades limitadas de personalización y funcionalidad.
- **Odoo Enterprise (Pago):** Ofrece funcionalidades avanzadas, soporte técnico y una mayor integración, adecuada para empresas en crecimiento que requieren más funcionalidades y soporte.
- **Odoo Online (SaaS):** Es una versión en la nube de Odoo Enterprise, pensada para empresas que prefieren no gestionar su propia

## Comparativa de ERP
A continuación, se presenta una comparación entre Odoo y otros dos ERP populares, SAP Business One y Microsoft Dynamics 365, para identificar la mejor opción para la gestión del restaurante:

| ERP                     | Ventajas                                                                 | Desventajas                                                                 |
|-------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| **Odoo**                | - Versión gratuita disponible (Community).                               | - La versión gratuita tiene funcionalidades limitadas.                      |
|                         | - Fácil de personalizar para ajustarse a las necesidades del negocio.     | - Algunas funciones avanzadas solo están en la versión de pago (Enterprise). |
|                         | - Costo accesible en comparación con otros ERP.                          |                                                                             |
| **SAP Business One**     | - Funcionalidades avanzadas para una gestión detallada y personalizada. | - Costo inicial elevado, lo cual puede no ser ideal para pequeñas empresas.  |
|                         | - Muy flexible, permite gran control sobre el inventario, ventas y finanzas. | - Curva de aprendizaje alta; requiere capacitación adicional.              |
| **Microsoft Dynamics 365** | - Integración completa con herramientas de Microsoft (Office, Teams, etc.). | - Costo intermedio, aunque puede resultar elevado para algunas pequeñas empresas. |
|                         | - Interfaz amigable y fácil de usar, lo cual facilita el aprendizaje del personal. | - Las personalizaciones pueden requerir ayuda de consultores, lo cual añade costos. |


- Odoo es una opción asequible con una versión gratuita (Community) y fácil de personalizar, pero su versión gratuita tiene limitaciones y algunas características avanzadas solo están disponibles en la versión de pago (Enterprise).

- SAP Business One ofrece funcionalidades avanzadas y un control detallado sobre el negocio, ideal para empresas con necesidades complejas, pero tiene un costo elevado y una curva de aprendizaje alta, lo que puede requerir capacitación adicional.

- Microsoft Dynamics 365 destaca por su integración con herramientas de Microsoft, facilitando la adopción del sistema, aunque su costo puede ser elevado para pequeñas empresas y las personalizaciones pueden generar costos adicionales debido a la necesidad de consultores externos.