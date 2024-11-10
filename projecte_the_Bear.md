# GESTIÓN DEL RESTAURANTE  
**The Original Beef of Chicagoland**

**Fecha:** 10_11_24  
**Nombres y Apellidos:** Akasha Karam, Adriana Sanchez, Set Catalan y Oscar Fernandez  

## Índice

0. [Introducción](#introducción)  
1. [Nosotros](#nosotros)  
2. [Empleados](#empleados)  
3. [Módulo de Ventas](#módulo-de-ventas)  
4. [Compras](#compras)  
5. [Puntos de Venta](#puntos-de-venta)  
6. [Eventos](#eventos)  
7. [Módulo de Calendario](#módulo-de-calendario)  
8. [Costos](#costos)  
9. [Planificación](#planificación)  
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