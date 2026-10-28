# Informe mensual de resultados

> Informe mensual de resultados: prompt para pasar de datos sueltos a un informe claro con cifras clave, causas, riesgos y próximos pasos.

## Cuándo usarlo

Este prompt es ideal cuando tienes un montón de datos crudos y poco tiempo para estructurarlos de forma lógica para tus superiores. Te ayuda a pasar del qué ha pasado al por qué y qué haremos ahora de manera coherente. No obstante, no te servirá si los datos son extremadamente confidenciales y no puedes subirlos por política de empresa, o si buscas un análisis financiero profundo que requiera acceso a sistemas contables externos que la IA no puede consultar directamente.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un analista de negocio que escribe informes para dirección.

## Contexto
Tengo las cifras del mes y comentarios del equipo, y debo presentar un informe que se entienda sin explicaciones adicionales.

## Objetivo
Elaborar un informe mensual con resumen ejecutivo, indicadores, explicación de las variaciones y acciones propuestas.

## Datos (rellena lo que va entre corchetes)
- [cifras del mes y del mes anterior]
- [objetivos del periodo]
- [comentarios o incidencias del equipo]
- [público del informe]

## Instrucciones paso a paso
1. Calcula las variaciones respecto al mes anterior y al objetivo.
2. Identifica las tres variaciones más relevantes y sus posibles causas, marcando lo que es hipótesis.
3. Detecta riesgos para el próximo mes.
4. Propón entre tres y cinco acciones concretas.

## Formato de salida
Resumen ejecutivo de 5 líneas, tabla de indicadores (valor, mes anterior, objetivo, variación), apartado de causas, riesgos y acciones.

## Criterios de calidad
- Todas las cifras proceden de los datos aportados.
- Las hipótesis se marcan como tales.
- Cada acción tiene responsable sugerido.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Ventas, visitas y devoluciones de una tienda online. Resultado: tabla con variaciones, explicación de la caída de conversión como hipótesis y tres acciones.
- **Consejo:** ChatGPT: puedes adjuntar el archivo (Excel, CSV o PDF) y pedirle que lo analice; pide que te muestre los cálculos que ha hecho.
- **Consejo:** Gemini: si tu plan lo incluye, puedes usarlo dentro de Google Docs o Sheets sin salir del documento.
- **Evita:** Pedir causas sin dar contexto: la IA las inventa.
- **Evita:** No comprobar los cálculos de porcentajes.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Informe mensual de resultados en Cognenza](https://cognenza.com/prompts/informe-mensual-de-resultados/)
