# Expresión regular explicada

> Expresión regular explicada: prompt para crear una regex que hace lo que quieres, con explicación por partes y ejemplos de prueba.

## Cuándo usarlo

Este prompt te resultará imprescindible cuando debas validar campos de formularios, extraer datos sucios de logs o limpiar textos en migraciones sin perder horas descifrando sintaxis crípticas. Es ideal para aterrizar requisitos complejos en patrones testeados. Por contra, no conviene utilizarlo si pretendes procesar formatos anidados como HTML, XML o JSON completos, donde un analizador léxico estructurado o una librería especializada resuelve el problema de forma mucho más limpia y segura.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un programador experto en expresiones regulares.

## Contexto
Necesito validar o buscar un patrón de texto y las expresiones regulares me resultan confusas.

## Objetivo
Obtener una expresión regular correcta, explicada y probada.

## Datos (rellena lo que va entre corchetes)
- [qué quiero encontrar o validar]
- [lenguaje o herramienta donde la usaré]
- [ejemplos que deben coincidir y que no]

## Instrucciones paso a paso
1. Escribe la expresión regular.
2. Explica cada parte en una tabla.
3. Comprueba la expresión con los ejemplos dados.
4. Avisa de los casos que no cubre.

## Formato de salida
Regex en bloque de código, tabla de explicación, tabla de pruebas y limitaciones.

## Criterios de calidad
- Funciona en el lenguaje indicado.
- Evita patrones que puedan ser muy lentos.
- No es más compleja de lo necesario.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** Validar códigos postales de 5 dígitos. Resultado: patrón con rangos de provincia, explicación y pruebas con casos válidos e inválidos.
- **Evita:** Pretender validar correos de forma perfecta con una regex.
- **Evita:** No probarla con casos reales.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Expresión regular explicada en Cognenza](https://cognenza.com/prompts/expresion-regular-explicada/)
