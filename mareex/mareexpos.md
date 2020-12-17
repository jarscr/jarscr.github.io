![Build Status](https://img.shields.io/badge/Estado-Desarrollo-orange.svg?style=for-the-badge)

# MareexPOS

### [Regresar](https://jarscr.github.io/mareex/home#release)

## Liberaciones
### Version 4.8.7 2020-12-17
- Reporte del Dashboard por mes presente
- Reporte del Dashboard muestra error en Documento
- Reporte de ventas totales muestra los IVA's soportados por factura
- Reporte de ventas separa los documentos por moneda y por tipo, Colones y Dolares, Facturas-Tiquetes y Notas de Crédito
- Corrige: Eleventa Syncronizador "SubTotal"
- SoftHotel convierte el producto "PROPINA" en otros cargos
- Edicion de Cabys incorrecto en Ver Factura
- Reenvio de Documento a Hacienda desde Ver Factura cuando el estado es 4 (Pendiente)

### Version 4.8.6 2020-12-8
- Exoneraciones relacionadas a Clientes en SR
- Notificacion de Recepcion de Facturas
- Cabys en Factura de Compra
- Envio por SendGrid correo certificado
- Se corrige el nombre de Archivo en Recepción automatico

### Version 4.8.5 2020-11-15
- Codigos Cabys

### Version 4.8.2 2020-10-9
- Envio automatico de Notas de Crédito
- Factución muestra el tipo de documento
- Facturación muestra el total del documento + iva

### Version 4.8.1 2020-10-2
- Regenerar las lineas de recepcion
- Ajustes en reporte de recepción
- Descarga de Respaldos 


### Version 4.8.0 2020-09-17
- Generacion de consecutivos basado en historico de sistemas anteriores
- Sistema de deteccion de faltante de datos regenera el consecutivo basado en el historico
- Correccion de Reportes 
- Generación de Reportes en PDF

### Version 4.7.9 2020-09-01
- Generacion de Respaldos diarios
- Generacion de Respaldos mensuales
- Compresion de Respaldos
- Carga de Respaldos en la nube
- Registro en la base de datos de los respaldos

### Version 4.7.8 R9 2020-08-31
- Anulacion de Factura de compras



### Version 4.7.8 R8 2020-08-28
- Se agrega un correo a la factura para que se envie a esa dirección, para los casos que una factura se divide en varios cliente y esta debe ser enviada a diferentes direcciones
- Correccion reporte Compras Redondeo en Totales Gravados

### Version 4.7.8 R7 2020-08-25
- Corrección en el validador de documentos para factura de compra simplificado
- Automatizacion de Simplificado
- Corrección en el receptor para capturar los PDF


### Version 4.7.8 R6 2020-08-24

- Reporte de Gastos ampliado
- Mejora en el receptor de IMAP para agregar notas de error
- Nuevo modulo de Recepción Error que permite ver cuando no se registran los gastos

