# Usuarios
## Crear, administrar y visualizar usuarios
## Responsabilidades
- Crear usuarios
- Actualizar datos de usuarios
- Dar de baja usuarios
- Bloquear Usuarios

# Autenticación
## Gestionar la autenticación de los usuarios
- Validar credenciales
- Iniciar sesión
- Cerrar sesión

# Roles 
## Gestionar y asignar los diferentes roles y permisos dentro del sistema
- Asignar roles a usuarios
- Asignar roles
- Asignar permisos
- Verificar autorización 
- Desplegar visualmente una lista de roles

# Permisos 
## Craer, gestionar los diferentes permisos que se conceden dentro del sistema
- Asignar permisos a roles
- Asignar permiso a usario
- Editar permiso a usario
- Eliminar permiso a usuario
- Desplegar visualmente una lista de permisos

# Autorización
## Gestionar, definir y asignar los tipos de autorización que cada usuario puede
- Definir y crear los tipos de autorizaciones de acuerdo al rol de usuario
- Consultar autorizaciones de usuarios
- Crear una sesiones de usuario
- Crear tokens para autorizacion de consulta de informacion vía API
- Seleccionar usuarios y su capacidad que tiene dentro del sistema para crear, consultar o actualizar información sensible de un producto particular
- Delegar autorización a un usuario determinado para modificar el inventario

# Ventas
## Crear, administrar y visualizar ventas
## Responsabilidades
- Iniciar una nueva venta
- Agregar productos a la venta
- Modificar la cantidad de un producto antes de completar la venta
- Retirar productos de una venta en curso
- Calcular subtotal, descuentos y total
- Registrar el pago
- Completar la venta
- Cancelar una venta
- Consultar ventas por período
- Consultar el detalle de una venta
- Extraer información de ventas y darle formato apropiado para servirlo como servicio API

# Productos
## Crear, administrar y visualizar productos
## Responsabilidades
- Ingresar datos de un nuevo producto
- Actualizar datos de productos
- Dar de baja productos
- Adjuntar producto a una categoría existente
- Mostar el stock de un producto x, de acuerdo a la sucuersal en la que está presente
- Actualizar el stock de un producto en particular
- Actualizar el tipi estado disponible o no disponible  de productos
- Modificar el stock de producto  X por daño en ese producto
- Modificar el stock del producto por faltante en sucursal de ese producto
- Adjuntar nuevo producto a Bodega
- Visualizar la fecha de última modifición del stock de un producto determinado por el usuario
- Desplegar visualmente una lista de productos
- Desplegar visualmente una lista en un conjunto de productos en una sucursal existente

# Categorías
# Definir, crear y actualizar categorías
## Responsabilidades
- Crear una nueva categoria
- Desplegar visualmente un lista de categorías
- Desplegar visualmente una lista de productos de acuerdo a una categoría definida

# Bodega
## Crear, administrar y visualizar productos existentes en Bodega
## Responsabilidades
- Crear el stock principal de un producto en particular que existe en Bódega
- Actualizar información de un producto en bódega por transferencia a una sucursal
- Actualizar el stock de un producto en particular
- Seleccionar producto en Bódega yTransferir mercancía a una sucursal
- Modificar el stock del producto por daño en ese producto
- Mostar el stock de un producto x, de acuerdo a la sucuersal en la que está presente
- Registrar mercancía dañada
- Corregir una entrada errónea
- Cancelar adición de productos a bódega
- Devolución de productos a bodega
- Desplegar visualmente el stock universal de existencias en bodega
- Desplegar visualmente el conjunto universal de productos dañados
- Desplegar visualmente la cantidad de unidades dañadas de un producto determinado
# Reportes
## Crear, administrar y visualizar reportes
## Responsabilidades
- Generar reporte de ventas por período
- Generar reporte de ventas diarias por sucursal
- Generar reporte de ventas diarias de todos las las sucursales
- Generar reporte de productos más vendidos
- Generar reporte de movimientos de inventario
- Generar reporte de stock actual en una sucursal determinada
- Generar reporte del stock de productos dañados
- Generar el reporte del stock existente de una sucursal X
- Generar un reporte del inventario universal de sucursales
- Exportar reportes autorizados a PDF
- Generar un reporte universal del estado de ventas y productos existentes de una sucursal determinada
- Generar un reporte comparativo de ventas con respecto a un monto de ventas de un período anterios de tiempo
- Generar un reporte de los movimientos realizados a esa sucursal en particular
- Generar el reporte del stock universal de las diferentes sucursales
- Generar reporte semanal de ventas para una locacion particular
- Generar un reporte de ventas para una locacion particular de acuerdo a un tiempo determinado
- Generar un reporte de los diferentes movimientos realizados en cada una de las locaciones

# Movimientos Inventario
## Crear, administrar y visualizar movimientos de historicos de la información más relevante del sistema
## Responsabilidades
- Crear un nuevo momovimiento en inventario cuando se crea un nuevo producto
- Crear un histórico cuando se ejecute un envío de producto desde Bódega, a una locacion particular
- Ajustar datos inventario por recepción de producto exixtente o nuevo producto
- Ajustar datos inventario cuando se agregan nuevos productos a una sucursal de manera directa
- Seleccionar un conjunto de históricos de acuerdo a un tiempo determinado
- Ajustar datos de inventario por robo o pérdida
- Ajustar datos de Inventario por producto dañado
- Mostrar el stock de determinado producto en una fecha seleccionada
- Seleccionar un histórico determinado de acuerdo al ID de un producto particular
- Visualizar el registro histórico de los movimientos de un producto, dado un período determinado de tiempo
- Sumar y visualizar la cantidad de unidades de un mismo producto ingresados durante determinado tiempo

# Inventario
## Gestionar los identificadores de los productos, sucursales y cantidades existentes del producto en cada una las sucursales
- Crear los registros de los identificadores de las productos, locaciones y la cantidad del producto que se crea
- Consultar stock por producto
- Consultar stock por producto y ubicación particular
- Recibir mercancía
- Transferir mercancía
- Registrar pérdidas o daños
- Realizar ajustes por conteo físico
- Consultar disponibilidad

# Ubicaciones
## Gestionar información de una sucursal determinada
- Crear ubicación
- Actualizar ubicación
- Clasificar ubicación como bodega o sucursal
- Consultar ubicaciones activas
- Generar datos de una nueva sucursal
- Actualizar datos de una sucursal existente
- Seleccionar y desplegar visualmente las diferentes sucursales administradas en el sistema