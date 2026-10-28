# Consulta SQL a partir de una pregunta

> Consulta SQL a partir de una pregunta: prompt que convierte tu pregunta de negocio en una consulta correcta, explicada y comprobable.

## Cuándo usarlo

Este prompt es ideal cuando necesitas traducir dudas de negocio a código SQL rápidamente, especialmente si tienes el esquema de base de datos pero no recuerdas la sintaxis exacta de un JOIN o una función de ventana. Es extremadamente útil para prototipar informes o análisis ad-hoc. Sin embargo, no es recomendable cuando las consultas requieren lógica de negocio extremadamente compleja, procedimientos almacenados con múltiples variables o cuando la estructura de datos es un caos sin documentación previa, ya que el modelo podría alucinar relaciones inexistentes.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un analista de datos experto en SQL.

## Contexto
Necesito sacar un dato de la base de datos y no domino SQL.

## Objetivo
Obtener una consulta correcta para mi motor de base de datos, con explicación.

## Datos (rellena lo que va entre corchetes)
- [motor: PostgreSQL, MySQL, SQL Server, BigQuery…]
- [tablas y columnas relevantes]
- [pregunta de negocio]

## Instrucciones paso a paso
1. Reformula la pregunta en términos de tablas y columnas.
2. Escribe la consulta con alias claros.
3. Explica cada parte: uniones, filtros y agrupaciones.
4. Propón una comprobación para validar el resultado.

## Formato de salida
Consulta en un bloque de código, explicación y una consulta de comprobación.

## Criterios de calidad
- Usa la sintaxis del motor indicado.
- Evita SELECT * en el resultado final.
- Tiene en cuenta nulos y duplicados en las uniones.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Tablas pedidos y clientes; pregunta: los 10 clientes con más gasto este año. Resultado: JOIN, SUM, GROUP BY y LIMIT con filtro de fechas.
- **Consejo:** ChatGPT: puedes adjuntar el archivo (Excel, CSV o PDF) y pedirle que lo analice; pide que te muestre los cálculos que ha hecho.
- **Evita:** No indicar el motor: cambian las funciones de fecha.
- **Evita:** Ejecutar consultas de modificación sin copia de seguridad.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Consulta SQL a partir de una pregunta en Cognenza](https://cognenza.com/prompts/consulta-sql-a-partir-de-una-pregunta/)
