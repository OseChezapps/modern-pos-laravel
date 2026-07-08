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
- Asignar roles
- Asignar permisos
- Verificar autorización 

# Permisos 
## Craer, gestionar los diferentes permisos que se conceden dentro del sistema
- Asignar permiso a usario
- Editar permiso a usario
- Eliminar permiso a usuario
# Autorización
## Gestionar, definir y asignar los tipos de autorización que cada usuario puede
- Crear nuevo permiso
- Crear nuevo rol
- Asignar permisos a roles
- Asignar roles a usuarios
- Asignar permisos directos
- Renovar permisos
- Revocar permisos
- Consultar autorizaciones 

# Ventas
## Crear, administrar y visualizar ventas
## Responsabilidades
# Ventas
## Responsabilidades:
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

# Productos
## Crear, administrar y visualizar productos
## Responsabilidades
- Ingresar datos de un nuevo producto
- Actualizar datos de productos
- Dar de baja productos
- Actualizar estado de productos
- Seleccionar usuarios y su capacidad que tiene dentro del sistema para crear o actualizar información sensible del producto
- Crear nuevo producto en el módulo Bodega
- Generar la lista en un conjunto de productos en una sucursal existente

# Bodega
## Crear, administrar y visualizar productos existentes en Bodega
## Responsabilidades
- Actualizar información de producto en bódega
- Seleccionar producto en Bódega yTransferir mercancía a una sucursal
- Registrar mercancía dañada
- Corregir una entrada errónea

# Reportes
## Crear, administrar y visualizar reportes
## Responsabilidades
- Generar reporte de ventas por período
- Generar reporte de productos más vendidos
- Generar reporte de movimientos de inventario
- Generar reporte de stock actual
- Exportar reportes autorizados a PDF

# Historial Movimientos
## Crear, administrar y visualizar movimientos de historicos de la información más relevante del sistema
## Responsabilidades
- Crear un nuevo histórico cuando se crea un nuevo producto
- Crear un histórico cuando se ejecute un envío de producto desde Bódega, a una locacion particular
- Crear un histórico cuando se agregan nuevos productos a una sucursal de manera directa
- Seleccionar un conjunto de históricos de acuerdo a un tiempo determinado
- Seleccionar un histórico determinado de acuerdo al ID de un producto particular

# Stock
## Gestionar el stock de las diferentes productos pertenecientes al inventario de acuerdo a la sucursal a la que pertenecen
## Responsabilidades
- Crear el stock principal de un producto en particular que existe en Bódega
- Actualizar el stock de un producto en particular
- Mostar el stock de un producto x, de acuerdo a la sucuersal en la que está presente
- Actulizar el stock general de Bódega, cuando se hace un envío de producto X, a una una sucursal X
- Generar el reporte del stock existente de una sucursal X
- Generar el reporte del stock universal de las diferentes sucursales

# Locaciones
## Crear y actualizar datos de las diferntes suscursales administrads en el sistema
## Responsabilidades
- Crear una nueva locacion
- actualizar los datos de una locacion existente
- Generar un reporte de los diferentes movimientos realizados en cada una de las locaciones

# Inventario
## Gestionar los identificadores de los productos, sucursales y cantidades existentes del producto en cada una las sucursales
- Crear los registros de los identificadores de las productos, locaciones y la cantidad del producto que se crea
- Generar un reporte del inventario universal de sucursales

# Sucursal
## Gestionar información de una sucursal determinada
- Generar datos de una nueva sucursal
- Actualizar datos de una sucursal existente
- Generar un reporte universal del estado de ventas y productos existentes de una sucursal determinada
- Generar un reporte comparativo de ventas con respecto a un monto de ventas de un período anterios de tiempo
- Generar un reporte de los movimientos realizados a esa sucursal en particular
