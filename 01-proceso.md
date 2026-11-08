# 01 · Proceso: pasos con su tipo de tarea

> Cada paso dice **qué le pedí al asistente** y **qué tipo de tarea es** (resumir, extraer,
> clasificar o redactar), con la razón de por qué ese tipo y no otro.

---

## Paso 1 · Buscar el orden y separar correos con más de un asunto → **RESUMIR**

**Le pedí al asistente:** que resumiera cada uno de los 10 correos en una línea con el asunto
central del cliente, señalando si hay más de un pedido tratado en el mismo correo.

**Por qué resumir:** antes de clasificar necesito entender el mensaje en corto: en la bandeja
apareció un correo que mezcla dos temas (el correo 9: agradecimiento + factura + faltante).
Resumir no inventa datos y me deja detectar correos multi-asunto sin leer 10 mensajes largos.

## Paso 2 · Sacar los datos que se usan para responder → **EXTRAER**

**Le pedí al asistente:** que extrajera, correo por correo, los datos concretos que mis
respuestas necesitan: nombre del cliente, pedido/folio, artículo, fecha de compra, fecha de
recepción, montos, si adjuntó fotos, datos fiscales y lo que **no debería** haber compartido.

**Por qué extraer (y no resumir):** aquí no quiero el sentido del correo, quiero **campos
exactos que ya existen en el mensaje** (folio 48213, $1,890, RFC, etc.). Extraer es sacar
datos; resumir es compactar texto. Los datos extraídos son los que después van entre
corchetes en las respuestas base.

## Paso 3 · Ordenar los correos por tipo → **CLASIFICAR**

**Le pedí al asistente:** que clasificara los 10 correos en MIS categorías (las definí yo:
6 categorías, de "estatus de pedido" a "dudas antes de comprar") con urgencia y una frase de
razón, y que marcara los correos que podían caer en más de una.

**Por qué clasificar:** el objetivo de Leo es un *orden de atención*: no se contesta en orden
de llegada, se contesta por urgencia y por tipo, porque ese orden es lo que le ahorra tiempo.
Clasificar (asignar una etiqueta con criterio) es la tarea correcta; redactar aquí sería
adelantarse.

## Paso 4 · Escribir la respuesta por tipo → **REDACTAR**

**Le pedí al asistente:** que redactara una respuesta base por cada categoría, en el tono de
la marca (cercano y sencillo), **citando solo reglas de mis políticas** y dejando entre
corchetes `[ ]` todo dato que depende del sistema (estatus de pedido, fecha de entrega, si el
pedido sigue en almacén...).

**Por qué redactar al final y con corchetes:** redactar es generar texto nuevo y es lo único
que la IA debe hacer sola; los datos que no están en el correo ni en la política **no** los
puede saber el asistente, y para eso sirven los corchetes: Leo los llena antes de enviar.

## Paso 5 · Checar contra las políticas → **CLASIFICAR de nuevo + RESUMIR (revisión)**

**Le pedí al asistente:** que volviera a revisar cada respuesta base marcando, con sí/no,
si cumpía cada política aplicable (24 horas hábiles, plazos de factura, no pedir datos
sensibles, no prometer fechas) y que devolviera un resumen de qué corregir.

**Por qué una revisión en dos tipos:** la comparación contra reglas es de nuevo clasificación
(cumple / no cumple / fuera de plazo) y el resultado de la revisión me lo devolvió compacto
para poder corregir rápido. La lista de errores quedó en [05-revisión](./05-revision.md).
