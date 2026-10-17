# Revisión de plantillas legales para México

Fecha de corte: **17 de octubre de 2026**. Revisión del commit `1b0396ba87432685e547e10fe7670c1bfd745a6b`.

## Resultado

**No debe afirmarse todavía que todas las plantillas están correctas y actualizadas.** Hay una base útil y varias reformas recientes están incorporadas, pero se identificaron **6 hallazgos de prioridad alta y 8 de prioridad media**. Algunos son errores jurídicos; otros son contradicciones o campos que permiten preparar un documento defectuoso. Cada hallazgo distingue su naturaleza.

Se revisaron las **13 plantillas**, sus **13 README**, `README.md`, `FUENTES.md` y `CONTRIBUIR.md`. Esta revisión documental no verifica las prácticas de una empresa, la operación de una plataforma, poderes, consentimientos reales, registros o obligaciones sectoriales. No constituye un dictamen profesional ni una certificación de cumplimiento. No se modificaron las plantillas.

La investigación de Gemini se leyó como documento de comparación, no como autoridad jurídica. Sus conclusiones se contrastaron con fuentes oficiales. Los enlaces de Orden Jurídico Nacional pueden contener consolidaciones históricas: su leyenda «texto vigente» no garantiza que incorporen la última reforma. Las lecturas de algunos PDF de Diputados fueron intermitentes; las comprobaciones que requieren cierre adicional se indican al final.

## Prioridades

- **Alta:** corregir antes de recomendar la opción afectada para firma o publicación.
- **Media:** corregir antes de presentar la biblioteca como validada; el efecto depende del uso concreto.
- **Ampliación:** documento o control útil que falta, sin que su ausencia invalide por sí misma las demás plantillas.

## Hallazgos de prioridad alta

### H01. El consentimiento tácito tiene un alcance excesivo en el aviso integral

**Ubicación:** [aviso integral](templates/aviso-de-privacidad-integral/plantilla.md), líneas 81, 190–193 y 310–317; [aviso simplificado](templates/aviso-de-privacidad-simplificado/plantilla.md), líneas 49–51; [transferencias](templates/convenio-de-transferencia-de-datos-personales/plantilla.md), línea 115.

**Problema:** la opción A del aviso integral permite consentimiento tácito para todo dato «que no sea sensible». Eso incluye datos financieros o patrimoniales. Además, las casillas de negativa a transferencias se ofrecen sin distinguir suficientemente el caso de consumidores que compran por medios electrónicos. La opción para datos sensibles menciona una casilla sin exigir ahí un mecanismo de autenticación.

**Regla:** los artículos 7–9 de la LFPDPPP distinguen datos comunes, financieros/patrimoniales, sensibles y excepciones. El artículo 76 Bis, fracción I, de la LFPC exige autorización expresa para comunicar información del consumidor a proveedores ajenos a la transacción, salvo requerimiento competente. Véanse la [LFPDPPP](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf) y la [LFPC, artículo 76 Bis](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo120869.html).

**Corrección:** separar las rutas de consentimiento por dato, finalidad y transferencia; documentar las excepciones. Para datos sensibles, vincular la manifestación escrita a firma o autenticación verificable. No describir cualquier casilla anónima como suficiente. Para transferencias comerciales de consumidores, no ofrecer la mera falta de negativa como autorización expresa.

### H02. Las suscripciones no deben depender de la aceptación por mero uso

**Ubicación:** [términos de uso](templates/terminos-y-condiciones-de-uso/plantilla.md), líneas 43–44, cláusulas OCTAVA y NOVENA, y línea 201.

**Problema:** se califica como consentimiento expreso el uso del servicio. La renovación se informa, pero no se exige de forma inequívoca una acción afirmativa que autorice los cobros recurrentes. La cancelación se describe como efectiva al final del periodo, sin distinguirla claramente de la continuación del acceso ya pagado.

