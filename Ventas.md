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

2. En la sección de productos, busca "macarrones" en la lista de productos o añádelo manualmente si no está registrado.Ingresa la cantidad de macarrones que el empleado está comprando. Odoo calcula automáticamente el total del presupuesto en función del precio y la cantidad del producto.

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
