# Proyecto · Clase 4 · Leo ordena su bandeja de correos y prepara respuestas base

**LIA Lab · DEV.F · Módulo 4 (IA generativa para distintos problemas)**
**Rol: Leo (Atención a clientes de Tienda Pino Real) · Tiempo estimado: ~30 min**

Caso: Leo recibe decenas de correos cada mañana en la bandeja de atención a clientes y quiere
un orden para atenderlos y respuestas base por tipo que pueda ajustar antes de enviar.
Fecha del caso: hoy es **lunes 19 de octubre**.

## Estructura del proyecto

| Archivo | Contenido |
|---|---|
| [01-proceso.md](./01-proceso.md) | Los pasos con su tipo de tarea (resumir, extraer, clasificar o redactar) |
| [02-clasificacion.md](./02-clasificacion.md) | Tabla con los 10 correos: categoría, urgencia y razón de una frase |
| [03-respuestas-base.md](./03-respuestas-base.md) | Una respuesta base por categoría, con los corchetes de datos variables |
| [04-no-resuelve-base.md](./04-no-resuelve-base.md) | Correos que pasan a una persona y por qué |
| [05-revision.md](./05-revision.md) | Qué se comparó contra las políticas y qué se corrigió |

## Cómo saber si quedó bien (checklist del brief)

- [x] El proceso **nombra el tipo de tarea de cada paso** y es el correcto: sacar datos del correo es **extraer**, ordenarlos es **clasificar**, contestar es **redactar**.
- [x] Se definieron **categorías propias (6)**, cada correo quedó en una con una razón de una frase, y se **señalaron los correos que podían caer en más de una** (correo 9).
- [x] Las respuestas base usan **solo reglas de las políticas** y dejan entre corchetes lo que el asistente no puede saber (estatus de un pedido, fecha de entrega).
- [x] Se dijo **qué correos no se resuelven con respuesta base** y por qué los atendería una persona.
- [x] La revisión nombra **al menos un error concreto** encontrado y cómo se corrigió.

## Fuente de reglas

Políticas de Tienda Pino Real (anexadas al brief): horario 9:00 a 18:00, respuesta en máximo
24 horas hábiles; entregas 3–5 días hábiles en ciudades principales y 5–8 en el resto;
devoluciones hasta 15 días con producto sin uso y en su empaque; dañado o incompleto se avisa
en 3 días naturales con fotos y se repone sin costo; reembolsos de 5–7 días hábiles tras
llegar al almacén; cancelaciones solo si el pedido no salió de almacén; facturas solo durante
el mes de la compra; cobros duplicados se revisan en 2 días hábiles y el banco devuelve en
3–5; quejas formales o mención de autoridades van con la supervisora Marcela Reyes el mismo
día y **no** se contestan con respuesta base; nunca se piden por correo números completos de
tarjeta, contraseñas ni códigos de seguridad.
