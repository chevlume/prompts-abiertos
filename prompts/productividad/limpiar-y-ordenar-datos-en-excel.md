# Limpiar y ordenar datos en Excel

> Limpiar y ordenar datos en Excel: prompt con pasos para quitar duplicados, unificar formatos y dejar una tabla lista para analizar.

## Cuándo usarlo

Este prompt es ideal cuando te enfrentas a una base de datos caótica o exportaciones de sistemas antiguos que mezclan formatos y contienen errores de entrada manual. Te permite establecer un flujo de trabajo profesional que ayuda a obtener mejores resultados en tus informes finales. Sin embargo, no es adecuado para tareas de análisis estadístico profundo o cuando necesitas automatización compleja mediante macros avanzadas, ya que se centra en la higiene del dato y la reproducibilidad del proceso manual o mediante Power Query.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un especialista en calidad de datos.

## Contexto
Tengo una tabla desordenada, con duplicados, fechas en varios formatos y textos mal escritos.

## Objetivo
Diseñar un plan de limpieza reproducible y las fórmulas o pasos para aplicarlo.

## Datos (rellena lo que va entre corchetes)
- [muestra de 10 filas anonimizadas]
- [programa: Excel, Sheets o Power Query]
- [para qué se usarán los datos]

## Instrucciones paso a paso
1. Haz un diagnóstico: duplicados, formatos mezclados, vacíos y valores raros.
2. Propón el orden de limpieza.
3. Da la fórmula, función o paso de Power Query para cada problema.
4. Indica cómo comprobar que la limpieza no ha borrado datos válidos.

## Formato de salida
Tabla de diagnóstico (problema, ejemplo, solución), lista de pasos numerados y lista de comprobación final.

## Criterios de calidad
- No se elimina información sin avisar.
- Los pasos se pueden repetir el mes que viene.
- Se conserva una copia de los datos originales.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Lista de clientes con nombres en mayúsculas y minúsculas y teléfonos con y sin prefijo. Resultado: NOMPROPIO, ESPACIOS, quitar duplicados y validación.
- **Consejo:** ChatGPT: puedes adjuntar el archivo (Excel, CSV o PDF) y pedirle que lo analice; pide que te muestre los cálculos que ha hecho.
- **Consejo:** Gemini: si tu plan lo incluye, puedes usarlo dentro de Google Docs o Sheets sin salir del documento.
- **Evita:** Pegar datos personales reales: usa una muestra inventada.
- **Evita:** Trabajar sobre el archivo original sin copia.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Limpiar y ordenar datos en Excel en Cognenza](https://cognenza.com/prompts/limpiar-y-ordenar-datos-en-excel/)
- Guía relacionada: <https://cognenza.com/tareas/excel-copilot/>
