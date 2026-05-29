# Reporte-Horas

Aplicación HTML para visualizar y procesar horas desde Google Sheets.

## Vistas disponibles

- `ach-timesheet.html`: dashboard operativo con detalle por registro, área y proyecto.
- `ach-admin-timesheet.html`: vista administrativa con resumen por usuario de facturación, horas totales y horas procesadas.

## Configuración de precios

La hoja de configuración de precios debe incluir estas columnas:

- `Type`: admite `User`, `Project` y `Task`.
- `Reference`: el nombre exacto del usuario, proyecto o tarea a la que aplica la tasa.
- `Price Prop`: el multiplicador numérico que se aplicará en el cálculo de horas procesadas.

Ejemplo:

```text
Type	Reference	Price Prop
Task	Entrevista - Asistente	0.35
```