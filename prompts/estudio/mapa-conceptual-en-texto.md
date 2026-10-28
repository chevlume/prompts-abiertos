# Mapa conceptual en texto

> Mapa conceptual en texto: prompt que organiza un tema en conceptos y relaciones, listo para dibujar o pegar en una herramienta de diagramas.

## Cuándo usarlo

Este prompt es ideal cuando necesitas sintetizar información densa, como apuntes de estudio o informes complejos, para visualizar jerarquías rápidamente. Es una herramienta potente para identificar lagunas en tu comprensión o preparar presentaciones esquemáticas. Sin embargo, no es adecuado si el tema carece de estructura lógica, como en narrativas puramente creativas o poemas abstractos, donde las relaciones causales no son el foco principal. Úsalo para organizar datos, no para generar contenido literario o subjetivo donde la linealidad no importa.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un experto en aprendizaje visual.

## Contexto
Quiero ver un tema de un vistazo y entender cómo se relacionan sus ideas.

## Objetivo
Crear un mapa conceptual jerárquico con relaciones etiquetadas.

## Datos (rellena lo que va entre corchetes)
- [tema o texto]
- [nivel de detalle: básico o completo]
- [formato: lista sangrada o Mermaid]

## Instrucciones paso a paso
1. Identifica el concepto central.
2. Lista conceptos de segundo y tercer nivel.
3. Une los conceptos con palabras de enlace.
4. Revisa que no haya conceptos aislados.

## Formato de salida
Mapa en lista sangrada y, si se pide, en código Mermaid.

## Criterios de calidad
- Cada relación tiene una palabra de enlace.
- No supera tres niveles en la versión básica.
- Los conceptos son sustantivos breves.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** La fotosíntesis. Resultado: concepto central con fases, elementos y productos, y código Mermaid para dibujarlo.
- **Consejo:** Claude: pide el resultado como artefacto para verlo y editarlo aparte del chat.
- **Evita:** Meter frases largas en los nodos.
- **Evita:** Copiar el mapa sin comprobar las relaciones.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Mapa conceptual en texto en Cognenza](https://cognenza.com/prompts/mapa-conceptual-en-texto/)
