# Depurar un error a partir del mensaje

> Depurar un error a partir del mensaje: prompt que analiza el error, plantea hipótesis ordenadas y propone pruebas para encontrar la causa.

## Cuándo usarlo

Este prompt es extremadamente útil cuando te bloqueas ante un error críptico y necesitas un enfoque estructurado, especialmente si el fallo parece intermitente o depende de factores externos. Funciona de maravilla para errores de sintaxis o lógica compleja donde el stack trace no es obvio. Sin embargo, no es la mejor herramienta si el problema es un error de arquitectura global o una configuración de infraestructura mal definida, donde el mensaje de error es solo un síntoma de un problema mucho más profundo.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un desarrollador experto en depuración metódica.

## Contexto
Mi programa falla y tengo el mensaje de error, pero no sé por qué.

## Objetivo
Encontrar la causa más probable y una solución verificada.

## Datos (rellena lo que va entre corchetes)
- [mensaje de error completo]
- [fragmento de código relacionado]
- [entorno: lenguaje, versiones, sistema]
- [qué cambió antes de que fallara]

## Instrucciones paso a paso
1. Explica en lenguaje claro qué dice el error.
2. Plantea entre tres y cinco hipótesis ordenadas por probabilidad.
3. Para cada una, propón una prueba rápida para confirmarla o descartarla.
4. Da la solución para la hipótesis más probable.

## Formato de salida
Explicación, tabla de hipótesis (causa, prueba, resultado esperado) y solución en un bloque de código.

## Criterios de calidad
- No da por segura una causa sin pruebas.
- Las pruebas son rápidas de ejecutar.
- La solución no oculta el error con un try/catch vacío.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** «TypeError: Cannot read properties of undefined». Resultado: hipótesis de dato asíncrono no cargado y comprobación con un console.log.
- **Consejo:** Claude: separa tus datos con etiquetas como <documento>…</documento>; Anthropic lo recomienda para que distinga instrucciones y contenido.
- **Consejo:** ChatGPT: abre el resultado en Canvas para editar párrafos concretos sin regenerar todo el texto.
- **Evita:** Pegar solo la última línea del error.
- **Evita:** Aplicar soluciones sin entenderlas.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Depurar un error a partir del mensaje en Cognenza](https://cognenza.com/prompts/depurar-un-error-a-partir-del-mensaje/)
- Guía relacionada: <https://cognenza.com/oficios/programadores-principiantes/>
