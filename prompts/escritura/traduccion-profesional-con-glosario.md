# Traducción profesional con glosario

> Traducción profesional con glosario: prompt que traduce respetando terminología, tono y formato, y señala las dudas para revisarlas.

## Cuándo usarlo

Este prompt es ideal cuando necesitas traducir documentos técnicos o corporativos donde la consistencia terminológica es innegociable. Funciona de maravilla con manuales, contratos o artículos especializados. Sin embargo, no lo uses para textos literarios, poesía o publicidad creativa donde la transcreación y el juego de palabras importan más que la fidelidad estricta. Tampoco sirve si no dispones de un glosario base, ya que sin esa guía, la IA podría tomar decisiones léxicas que no se ajustan a las necesidades específicas de tu empresa.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un traductor profesional especializado en el sector del texto.

## Contexto
Necesito traducir un documento con términos específicos que deben mantenerse.

## Objetivo
Obtener una traducción fiel, natural y coherente con el glosario.

## Datos (rellena lo que va entre corchetes)
- [texto]
- [idioma de origen y de destino, con variante: inglés británico, portugués europeo…]
- [glosario de términos]
- [público y registro]

## Instrucciones paso a paso
1. Lee el texto completo antes de traducir.
2. Traduce respetando el glosario y el formato.
3. Adapta las expresiones idiomáticas al destino.
4. Lista las dudas y las decisiones de traducción.

## Formato de salida
Traducción con el mismo formato y tabla de dudas (original, opción elegida, alternativa).

## Criterios de calidad
- Los términos del glosario se usan siempre igual.
- Cifras, fechas y unidades siguen la convención del destino.
- No omite frases.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Manual técnico al inglés británico con un glosario de 20 términos. Resultado: traducción y cuatro dudas sobre unidades.
- **Consejo:** Claude: admite documentos largos; pega el texto completo en lugar de fragmentos sueltos.
- **Consejo:** Claude: separa tus datos con etiquetas como <documento>…</documento>; Anthropic lo recomienda para que distinga instrucciones y contenido.
- **Evita:** Usar traducciones de documentos oficiales sin revisión profesional.
- **Evita:** No indicar la variante del idioma.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Traducción profesional con glosario en Cognenza](https://cognenza.com/prompts/traduccion-profesional-con-glosario/)
