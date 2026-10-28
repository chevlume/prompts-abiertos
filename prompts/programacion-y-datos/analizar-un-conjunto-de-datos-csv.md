# Analizar un conjunto de datos CSV

> Analizar un conjunto de datos CSV: prompt para explorar datos, encontrar patrones y obtener conclusiones con cifras, gráficos y límites claros.

## Cuándo usarlo

Este prompt te vendrá genial cuando exportes un CSV de tu CRM, pasarela de cobro o analítica web y necesites aterrizar tendencias antes de una reunión sin pelearte horas con fórmulas complejas. Es perfecto para detectar fugas de ingresos o estacionalidad. En cambio, no es la herramienta adecuada para entrenar modelos predictivos de machine learning, auditar bases de datos relacionales con esquemas cruzados ni validar transacciones financieras críticas que exijan conciliación contable al céntimo.

## El prompt

Copia el bloque, pégalo en tu asistente (ChatGPT, Claude, Gemini…) y rellena lo que va entre corchetes.

```text
## Rol
Actúa como un científico de datos que explica resultados a personas no técnicas.

## Contexto
Tengo un archivo de datos y quiero saber qué dice.

## Objetivo
Hacer un análisis exploratorio con conclusiones prácticas y sus límites.

## Datos (rellena lo que va entre corchetes)
- [descripción de las columnas o el archivo]
- [pregunta principal]
- [decisión que depende del análisis]

## Instrucciones paso a paso
1. Describe la calidad de los datos: filas, vacíos y valores extraños.
2. Calcula estadísticas básicas de las columnas relevantes.
3. Busca patrones, tendencias y segmentos relacionados con la pregunta.
4. Resume las conclusiones y señala qué no se puede concluir.

## Formato de salida
Resumen de calidad, tabla de estadísticas, de tres a cinco hallazgos con su cifra, gráficos sugeridos y limitaciones.

## Criterios de calidad
- No confunde correlación con causalidad.
- Cada hallazgo tiene una cifra que lo respalda.
- Indica el tamaño de la muestra.

## Autorrevisión
Antes de responder, comprueba cada criterio de calidad. Si falta información, pregúntame en lugar de inventarla, y al final indica qué has supuesto.
```

## Consejo y ejemplo

- **Ejemplo:** CSV de ventas de un año. Resultado: estacionalidad en diciembre, dos productos que suman el 60 % y aviso de meses con datos incompletos.
- **Consejo:** ChatGPT: puedes adjuntar el archivo (Excel, CSV o PDF) y pedirle que lo analice; pide que te muestre los cálculos que ha hecho.
- **Consejo:** Gemini: si tu plan lo incluye, puedes usarlo dentro de Google Docs o Sheets sin salir del documento.
- **Evita:** Subir datos personales sin anonimizar.
- **Evita:** Aceptar conclusiones sin pedir cómo se calcularon.

No uses datos personales reales: cambia nombres, correos y cifras sensibles por datos ficticios. Revisa siempre la respuesta antes de usarla.

## Más en Cognenza

- Versión completa, con ejemplo resuelto y variantes: [Analizar un conjunto de datos CSV en Cognenza](https://cognenza.com/prompts/analizar-un-conjunto-de-datos-csv/)
