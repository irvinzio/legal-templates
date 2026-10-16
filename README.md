# Plantillas Legales para México

Plantillas legales gratuitas para startups y empresas de tecnología **en México**, escritas en lenguaje claro y basadas solo en **fuentes oficiales del gobierno de México**.

Este proyecto se inspira en [General-Legal/legal-templates](https://github.com/General-Legal/legal-templates), que tiene plantillas para Estados Unidos. Aquí adaptamos la idea a la ley mexicana: no es una traducción. Algunas plantillas de EE. UU. no tienen equivalente en México (por ejemplo, el *Business Associate Agreement* de HIPAA), y otras se tuvieron que cambiar por completo (por ejemplo, la *offer letter* de California se volvió un contrato individual de trabajo conforme a la Ley Federal del Trabajo).

> ⚠️ **Importante:** Estas plantillas no son asesoría legal. Son un punto de partida. Las leyes cambian (por ejemplo, la jornada laboral bajará cada año hasta 2030). Antes de firmar, revisa el texto vigente de la ley y, si puedes, consulta a una persona abogada con cédula profesional en México.

## Plantillas disponibles

### Protección de datos personales

| Plantilla | Para qué sirve | Equivalente en el repo de EE. UU. |
|---|---|---|
| [Aviso de privacidad integral](templates/aviso-de-privacidad-integral/) | Informar a las personas qué datos tratas, para qué y cómo ejercer sus derechos ARCO | Privacy Policy |
| [Aviso de privacidad simplificado](templates/aviso-de-privacidad-simplificado/) | Versión corta para formularios y apps | — |
| [Aviso de cookies](templates/aviso-de-cookies/) | Informar el uso de cookies y otras tecnologías de rastreo | Cookie Notice |
| [Contrato de encargado de datos personales](templates/contrato-de-encargado-de-datos-personales/) | Cuando un proveedor trata datos por cuenta de tu empresa | Data Processing Addendum / BAA |
| [Convenio de transferencia de datos personales](templates/convenio-de-transferencia-de-datos-personales/) | Cuando compartes datos con otra empresa que los usará para sus propios fines | Data Processing Addendum (Global) |

### Laboral y equipo

| Plantilla | Para qué sirve | Equivalente en el repo de EE. UU. |
|---|---|---|
| [Contrato individual de trabajo](templates/contrato-individual-de-trabajo/) | Contratar a una persona trabajadora por tiempo indeterminado | Employee Offer Letter |
| [Carta oferta de empleo](templates/carta-oferta-de-empleo/) | Ofrecer un puesto antes de firmar el contrato | Employee Offer Letter |
| [Contrato de asesoría](templates/contrato-de-asesoria/) | Contratar a un asesor externo (servicios profesionales) | Advisor Agreement |
| [Convenio de cesión de derechos de propiedad intelectual](templates/convenio-de-cesion-de-derechos-de-propiedad-intelectual/) | Pasar a la empresa el código, diseños o marcas que creó otra persona | — |

### Comercial

| Plantilla | Para qué sirve | Equivalente en el repo de EE. UU. |
|---|---|---|
| [Contrato marco de prestación de servicios](templates/contrato-marco-de-prestacion-de-servicios/) | Relación de servicios entre empresas con órdenes de servicio | Master Services Agreement |
| [Convenio de confidencialidad mutuo](templates/convenio-de-confidencialidad-mutuo/) | Ambas partes comparten información confidencial | Mutual NDA |
| [Convenio de confidencialidad unilateral](templates/convenio-de-confidencialidad-unilateral/) | Solo una parte comparte información confidencial | One-Way NDA |
| [Términos y condiciones de uso](templates/terminos-y-condiciones-de-uso/) | Reglas de uso de tu sitio web, app o SaaS | Terms of Use |

## Cómo está organizado

```
.
├── README.md          ← este archivo
├── FUENTES.md         ← lista de leyes y fuentes oficiales usadas
├── CONTRIBUIR.md      ← reglas para escribir o cambiar plantillas
├── LICENSE            ← CC0 1.0 (dominio público)
└── templates/
    └── <plantilla>/
        ├── README.md      ← qué es, cuándo usarla, fundamento legal, checklist
        └── plantilla.md   ← el texto completo del documento
```

## Cómo usar una plantilla

1. Lee el `README.md` de la plantilla. Ahí dice cuándo usarla y cuándo **no**.
2. Abre `plantilla.md` y cambia todo lo que está marcado así: <mark>[CAMPO PARA LLENAR]</mark>.
3. Borra las cláusulas marcadas como <mark>[OPCIONAL]</mark> que no necesites.
4. Borra la sección «Notas para quien llena la plantilla» al final.
5. Revisa la lista «Antes de firmar, revisa» del `README.md`.
6. Firma de forma autógrafa o electrónica (el Código de Comercio y el Código Civil Federal reconocen los medios electrónicos).

Las plantillas están en Markdown para que sean fáciles de leer, de comparar con `git diff` y de usar con herramientas de inteligencia artificial. Para pasarlas a Word puedes usar, por ejemplo, [Pandoc](https://pandoc.org/): `pandoc plantilla.md -o contrato.docx`.

## Cambios importantes en la ley que estas plantillas ya consideran

- **Nueva Ley Federal de Protección de Datos Personales en Posesión de los Particulares** (DOF 20 de marzo de 2025). Sustituyó a la ley de 2010. El INAI desapareció; ahora la autoridad es la **Secretaría Anticorrupción y Buen Gobierno**.
- **Reforma laboral de 40 horas** (Constitución, DOF 3 de marzo de 2026; Ley Federal del Trabajo, DOF 1 de mayo de 2026). La jornada baja poco a poco: 48 horas en 2026, 46 en 2027, 44 en 2028, 42 en 2029 y 40 en 2030. También pide un registro electrónico de la jornada.
- **Vacaciones dignas** (DOF 27 de diciembre de 2022): 12 días de vacaciones desde el primer año.
- **Reforma de subcontratación** (2021): se prohíbe subcontratar personal; solo se permiten servicios especializados con registro en el REPSE.

Revisa [FUENTES.md](FUENTES.md) para ver los enlaces oficiales.

## Licencia

[CC0 1.0 Universal](LICENSE). Puedes usar, copiar, cambiar y compartir estas plantillas sin pedir permiso y sin dar crédito.

## Contribuir

Lee [CONTRIBUIR.md](CONTRIBUIR.md). La regla más importante: **solo fuentes oficiales del gobierno de México**.
