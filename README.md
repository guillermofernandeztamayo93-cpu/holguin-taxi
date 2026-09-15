# Holguín Taxi — Release Candidate 1.2 / V15

Flutter + Supabase para pasajeros, conductores y administración.

## V15
- Creación de viajes autoritativa en servidor.
- Tarifas, comisión y servicio no pueden ser modificados por el cliente.
- Configuración bancaria solo mediante RPC administrativo.
- Escritura directa de `trips` y `driver_documents` revocada para clientes.
- Corrección de carga de categorías en registro de conductores.
- Se mantiene pago por transferencia directa y la regla: **pago confirmado → despacho**.

## Importante
No almacenar PIN, CVV, OTP ni contraseñas bancarias. La transferencia directa se confirma manualmente por el administrador hasta disponer de una integración bancaria autorizada.

El código no ha sido compilado en este entorno porque no hay Flutter/Android SDK disponible. Ver `docs/PRODUCCION_V15.md` para la batería de pruebas.
