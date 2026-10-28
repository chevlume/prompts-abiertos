# Revisar código como un sénior

> Revisar código como un sénior: prompt de revisión que busca errores, problemas de seguridad y mejoras de legibilidad, ordenados por gravedad.

## Cuándo usarlo

Este prompt es ideal cuando trabajas en solitario o en equipos pequeños y necesitas una segunda opinión técnica antes de hacer un merge a producción. Es muy útil para detectar fallos de seguridad críticos o errores de lógica sutiles. Sin embargo, no sustituye a los tests automatizados ni a un proceso de QA riguroso. Evita usarlo para refactorizaciones arquitectónicas masivas; ahí es mejor discutir el diseño con compañeros antes de escribir el código, ya que la IA puede perderse en contextos muy amplios.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un ingeniero de software sénior que hace revisiones de código exigentes y amables.

## Contexto
Quiero una revisión de mi código antes de integrarlo.

## Objetivo
Detectar errores, riesgos de seguridad, problemas de rendimiento y de legibilidad, con propuestas concretas.

## Datos (rellena lo que va entre corchetes)
- [código o diff, sin contraseñas ni credenciales]
- [lenguaje y versión]
- [qué debe hacer el código]
- [convenciones del proyecto]

## Instrucciones paso a paso
1. Resume qué hace el código para confirmar que lo has entendido.
2. Busca errores lógicos y casos límite.
3. Revisa seguridad: entradas, inyecciones, credenciales expuestas y permisos.
4. Propón mejoras de legibilidad y rendimiento con el código corregido.

## Formato de salida
Lista de hallazgos con gravedad (crítico, importante, menor), línea, explicación y propuesta; al final, el fragmento corregido.

## Criterios de calidad
- No inventa APIs ni funciones inexistentes.
- Cada hallazgo tiene una razón concreta.
- Distingue errores de preferencias de estilo.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Función de login en Node. Resultado: aviso crítico por comparar contraseñas sin hash y propuesta con bcrypt.
- **Consejo:** Claude: pide el resultado como artefacto para verlo y editarlo aparte del chat.
- **Consejo:** ChatGPT: abre el resultado en Canvas para editar párrafos concretos sin regenerar todo el texto.
- **Evita:** Pegar claves de API o datos de clientes en el código.
- **Evita:** Aceptar los cambios sin ejecutar los tests.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Revisar código como un sénior en Cognenza](https://cognenza.com/prompts/revisar-codigo-como-un-senior/)
- Guía relacionada: <https://cognenza.com/oficios/programadores-principiantes/>
