# Dashboard de control de órdenes de compra y ejecución

Dashboard en Power BI para seguir las órdenes de compra de un hospital
público ficticio: monto emitido, devengado y sin devengar, por servicio,
proveedor y mes.

**Los datos son ficticios**, generados para este proyecto.

## Qué responde
- ¿Qué porcentaje de lo comprado ya se devengó?
- ¿Qué servicios tienen menor ejecución?
- ¿Cómo evoluciona lo devengado mes a mes?
- ¿Qué proveedores concentran más compras?

## Herramientas
Power BI (modelo de datos, medidas DAX, visualizaciones), Excel.

## Medidas DAX principales
- Total Neto OC = monto de OC menos monto anulado
- Total Devengado
- Total Sin Devengar = neto menos devengado
- % Ejecución = devengado / neto

## Hallazgos
- Ejecución global del 75 %: $2.513 M devengados sobre $3.353 M netos.
- Octubre apenas llega al 11 % devengado; septiembre y octubre concentran
  el 48 % de lo pendiente.
- Pediatría ejecuta el 97 %; Diagnóstico por Imágenes, el 55 %.
- Los 5 principales proveedores concentran el 50 % de lo devengado.

## Archivos
- `Control_Hosp_Ficticio.xlsx`: datos
- `Power_BI_Hosp_Ficticio.pbix`: dashboard
- `captura_dashboard.png`: vista del dashboard
- ![Dashboard](captura_dashboard.png)
- 
