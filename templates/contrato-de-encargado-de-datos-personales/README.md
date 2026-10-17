# Contrato de encargado de datos personales

## ¿Qué es?

Es el contrato que firma una empresa (el **responsable**, quien decide sobre los datos) con un proveedor (el **encargado**, quien trata los datos solo por cuenta del responsable). En México, cuando el responsable entrega datos a un encargado se le llama **remisión**. Este contrato fija las reglas: el encargado solo usa los datos según las instrucciones del responsable, los protege, no los comparte y los devuelve o borra al terminar.

Es el equivalente mexicano de un **«Data Processing Addendum» (DPA)**. En México **no existe HIPAA** (la ley de salud de EE. UU.). Aquí los datos de salud son **datos personales sensibles** y se protegen con la misma LFPDPPP, con reglas más estrictas. Para una relación que solo se rige por la ley mexicana, no necesitas un BAA: necesitas este contrato, con las medidas de seguridad reforzadas para datos sensibles.

> **Ojo:** este contrato cubre **solo la ley mexicana**. Si tu cliente está en Estados Unidos y está sujeto a HIPAA, la ley de ese país le puede exigir un BAA aunque tú estés en México. Este contrato **no sustituye** ese BAA; en ese caso, tu cliente necesitará un documento aparte, revisado por una persona abogada de EE. UU.

## ¿Cuándo usarla?

- Tu empresa SaaS trata datos que sus clientes suben a la plataforma (tú eres el **encargado**; tu cliente es el **responsable**).
- Tu empresa contrata un proveedor de nube, correo, CRM, nómina, soporte, analítica o desarrollo que tendrá acceso a datos personales (tú eres el **responsable**; tu proveedor es el **encargado**).
- Un cliente te pide un DPA: puedes ofrecer este contrato como versión mexicana. (Si te pide un BAA por HIPAA, lee el aviso de arriba.)
- Necesitas autorizar a un **subencargado** (el proveedor de tu proveedor).
- Tratas datos de salud por cuenta de un hospital, consultorio, aseguradora o laboratorio.

## ¿Cuándo NO usarla?

- **El que recibe los datos los usará para sus propios fines** (no solo por tu cuenta). Eso es una **transferencia**, no una remisión. Usa la plantilla `convenio-de-transferencia-de-datos-personales`.
- **El proveedor no tendrá acceso a datos personales** (por ejemplo, solo vende licencias de software que instalas tú). Basta con una cláusula de confidencialidad en el contrato principal.
- **Una de las partes es una dependencia de gobierno:** aplica otra ley de datos personales (sector público).
- **El contrato principal ya incluye todas estas cláusulas** con el mismo nivel de detalle.

## Puntos clave

- **Solo por instrucciones del responsable:** el encargado no puede usar los datos para nada más. Si lo hace, la ley lo trata como responsable y asume todas sus obligaciones.
- **Confidencialidad:** el encargado y su personal guardan secreto, incluso después de terminar el contrato.
- **Medidas de seguridad administrativas, físicas y técnicas:** la LFPDPPP las exige. El Anexo B las detalla.
- **Subencargados con autorización:** el encargado no puede pasar los datos a otro proveedor sin permiso del responsable. El Anexo C lista los ya autorizados.
- **Aviso de vulneraciones de seguridad:** el encargado avisa al responsable en un plazo corto, para que este pueda avisar a las personas afectadas.
- **Apoyo con derechos ARCO:** el encargado ayuda al responsable a responder solicitudes dentro de los plazos de ley.
- **Devolución o supresión al terminar:** el encargado no se queda con los datos.
- **Auditorías:** el responsable puede verificar que el encargado cumple.
- **Transferencias y remisiones internacionales:** reglas cuando los datos se guardan o tratan fuera de México.
- **Datos sensibles y de salud:** cláusula opcional con medidas reforzadas para datos de salud bajo la ley mexicana.

## Fundamento legal

| Ley | Artículos | Para qué sirve | Enlace oficial |
|---|---|---|---|
| Constitución Política de los Estados Unidos Mexicanos (CPEUM) | Art. 16 | Derecho a la protección de datos personales. | [diputados.gob.mx](https://www.diputados.gob.mx/LeyesBiblio/pdf/CPEUM.pdf) |
| Ley Federal de Protección de Datos Personales en Posesión de los Particulares (LFPDPPP, DOF 20-03-2025) | Sin número (ley nueva; revisa el texto vigente) | Figuras de responsable y encargado, remisiones, medidas de seguridad, vulneraciones, datos sensibles, derechos ARCO, autoridad (Secretaría Anticorrupción y Buen Gobierno). | [Texto vigente](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf) |
| Reglamento de la LFPDPPP (2011, expedido bajo la ley anterior) | Sin número | Referencia sobre obligaciones del encargado, subcontratación y medidas de seguridad. Puede cambiar con la nueva ley. | [diputados.gob.mx](https://www.diputados.gob.mx/LeyesBiblio/regley/Reg_LFPDPPP.pdf) |
| Código Civil Federal (CCF) | Arts. 1792–1796, 1803, 1834 bis, 1840, 2104 y siguientes | Formación del contrato, consentimiento y firma por medios electrónicos, pena convencional, daños y perjuicios. | [diputados.gob.mx](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCF.pdf) |
| Código de Comercio | Arts. 89–114; 1415 y siguientes | Mensajes de datos y firma electrónica; arbitraje comercial (opcional). | [diputados.gob.mx](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCom.pdf) |
| Código Penal Federal (CPF) | Arts. 210, 211 y 211 bis 1 a 211 bis 7 | Revelación de secretos y acceso ilícito a sistemas informáticos. | [diputados.gob.mx](https://www.diputados.gob.mx/LeyesBiblio/pdf/CPF.pdf) |

## Antes de firmar, revisa

- [ ] Confirmaste que de verdad es una **remisión** (el proveedor no usa los datos para sus propios fines).
- [ ] Llenaste el **Anexo A** con los tipos de datos, de personas y de tratamiento reales.
- [ ] El **Anexo B** describe medidas de seguridad que el encargado de verdad tiene (pide evidencia: certificaciones, políticas, reportes de auditoría).
- [ ] El **Anexo C** lista todos los subencargados actuales, con país y servicio.
- [ ] El plazo para avisar de vulneraciones es corto y realista (por ejemplo, 24 a 72 horas).
- [ ] Si hay datos sensibles o de salud, activaste la cláusula opcional y las medidas reforzadas.
- [ ] Si hay tratamiento fuera de México, los países están listados.
- [ ] La cláusula de prioridad deja claro qué documento gana si hay contradicción con el contrato principal.
- [ ] Revisaste que el límite de responsabilidad del contrato principal no deje sin efecto las obligaciones de datos.
- [ ] Los representantes que firman tienen poder suficiente.
