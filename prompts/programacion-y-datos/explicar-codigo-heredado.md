# Explicar código heredado

> Explicar código heredado: prompt para entender un programa antiguo, con resumen, flujo, dependencias y riesgos antes de tocarlo.

## Cuándo usarlo

Este prompt es fundamental cuando te enfrentas al famoso código 'spaghetti' sin documentación, donde cualquier cambio parece un salto al vacío. Es perfecto para obtener una visión clara antes de empezar a tocar nada. Sin embargo, no lo uses si el código es excesivamente largo (miles de líneas), ya que la IA podría perderse en los detalles. Tampoco es útil si buscas una reescritura total inmediata; su objetivo es la comprensión profunda del estado actual para minimizar el riesgo de roturas.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un arquitecto de software que documenta sistemas antiguos.

## Contexto
Tengo que modificar código que no escribí y no tiene documentación.

## Objetivo
Entender qué hace, cómo fluye y qué puede romperse al cambiarlo.

## Datos (rellena lo que va entre corchetes)
- [código]
- [lenguaje]
- [cambio que quiero hacer]

## Instrucciones paso a paso
1. Resume el propósito del código en tres frases.
2. Describe el flujo principal paso a paso.
3. Lista dependencias, efectos secundarios y variables globales.
4. Señala los riesgos del cambio que quiero hacer.

## Formato de salida
Resumen, flujo numerado, tabla de dependencias y lista de riesgos con tests previos sugeridos.

## Criterios de calidad
- Separa lo seguro de lo que es una suposición.
- Usa los nombres reales del código.
- No reescribe el código si no se le pide.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Script de facturación en PHP. Resultado: flujo de cinco pasos y aviso de una variable global que también usa otro módulo.
- **Consejo:** Claude: admite documentos largos; pega el texto completo en lugar de fragmentos sueltos.
- **Consejo:** Claude: separa tus datos con etiquetas como <documento>…</documento>; Anthropic lo recomienda para que distinga instrucciones y contenido.
- **Evita:** Refactorizar todo antes de entenderlo.
- **Evita:** Pegar código con credenciales.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Explicar código heredado en Cognenza](https://cognenza.com/prompts/explicar-codigo-heredado/)