**Regla:** el artículo 76 Bis VIII exige consentimiento expreso e informado para cobros recurrentes; IX exige un mecanismo de cancelación inmediata, sujeto al marco contractual. El aviso de cinco días no sustituye al consentimiento. Fuente: [decreto DOF del 12 de diciembre de 2025](https://sidof.segob.gob.mx/notas/docFuente/5775999). La distinción entre consentimiento expreso y tácito está en el [CCF, artículo 1803](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCF.pdf).

**Corrección:** exigir una aceptación afirmativa, informada y registrable del cobro recurrente, indicando monto, periodicidad y fecha. Puede integrarse en un flujo claro de contratación; la ley no exige necesariamente una casilla independiente. Hacer inmediata la cancelación de la suscripción y de su renovación; explicar por separado si se conserva acceso hasta el vencimiento de lo pagado y qué devoluciones proceden. No afirmar que cancelar obliga siempre a un reembolso proporcional.

### H03. El contrato laboral amplía indebidamente la regla sobre invenciones

**Ubicación:** [contrato individual](templates/contrato-individual-de-trabajo/plantilla.md), línea 241, cláusula VIGÉSIMA PRIMERA.

**Problema:** atribuye a la empresa una invención si se hace «como parte de su trabajo», como supuesto alternativo a investigar o mejorar procesos. Esa fórmula puede abarcar supuestos que la regla legal reserva a la persona inventora.

**Regla y corrección:** reproducir con precisión la distinción del artículo 163 II y III de la [LFT](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFT.pdf): investigación o perfeccionamiento por cuenta de la empresa frente a los demás casos. Conservar la compensación complementaria y el derecho preferente donde correspondan. No confundir esta regla con la del software laboral de la LFDA.

### H04. La cesión de entregables distintos del software no fija un plazo determinado

**Ubicación:** [contrato marco](templates/contrato-marco-de-prestacion-de-servicios/plantilla.md), línea 127, cláusula DÉCIMA SEGUNDA, opción A.

**Problema:** «por el plazo máximo que permita la ley» no determina cuántos años se ceden textos, diseños u otras obras. No existe un máximo ordinario único que esa frase resuelva: hay una duración supletoria y una posibilidad excepcional de plazos mayores. La mezcla de obra por encargo y cesión subsidiaria añade incertidumbre sobre el título de adquisición.

**Regla:** artículos 30, 33, 83 y 103 de la [LFDA](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFDA.pdf); [transcripción oficial de los artículos](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo17068.html). La cesión sin plazo se considera por cinco años; superar quince requiere justificación excepcional. El artículo 103 contiene una excepción para programas de cómputo.

**Corrección:** definir el fundamento de adquisición y fijar expresamente los años de la cesión subsidiaria para cada clase de obra, con justificación si procede. Mantener separada la regla del software. Es un riesgo de titularidad y duración, no una conclusión de nulidad de todo el contrato.

### H05. La asesoría permite trabajar a cambio de una intención de entregar capital

**Ubicación:** [contrato de asesoría](templates/contrato-de-asesoria/plantilla.md), líneas 68–76, 103–104 y Anexo A, líneas 172–174.

**Problema:** se puede elegir únicamente participación en capital y dejar el plan «pendiente», mientras el texto aclara que no otorga acciones ni opciones. La cesión de derechos se declara onerosa por remisión a esa contraprestación. La persona podría prestar servicios y ceder entregables sin una obligación de remuneración suficientemente definida y exigible.

**Regla y corrección:** los artículos 30–31 de la [LFDA](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo17068.html) protegen la remuneración por la transmisión. Exigir que el otorgamiento corporativo esté aprobado e instrumentado, o establecer honorarios exigibles como alternativa si no se concreta. Coordinar el inicio de servicios y la adquisición de derechos con esos documentos. No hace falta convertir toda asesoría en una relación laboral; la subordinación se analiza por separado.

### H06. El encargado puede interpretar que basta una confirmación para ejecutar una instrucción ilícita

**Ubicación:** [contrato de encargado](templates/contrato-de-encargado-de-datos-personales/plantilla.md), líneas 77–83.

**Problema:** permite suspender una instrucción posiblemente ilegal hasta que el responsable «la confirme o la cambie». También permite fines propios mediante autorización escrita, sin exigir ahí la revisión del cambio de rol, finalidades y base jurídica.

**Regla y corrección:** una orden privada no subsana la ilicitud. Exigir suspensión hasta que se resuelva la objeción y prohibir ejecutar instrucciones contrarias a la ley. Si el proveedor decide fines propios, analizarlo como responsable y documentar la base correspondiente; una autorización entre empresas no sustituye derechos de titulares. Fuentes: [LFPDPPP, artículos 5–9 y 35–36](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf), y [Reglamento, artículos 49–53](https://www.diputados.gob.mx/LeyesBiblio/regley/Reg_LFPDPPP.pdf). El alcance actual del Reglamento requiere el cierre de vigencia indicado al final.

## Hallazgos de prioridad media

### H07. Los plazos ARCO legales aparecen como ejemplos editables

**Ubicación:** [aviso integral](templates/aviso-de-privacidad-integral/plantilla.md), líneas 249–259 y nota 4, línea 330.

**Problema:** presenta 20 y 15 días como ejemplos de la ley anterior y deja una ampliación sin límite determinado.

**Corrección:** fijar 20 días hábiles para comunicar la determinación y 15 para hacerla efectiva, con una ampliación justificada por una sola vez y por un periodo igual en cada caso. Son reglas de la ley vigente, no simples ejemplos. Fuente: [LFPDPPP, artículos 2 VIII y 31](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf). Si se reproduce el procedimiento reglamentario para subsanar solicitudes, fijar también sus límites y condiciones tras cerrar su vigencia.

### H08. Faltan límites concretos en los campos de descanso y horas extra

**Ubicación:** [contrato individual](templates/contrato-individual-de-trabajo/plantilla.md), líneas 98 y 119–134; su [README](templates/contrato-individual-de-trabajo/README.md), apartado «Horas extra».

**Problema:** el descanso admite cualquier número de minutos; el detalle de horas extra solo fija límites semanales. El README anuncia doce horas sin explicar allí la transición.

**Corrección:** indicar media hora mínima en jornada continua; conservar el cómputo como tiempo efectivo cuando no se pueda salir. Añadir los topes diarios y de distribución de horas extra y el máximo combinado de doce horas diarias. Corregir el resumen a 9/9/10/11/12 horas por año. Fuentes: [LFT, artículos 61–68](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFT.pdf) y [decreto de jornada de 2026](https://www.diputados.gob.mx/LeyesBiblio/ref/lft/LFT_ref52_01may26.pdf). La remisión general a la LFT reduce el riesgo, pero no impide llenar mal estos campos.

### H09. La cláusula de teletrabajo no completa el paquete requerido

**Ubicación:** [contrato individual](templates/contrato-individual-de-trabajo/plantilla.md), líneas 217–235; [FUENTES.md](FUENTES.md).

**Problema:** no concreta mecanismos de contacto y supervisión; difiere el procedimiento de reversibilidad y habla genéricamente de las normas «que emita» la STPS. La NOM-037-STPS-2023 ya existe.

**Corrección:** definir esos mecanismos y el procedimiento; enlazar una política, lista de verificación y evidencias de capacitación conforme a la [NOM-037-STPS-2023](https://sidof.segob.gob.mx/notas/docFuente/5691672). Coordinar con contrato colectivo o reglamento interior según los [artículos 330-B a 330-G de la LFT](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFT.pdf). No basta firmar la cláusula: hay obligaciones operativas. Un anexo separado es una opción práctica, no una forma obligatoria universal.

### H10. Se aplica el Código Civil Federal como si fuera el código civil de todo México

**Ubicación:** [asesoría](templates/contrato-de-asesoria/plantilla.md), líneas 46 y 152–154; [NDA unilateral](templates/convenio-de-confidencialidad-unilateral/plantilla.md), línea 150.

**Problema:** la asesoría se define civil y se somete directamente al CCF; el NDA ofrece la misma ruta civil sin identificar entidad federativa. El CCF rige asuntos federales. La elección de una ciudad no resuelve por sí sola la ley sustantiva aplicable.

**Corrección:** identificar naturaleza mercantil o civil, estado y reglas de conflicto. Para materia mercantil, justificar la aplicación del Código de Comercio y su supletoriedad; para materia civil local, adaptar al código estatal y a sus formalidades. Fuentes: [CCF, artículos 1 y 13–14](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCF.pdf) y [Código de Comercio](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCom.pdf). Es un problema de adaptación territorial, no nulidad automática.

### H11. Las opciones de transferencias no distinguen bien excepción legal y protección contractual adicional

**Ubicación:** [convenio de transferencia](templates/convenio-de-transferencia-de-datos-personales/plantilla.md), líneas 113–129 y notas 3–5.

**Problema:** una reestructura aparece como opción de base jurídica sin identificar un supuesto legal; además, se afirma que siempre se debe obtener consentimiento para datos sensibles o financieros aunque se haya elegido una excepción.

**Corrección:** identificar la fracción concreta del artículo 36 o el consentimiento aplicable. Una fusión, venta o inversión no es por su nombre una excepción general. Separar los compromisos adicionales voluntarios de lo que la ley exige. No afirmar que toda excepción desaparece por la clase de dato. Fuente: [LFPDPPP, artículos 7–9 y 35–36](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf). Exigir contractualmente más protección puede ser lícito; describirla como obligación legal universal es inexacto.

### H12. La corrección de precios por error se presenta como facultad unilateral

**Ubicación:** [términos de uso](templates/terminos-y-condiciones-de-uso/plantilla.md), línea 82, cláusula SEXTA.6.

**Problema:** ante un supuesto error evidente, el consumidor solo podría pagar más o aceptar la devolución. Eso puede excluir su pretensión de cumplimiento del precio ofrecido.

**Corrección:** excluir de esta regla los derechos irrenunciables del consumidor. Si existe un error que pueda afectar el consentimiento, tratarlo conforme a la ley y al caso concreto, sin que la sola afirmación del proveedor cierre la controversia. Fuentes: [LFPC, artículos 7 y 42](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo120869.html) y [CCF, reglas de error en el consentimiento](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCF.pdf). No se concluye que cualquier precio erróneo deba cumplirse en toda circunstancia.

### H13. La reforma de competencia de 2025 se etiqueta como una ley nueva

**Ubicación:** [README del contrato marco](templates/contrato-marco-de-prestacion-de-servicios/README.md), línea 55; [FUENTES.md](FUENTES.md), línea 36.

**Problema:** el primero dice «nueva ley, DOF 16-07-2025». La LFCE se publicó el 23 de mayo de 2014; el cambio de 2025 es una reforma.

**Corrección:** identificar publicación original, reforma relevante y última reforma del texto consultado por separado. Fuente: [LFCE de la Cámara de Diputados](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFCE.pdf). Este error es documental y no invalida por sí mismo la advertencia sobre acuerdos de no contratación. El alcance de cualquier pacto concreto exige análisis de competencia.

### H14. La anotación de datos de salud contradice el límite sobre HIPAA

**Ubicación:** [contrato de encargado](templates/contrato-de-encargado-de-datos-personales/plantilla.md), línea 109, frente a la nota 2, línea 389, y su [README](templates/contrato-de-encargado-de-datos-personales/README.md).

**Problema:** la anotación de la cláusula SÉPTIMA dice que «reemplaza» un BAA estadounidense; los otros textos aclaran que no lo sustituye.

**Corrección:** describirla como protección de datos sensibles bajo derecho mexicano y eliminar la afirmación de sustitución. Es una contradicción interna de alcance; esta revisión no emite una opinión sobre cumplimiento estadounidense. En salud deben evaluarse también las normas mexicanas sectoriales aplicables.

## Contraste con la investigación de Gemini

Documento comparado: [Proyecto Arquitectónico para un Repositorio de Plantillas Legales en México](https://share.gemini.google/zUUze8vwWblu), leído en su página compartida. La tabla siguiente resume sus propuestas; no reproduce sus conclusiones como hechos confirmados.

| Tema de la investigación | Evaluación y decisión para este repositorio |
|---|---|
| Adaptar jurídicamente, en vez de traducir documentos estadounidenses | Correcto como método; el repositorio ya lo sigue en buena parte. |
| INAI como autoridad actual de particulares | Desactualizado. El repositorio acierta al identificar a la Secretaría Anticorrupción y Buen Gobierno. Fuente: [LFPDPPP, artículos 2 XV y 38–39](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf). |
| Cesión patrimonial gratuita si es expresa | Incorrecto como regla general de cesión autoral. El convenio de cesión del repositorio acierta al exigir onerosidad. No confundir cesión con cualquier licencia gratuita. Fuente: [LFDA, artículos 30–31](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo17068.html). |
| SAS como vehículo ideal y estatutos en Markdown | No es una recomendación universal. La constitución SAS usa el sistema y estatutos de Economía; un archivo no los sustituye. Fuente: [LGSM, artículos 260–264](https://www.diputados.gob.mx/LeyesBiblio/pdf/LGSM.pdf). Una guía de elección societaria sería más útil que prometer una constitución por plantilla. |
| Todo contrato de adhesión necesita aprobación o registro | Generalización incorrecta. El registro obligatorio depende de ley o NOM; no nace solo de ser un contrato de adhesión. El README de términos ya lo matiza. Fuente: [LFPC, artículos 85–87](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo12974.html). |
| NMX de comercio electrónico y Código de Ética como un mismo paquete obligatorio | Separar instrumentos. La NMX está [vigente en el catálogo de Economía](https://platiica.economia.gob.mx/normalizacion/nmx-coe-001-scfi-2018/) y el artículo 76 Bis 1 de la [LFPC](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo120869.html) remite a la Norma Mexicana. No debe descartarse como irrelevante por ser NMX. En cambio, la adopción del [Código de Ética, artículo 2](https://sidof.segob.gob.mx/notas/docFuente/5612351), es voluntaria y su cumplimiento vincula a quien lo adopta. Falta añadir esta distinción y una matriz de implementación. |
| Declaraciones y anexos que «blindan» la materialidad fiscal | Los entregables y registros ayudan, pero el contrato no garantiza efectos fiscales. Es recomendable añadir evidencia de servicios y diligencia sobre listas, sin prometer inmunidad. Fuente: [SAT, RMF 2026, regla 2.9.18](https://www.sat.gob.mx/minisitio/NormatividadRMFyRGCE/documentos2026/rmf/rmf/RMF_2026-DOF-28122025.pdf). |
| Un RIT sustituye la contratación individual o es requisito de toda rescisión | Incorrecto como regla general. Son instrumentos distintos. Las causas legales de rescisión no se crean ni eliminan por tener un RIT. Fuente: [LFT, artículos 24–26, 47 y 422–425](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFT.pdf). Sí debe atenderse la regla específica de teletrabajo del artículo 330-D. |
| Adenda de teletrabajo | Necesidad material atendida parcialmente por la cláusula existente; H09 explica el faltante. La ley exige contenido escrito y controles, no necesariamente un archivo separado. |
| Jornadas descritas sin transición futura | Insuficiente para el corte actual. El repositorio incorpora correctamente la transición de 2026; no debe reemplazarse por la descripción estática de la investigación. Fuente: [decreto DOF 01-05-2026](https://www.diputados.gob.mx/LeyesBiblio/ref/lft/LFT_ref52_01may26.pdf). |
| Destruir toda información financiera inmediatamente después del pago | No debe adoptarse como obligación universal. Distinguir datos completos de tarjeta, comprobantes y registros que deban conservarse. La retención necesita inventario y base jurídica; la [LFPDPPP](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf) no impone esa fórmula universal. |
| Modelos INDAABIN para arrendamiento privado | Pueden ser referencia estructural, pero las reglas de contratación pública no se trasladan automáticamente. Adaptar al derecho local del inmueble. Fuente: [CCF, artículo 13 III](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCF.pdf). |
| Contratos financieros RECA para cualquier startup | No corresponde a SaaS general. La exclusión de servicios financieros regulados en términos es razonable. Una ampliación financiera requiere revisión sectorial propia; esta auditoría no valida modelos RECA. |

## Cobertura de las 13 plantillas

«Sin defecto adicional confirmado» significa únicamente que esta revisión no identificó otro problema específico que pueda sostener con la evidencia consultada. No equivale a aprobación universal.

| Plantilla | Resultado documental | Acciones |
|---|---|---|
| Aviso integral | Requiere correcciones | H01, H07; concretar excepciones y prácticas reales. |
| Aviso simplificado | Requiere ajustar las opciones de consentimiento | H01; limitar versiones según datos y transferencias. |
| Aviso de cookies | Requiere adaptación de implementación | Elegir un modelo coherente: el banner y panel prometen aceptación, pero la sección 4 ofrece activar desde el ingreso. El rechazo debe funcionar. No se identificó una regla mexicana universal que imponga el mismo modelo previo para toda cookie; sí deben respetarse los consentimientos y excepciones aplicables. |
| Contrato de encargado | Requiere correcciones | H06, H14; completar anexos y países. Los plazos internos de 24/48/72 horas son compromisos contractuales, no un plazo legal mexicano universal. |
| Convenio de transferencia | Requiere correcciones y decisiones jurídicas | H01, H11; no cerrar una operación con «confirmar con tu abogado» como única base. |
| Contrato individual | Requiere correcciones | H03, H08, H09; revisar además la opción de no competencia según el caso. La advertencia existente no garantiza exigibilidad. |
| Carta oferta | Sin defecto adicional confirmado dentro de su alcance | Mantener coherencia con contrato; no iniciar trabajo sin las condiciones escritas. El aviso laboral que exige no está incluido en la biblioteca. |
| Contrato de asesoría | Requiere correcciones | H05, H10; distinguir ideas e invenciones de obras autorales y definir entregables. |
| Cesión de propiedad intelectual | Base consistente en onerosidad, escritura y derechos morales; requiere concretar activos y formalidades | Registrar cuando se necesiten efectos frente a terceros; no borrar esa cooperación como si fuera irrelevante. No extender automáticamente la excepción del software a cualquier manual o documentación independiente. |
| Contrato marco | Requiere correcciones | H04, H13; filtrar consumidores aunque sean personas morales; completar órdenes y documentación REPSE solo cuando corresponda. |
| NDA mutuo | Sin defecto adicional confirmado para un negocio mercantil entre empresas | No sustituye una base de tratamiento ni un contrato de encargado/transferencia. |
| NDA unilateral | Requiere adaptar el supuesto civil | H10; conservar la distinción entre persona física y empresa. |
| Términos de uso | Requiere correcciones | H02, H12; incorporar matriz de comercio electrónico y autorizaciones de datos. |

## Elementos que conviene conservar

- Nueva LFPDPPP de 2025 y sustitución del INAI; distinción básica entre responsable, encargado, remisión y transferencia.
- Separación de finalidades primarias y secundarias; negativa sin pérdida del servicio.
- Consideración de personas morales como posibles consumidores; no se debe clasificar solo por RFC o tipo societario.
- Aviso previo de cinco días para renovaciones, junto con las correcciones de consentimiento de H02.
- Calendario de reducción de jornada y horas extra de los transitorios de 2026; mantenimiento del salario.
- Vacaciones, prima vacacional, aguinaldo, seguridad social y reconocimiento de subordinación real.
- Cesión autoral escrita y onerosa, respeto a derechos morales y separación de materiales previos.
- Advertencias sobre subcontratación, REPSE, responsabilidad solidaria y no contratación entre competidores.

## Ampliaciones útiles, sin calificarlas como defectos generales

1. Aviso de privacidad para candidaturas y personal: varios documentos lo exigen y la biblioteca no lo proporciona.
2. Paquete de teletrabajo: política, reversibilidad, verificación y registros, coordinado con el RIT o contrato colectivo aplicable.
3. Guía de SAS, S.A., S. de R.L. y S.A.P.I., con límites y trámites, sin elegir una forma por defecto para toda startup.
4. Anexo de materialidad: alcance, entregables, aceptación, bitácoras, evidencias y pagos, con conservación y diligencia fiscal.
5. SLA y salida de SaaS: disponibilidad, soporte, exportación, respaldos y borrado conforme al rol de cada parte.
6. Matriz de LFPC 76 Bis/76 Bis 1 y NMX: texto contractual, pantalla o flujo, evidencia y persona responsable. El documento por sí solo no prueba que el producto cumple.

## Fuentes y cierre de vigencia

Las referencias jurídicas de esta revisión proceden de fuentes oficiales; Gemini únicamente sirvió para la comparación. Se consultaron, entre otras:

| Fuente primaria | Uso en esta revisión |
|---|---|
| [LFPDPPP, texto de Diputados](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf) | Artículos de consentimiento, ARCO y transferencias; el texto consultado indica reforma DOF 14-11-2025. |
| [LFT, texto de Diputados](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFT.pdf) | Jornada, invenciones y teletrabajo; el texto consultado indica reforma DOF 14-05-2026. |
| [Decreto de jornada, DOF 01-05-2026](https://www.diputados.gob.mx/LeyesBiblio/ref/lft/LFT_ref52_01may26.pdf) | Reglas transitorias de jornada, horas extra y disposiciones de registro. |
| [Decreto de suscripciones, DOF 12-12-2025](https://sidof.segob.gob.mx/notas/docFuente/5775999) | Consentimiento expreso, aviso previo y cancelación. |
| [LFDA, Diputados](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFDA.pdf) y [texto de Orden Jurídico Nacional](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo17068.html) | Cesiones, remuneración y software. El segundo conserva una consolidación de 2020; no debe citarse su encabezado como prueba de actualización a 2026. |
| [CCF](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCF.pdf), [Código de Comercio](https://www.diputados.gob.mx/LeyesBiblio/pdf/CCom.pdf) y [LGSM](https://www.diputados.gob.mx/LeyesBiblio/pdf/LGSM.pdf) | Consentimiento, ámbito civil/mercantil y constitución SAS. |
| [LFPC, Diputados](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPC.pdf) y [Orden Jurídico Nacional](https://www.ordenjuridico.gob.mx/Documentos/Federal/html/wo120869.html) | Precios, comercio electrónico y adhesión; complementar la versión histórica con los decretos posteriores. |
| [Reglamento de datos de 2011](https://www.diputados.gob.mx/LeyesBiblio/regley/Reg_LFPDPPP.pdf) | Reglas detalladas de encargados; lectura condicionada a su compatibilidad y vigencia actuales. |
| [NOM-037-STPS-2023](https://sidof.segob.gob.mx/notas/docFuente/5691672) | Política y controles de teletrabajo. |
| [LFCE](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFCE.pdf) | Fecha original de expedición frente a reforma. |
| [NMX en catálogo de Economía](https://platiica.economia.gob.mx/normalizacion/nmx-coe-001-scfi-2018/), [Código de Ética](https://sidof.segob.gob.mx/notas/docFuente/5612351) y [Ley de Infraestructura de la Calidad, artículo 73](https://www.diputados.gob.mx/LeyesBiblio/pdf/LICal_010720.pdf) | Distinguir norma, remisión legal y adopción voluntaria del Código. |
| [RMF 2026, SAT](https://www.sat.gob.mx/minisitio/NormatividadRMFyRGCE/documentos2026/rmf/rmf/RMF_2026-DOF-28122025.pdf) | Evidencia de operaciones y límites de una declaración contractual. |

**Pendientes para una afirmación formal de actualización integral:** cerrar el cotejo de los artículos autorales con la consolidación actual completa, revisar exhaustivamente sustituciones o adecuaciones del Reglamento y Lineamientos de datos, verificar disposiciones STPS del registro de jornada de 2027 y actualizar las referencias fiscales según operación y régimen. Las dificultades de recuperación no son evidencia de inexistencia de una reforma. No se afirma que esas disposiciones no hayan sido publicadas.

## Orden sugerido de corrección

1. Resolver H01–H06 y elegir bases jurídicas y alternativas contractuales exigibles.
2. Resolver H07–H14 y sincronizar cada README con su plantilla.
3. Cerrar las verificaciones de vigencia señaladas; sustituir «ley nueva, confirmar después» por artículos y reglas comprobados.
4. Actualizar `FUENTES.md` con publicación original, reforma, entrada en vigor y alcance de cada fuente; añadir NOM-037 y la matriz de comercio electrónico.
5. Revisar los documentos ya completados y su implementación con una persona abogada en México antes de tratarlos como un paquete validado.

No debe actualizarse masivamente la fecha de «última revisión» como sustituto de resolver estos puntos.
