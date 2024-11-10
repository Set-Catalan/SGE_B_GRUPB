# GESTIÓN DEL RESTAURANTE  
**The Original Beef of Chicagoland**

**Fecha:** 10_11_24  
**Nombres y Apellidos:** Akasha Karam, Adriana Sanchez, Set Catalan y Oscar Fernandez  

## Índice

0. Introducción  
1. Empleados  
2. Ventas  
3. Compras  
4. Puntos de Venta  
5. Eventos  
6. Calendario  
7. Costos  
8. Planificación  
9. Licencias de Odoo  
10. Comparativa de ERP  
11. Problemas Encontrados  

## Introducción

En este proyecto se presenta la historia de Carmy, un joven chef que desea transformar un restaurante de baja calidad, **The Original Beef of Chicagoland**, en un restaurante de lujo. Tras trabajar en un restaurante de alta gama, Carmy decide asumir la gestión del negocio familiar, que se encuentra en una situación complicada, ofreciendo principalmente sándwiches de calidad baja.

El objetivo de Carmy es mejorar todos los aspectos del restaurante, desde el servicio hasta la calidad de los productos, para finalmente renombrarlo como **The Bear**. Para ello, se enfrenta a varios retos, como gestionar la clientela, controlar los pagos y administrar a su equipo de trabajo.

Con el fin de optimizar la gestión, Carmy decide solicitar nuestra ayuda. Hemos implementado módulos de Odoo que facilitarán la administración del restaurante. Este enfoque integral permitirá a Carmy gestionar eficientemente el restaurante y llevar a cabo la transformación necesaria para cumplir con su visión de negocio.

## Módulos Documentados

- **Empleados (A):** Gestión del personal, contrataciones y control de horarios.
- **[Ventas (B):](Ventas.md)** Control de las ventas y la rentabilidad.
- **Compras (C):** Gestión de inventarios y proveedores.
- **Puntos de venta (D):** Optimización del proceso de ventas y atención al cliente.
- **Eventos (A):** Organización de eventos especiales en el restaurante.
- **[Calendario (B):](Calendario.md)** Planificación de reservas y eventos.
- **Costos (C):** Control de los costos operativos.
- **Planificación (D):** Estrategias a corto y largo plazo para el crecimiento del negocio.

## Licencias de Odoo

Odoo ofrece varios tipos de licencias que permiten diferentes niveles de acceso y opciones de personalización para los usuarios. Las principales son:

- **Odoo Community (Gratuita):** Versión de código abierto que permite el uso de funciones básicas, ideal para pequeñas empresas con necesidades limitadas de personalización y funcionalidad.

- **Odoo Enterprise (Pago):** Ofrece funcionalidades avanzadas, soporte técnico y una mayor integración, adecuada para empresas en crecimiento que requieren más funcionalidades y soporte.

- **Odoo Online (SaaS):** Es una versión en la nube de Odoo Enterprise, pensada para empresas que prefieren no gestionar su propia infraestructura y desean actualizaciones automáticas.

Cada licencia presenta distintas ventajas según el tamaño de la empresa y sus requerimientos de personalización y soporte.


## Comparativa de ERP

A continuación, se presenta una comparación entre Odoo y otros dos ERP populares, **SAP Business One** y **Microsoft Dynamics 365**, para identificar la mejor opción para la gestión del restaurante:

| ERP                    | Ventajas                                                                                   | Desventajas                                                                            |
|------------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| **Odoo**               | - Versión gratuita disponible (Community).                                                 | - La versión gratuita tiene funcionalidades limitadas.                                 |
|                        | - Fácil de personalizar para ajustarse a las necesidades del negocio.                       | - Algunas funciones avanzadas solo están en la versión de pago (Enterprise).           |
|                        | - Costo accesible en comparación con otros ERP.                                            |                                                                                        |
| **SAP Business One**   | - Funcionalidades avanzadas para una gestión detallada y personalizada.                     | - Costo inicial elevado, lo cual puede no ser ideal para pequeñas empresas.            |
|                        | - Muy flexible, permite gran control sobre el inventario, ventas y finanzas.                | - Curva de aprendizaje alta; requiere capacitación adicional.                          |
| **Microsoft Dynamics 365** | - Integración completa con herramientas de Microsoft (Office, Teams, etc.).          | - Costo intermedio, aunque puede resultar elevado para algunas pequeñas empresas.      |
|                        | - Interfaz amigable y fácil de usar, lo cual facilita el aprendizaje del personal.          | - Las personalizaciones pueden requerir ayuda de consultores, lo cual añade costos.     |

**Odoo** es una opción asequible con una versión gratuita (Community) y fácil de personalizar, pero su versión gratuita tiene limitaciones y algunas características avanzadas solo están disponibles en la versión de pago (Enterprise).

**SAP Business One** ofrece funcionalidades avanzadas y un control detallado sobre el negocio, ideal para empresas con necesidades complejas, pero tiene un costo elevado y una curva de aprendizaje alta, lo que puede requerir capacitación adicional.

**Microsoft Dynamics** 365 destaca por su integración con herramientas de Microsoft, facilitando la adopción del sistema, aunque su costo puede ser elevado para pequeñas empresas y las personalizaciones pueden generar costos adicionales debido a la necesidad de consultores externos.

## Problemas Encontrados

Uno de los problemas encontrados durante la instalación de Odoo fue que, al intentar configurarlo, se crearon dos bases de datos en lugar de una sola. Para solucionar este inconveniente, simplemente abrí Odoo, fui a la sección de Bases de Datos y desde allí eliminé la base de datos adicional que se había creado.

Además, al principio no sabía cómo visualizar las aplicaciones instaladas ni cómo realizar modificaciones. Después de investigar, descubrí que la opción de la  configuración era un modulo dentro de base de datos.

