# Cómo contribuir

Gracias por ayudar. Este documento explica las reglas para escribir o cambiar una plantilla.

## 1. Estructura de cada plantilla

Cada plantilla vive en su propia carpeta dentro de `templates/`:

```
templates/<nombre-de-la-plantilla>/
├── README.md      ← explicación: qué es, cuándo usarla, fundamento legal
└── plantilla.md   ← el texto completo del documento
```

### `README.md` de la plantilla

Usa siempre estas secciones, en este orden:

1. `# <Nombre de la plantilla>`
2. `## ¿Qué es?` – 2 o 3 frases simples.
3. `## ¿Cuándo usarla?` – lista corta de casos.
4. `## ¿Cuándo NO usarla?` – casos donde se necesita otro documento.
5. `## Puntos clave` – lista de las cláusulas más importantes y por qué existen.
6. `## Fundamento legal` – tabla con: ley, artículos, para qué sirve, enlace **oficial**.
7. `## Antes de firmar, revisa` – lista de verificación (checklist) con `- [ ]`.

### `plantilla.md`

1. Un aviso al inicio (bloque `>`), igual en todas las plantillas:

   > **Aviso:** Esta plantilla es un punto de partida y no es asesoría legal. Las leyes cambian. Antes de usarla, revisa el texto vigente de las leyes en las fuentes oficiales y, si puedes, consulta a una persona abogada con cédula profesional en México. Última revisión: <mark>16 de octubre de 2026</mark>.

2. El cuerpo del documento con la forma tradicional mexicana cuando sea un contrato:
   **Proemio** (quiénes firman) → **DECLARACIONES** → **CLÁUSULAS** → firmas.
3. Al final, una sección `## Notas para quien llena la plantilla` con consejos (esta sección se borra antes de firmar).

## 2. Campos para llenar

- Todo lo que el usuario debe cambiar va así: `<mark>[NOMBRE DE LA EMPRESA]</mark>`.
- Las opciones van así: `<mark>[ELIGE: opción A / opción B]</mark>`.
- Las cláusulas opcionales empiezan con `<mark>[OPCIONAL]</mark>`.

## 3. Lenguaje

- Español de México.
- **Lenguaje claro**: frases cortas, palabras comunes, voz activa. Pensamos en lectores que no son abogados y en personas que hablan español como segunda lengua.
- Evita palabras antiguas cuando hay una palabra simple (por ejemplo, «en lo sucesivo» → «en este contrato se le llamará»). Conserva los términos legales que la ley usa (por ejemplo, «responsable», «encargado», «derechos ARCO», «rescisión»).
- Usa lenguaje incluyente cuando sea natural («la persona trabajadora»).

## 4. Fuentes: solo oficiales

Solo citamos fuentes del gobierno de México:

| Dominio | Qué es |
|---|---|
| `diputados.gob.mx` | Cámara de Diputados – texto vigente de leyes federales |
| `dof.gob.mx` / `diariooficial.gob.mx` / `sidof.segob.gob.mx` | Diario Oficial de la Federación |
| `ordenjuridico.gob.mx` | Orden Jurídico Nacional (Segob) |
| `gob.mx` | Secretarías y órganos (STPS, SAT, Profeco, IMPI, Indautor, etc.) |
| `scjn.gob.mx` | Suprema Corte de Justicia de la Nación |
| `senado.gob.mx` | Senado de la República |

No uses blogs, despachos privados, Wikipedia ni otras fuentes no oficiales.

**Regla de oro:** si no puedes confirmar un número de artículo en una fuente oficial, cita la ley completa sin número de artículo. Es mejor citar menos que citar mal.
