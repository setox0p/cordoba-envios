# Diccionario de datos inicial

Entidades del módulo de gestión y seguimiento de encomiendas de Córdoba Envíos (Entrega 3).

## ENCOMIENDA

| Campo | Tipo | Descripción |
|---|---|---|
| id_encomienda | Integer | Código único generado automáticamente para la identificación y seguimiento del paquete. |
| descripcion | String | Detalle breve del paquete o características específicas de la carga. |
| fecha_recepcion | Date | Fecha en la que el cliente entrega la encomienda en la sucursal. |
| estado_envio | String | Estado actual dentro del flujo: «recibido», «en distribución» o «entregado». |

## CLIENTE

| Campo | Tipo | Descripción |
|---|---|---|
| id_cliente | Integer | Identificador interno y único del cliente en el sistema. |
| documento_fiscal | String | Número de documento legal o identificación fiscal del cliente (DNI o CUIT). |
| direccion_origen | String | Dirección postal donde se retira o se recibe inicialmente el paquete. |
| direccion_destino | String | Dirección postal de destino para la entrega final. |

## REGISTRO_OPERACION

| Campo | Tipo | Descripción |
|---|---|---|
| id_operacion | Integer | Clave primaria que identifica la transacción administrativa. |
| id_encomienda | Integer | Clave foránea que vincula la operación con la encomienda. |
| monto_servicio | Float | Valor total cobrado por el servicio de transporte y distribución. |
| id_empleado_registro | Integer | Legajo del empleado operativo que procesó la recepción o la entrega. |
