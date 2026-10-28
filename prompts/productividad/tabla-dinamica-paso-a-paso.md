# Tabla dinámica paso a paso

> Tabla dinámica paso a paso: prompt para diseñar el resumen que necesitas, con filas, columnas, valores y filtros explicados para tu versión.

## Cuándo usarlo

Este prompt es ideal cuando tienes un informe caótico y necesitas extraer conclusiones claras sin perderte entre menús de Excel. Resulta muy útil si te bloqueas al decidir qué dato va en cada cuadrante de la tabla dinámica para obtener una respuesta de negocio coherente. Sin embargo, no te servirá de mucho si tus datos de origen están desorganizados, tienen errores de formato o celdas en blanco, ya que la IA no puede arreglar la estructura de tu archivo por ti antes de procesarlo.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un formador de Excel paciente y práctico.

## Contexto
Quiero resumir una tabla grande y no sé cómo montar la tabla dinámica.

## Objetivo
Obtener instrucciones exactas para crear la tabla dinámica que responde a mi pregunta.

## Datos (rellena lo que va entre corchetes)
- [columnas de la tabla]
- [pregunta que quiero responder]
- [programa y versión]

## Instrucciones paso a paso
1. Traduce mi pregunta a filas, columnas, valores y filtros.
2. Da los pasos de clic en mi versión.
3. Indica qué cálculo usar en valores (suma, recuento, promedio).
4. Propón un gráfico dinámico si ayuda.

## Formato de salida
Esquema de la tabla, pasos numerados y un ejemplo de cómo quedará el resultado.

## Criterios de calidad
- Los nombres de menú corresponden a mi versión.
- Explica cómo actualizar la tabla con datos nuevos.
- Avisa si los datos necesitan limpieza previa.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Ventas por fecha, comercial y producto; pregunta: ventas por trimestre y producto. Resultado: fechas agrupadas por trimestre en filas y productos en columnas.
- **Consejo:** Gemini: si tu plan lo incluye, puedes usarlo dentro de Google Docs o Sheets sin salir del documento.
- **Evita:** Tener celdas combinadas o filas vacías en los datos de origen.
- **Evita:** No convertir el rango en tabla antes de empezar.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Tabla dinámica paso a paso en Cognenza](https://cognenza.com/prompts/tabla-dinamica-paso-a-paso/)
- Guía relacionada: <https://cognenza.com/tareas/excel-copilot/>
