# Plan de Contenido SEO — Gestorlex MX

> Contexto para continuar el trabajo en sesiones futuras. Ver también el artifact visual con el mismo contenido: https://claude.ai/code/artifact/9c11a6c0-1ec9-4bef-a5c1-e85b4f1ab8d9

## Decisión de cadencia (2026-09-02)

- Las **4 páginas pilar de servicio** se redactan y publican **todas juntas** (son estructura del sitio, no contenido de blog — no tiene sentido escalonarlas).
- Los **16 artículos de blog** de apoyo sí se publican escalonados, ~1 cada 1-2 semanas, para poder revisarlos con la clienta con calma y tener material recurrente para redes/newsletter.
- Calendario sugerido de 12 semanas al final de este documento.

## Clusters y estado

Leyenda de estado: `pendiente` · `redactado` · `publicado`

### Cluster 01 — Licencias Municipales de Funcionamiento (prioridad alta)

- **Página pilar** — `licencias-municipales-guadalajara-zapopan.html` — **redactado**
  - Keyword: licencia de funcionamiento zapopan / licencias municipales guadalajara
  - Title: Licencias Municipales en Guadalajara y Zapopan | Gestorlex MX
- Blog:
  - Requisitos para la Licencia de Funcionamiento en Zapopan (2026) — *requisitos licencia funcionamiento zapopan 2026* — MOFU — **redactado** (`requisitos-licencia-funcionamiento-zapopan-2026.html`)
  - ¿Cuánto Cuesta una Licencia Municipal en Guadalajara? Costos y Tiempos — *cuánto cuesta licencia municipal guadalajara* — MOFU — **redactado** (`costo-licencia-municipal-guadalajara.html`)
  - Licencia de Giro Comercial: Qué Es y Quién la Necesita — *licencia de giro comercial qué es* — TOFU — **redactado** (`licencia-de-giro-comercial-que-es.html`)
  - Riesgos y Multas por Operar sin Licencia de Funcionamiento en Jalisco — *multa por operar sin licencia jalisco* — TOFU — **redactado** (`riesgos-multas-operar-sin-licencia-jalisco.html`)

**Cluster 01 completo (4/4 artículos + página pilar).**

### Cluster 02 — Registro Público de Comercio y Constitución de Empresas (prioridad alta)

- **Página pilar** — `registro-publico-comercio-jalisco.html` — **redactado**
  - Keyword: registro público de comercio jalisco / constituir empresa guadalajara
  - Title: Registro Público de Comercio y Constitución de Empresas en Jalisco | Gestorlex MX
- Blog (pendientes):
  - Cómo Registrar tu Empresa en Jalisco: Guía Paso a Paso (2026) — *cómo registrar una empresa en jalisco paso a paso* — MOFU
  - Persona Física vs. Persona Moral: ¿Cuál Conviene para tu Negocio? — *persona física vs persona moral diferencias* — TOFU
  - ¿Cuánto Tarda el Registro Público de Comercio en Jalisco? — *cuánto tarda registro público de comercio jalisco* — MOFU
  - Documentos para Inscribir tu Acta Constitutiva en el Registro Público — *documentos para inscribir acta constitutiva* — BOFU

### Cluster 03 — Trámites Administrativos y Uso de Suelo (prioridad alta)

- **Página pilar** — `tramites-administrativos-uso-de-suelo.html` — **redactado**
  - Keyword: trámites administrativos guadalajara / permiso de uso de suelo
  - Title: Trámites Administrativos y Uso de Suelo en Guadalajara | Gestorlex MX
- Blog (pendientes):
  - Uso de Suelo: Qué Es y Por Qué lo Necesitas Antes de Abrir tu Negocio — *qué es el uso de suelo* — TOFU
  - Trámites para Abrir un Negocio Formal en Guadalajara: Checklist Completo — *trámites para abrir un negocio en guadalajara* — MOFU
  - Permisos y Licencias para Abrir un Restaurante en Guadalajara — *permisos para restaurante guadalajara* — MOFU
  - Cómo Verificar el Uso de Suelo de un Predio en Guadalajara o Zapopan — *cómo saber uso de suelo de un predio* — TOFU

### Cluster 04 — Asesoría Legal para Emprendedores y Pymes (prioridad media)

- **Página pilar** — `asesoria-legal-empresas-guadalajara.html` — **redactado**
  - Keyword: asesoría legal para empresas guadalajara / asesoría legal emprendedores
  - Title: Asesoría Legal para Emprendedores y Empresas en Guadalajara | Gestorlex MX
- Blog (pendientes):
  - Contrato de Arrendamiento Comercial: 7 Cláusulas que No Debes Omitir — *qué debe incluir un contrato de arrendamiento comercial* — MOFU
  - 5 Pasos para Proteger Legalmente tu Negocio desde el Día Uno — *cómo proteger legalmente mi negocio* — TOFU
  - Gestor vs. Abogado: ¿Cuál Necesitas para Cada Trámite? — *gestor vs abogado diferencias* — TOFU
  - Obligaciones Legales de una PyME en México: Checklist Anual — *obligaciones legales de una pyme en méxico* — MOFU

## Recursos fuera de los clusters originales

- **Amparo por Suspensión de Línea Telefónica por Falta de Vinculación** — `amparo-suspension-linea-telefonica.html` — **publicado**
  - Tema de coyuntura (obligación de vinculación de líneas móviles, 2026), alto potencial de búsqueda puntual.
  - Guía paso a paso (en línea con e.firma/FIREL, o presencial) convertida a HTML indexable + descarga de formato de amparo editable (`descargas/gestorlex-formato-amparo-suspension-linea-telefonica.docx`) + CTA de WhatsApp.
  - Visible desde: aviso destacado en el hero del homepage, enlace desde Asesoría Legal, y tarjeta en `blog.html`. No está en el menú principal (no es un trámite recurrente).
  - Si el tema pierde vigencia con el tiempo, evaluar quitar el aviso del homepage pero dejar la página y los demás enlaces.

## Notas de implementación

- Hay una página `blog.html` que lista todos los artículos publicados. El menú de navegación (todas las páginas) enlaza ahí con "Blog"; el index ya no tiene una sección de blog embebida (se quitó por diseño). Cada artículo nuevo debe agregarse como tarjeta en `blog.html`.
- Las 4 páginas pilar reutilizan el header/footer reales de `index.html` (mismo logo, colores de marca `#00619d` / `#e45b00`, botón de WhatsApp) — no la plantilla vieja de `blog-single.html` / `blog-grid.html`, que sigue sin personalizar.
- El footer de todas las páginas ahora enlaza el bloque "Trámites" a las páginas pilar reales en vez de `#!`.
- Contenido de requisitos/proceso basado en fuentes oficiales (reglamento de comercio de Zapopan, Registro Público de la Propiedad y de Comercio de Jalisco) — **validar montos y plazos vigentes antes de publicar**, cambian por año fiscal.
- Cada artículo de blog, cuando se redacte, debe enlazar a su página pilar correspondiente con texto ancla natural.

## Calendario sugerido — 12 semanas (artículos de blog)

| Semana | Publicación | Cluster |
|---|---|---|
| 1 | 4 páginas pilar (ya redactadas, listas para revisión/publicación) | 01–04 |
| 2 | Licencia de giro comercial: qué es y quién la necesita | 01 |
| 3 | Cómo registrar tu empresa en Jalisco: guía paso a paso | 02 |
| 4 | Uso de suelo: qué es y por qué lo necesitas | 03 |
| 5 | Requisitos licencia de funcionamiento Zapopan 2026 | 01 |
| 6 | Persona física vs. persona moral | 02 |
| 7 | Trámites para abrir un negocio en Guadalajara: checklist | 03 |
| 8 | Gestor vs. abogado: ¿cuál necesitas? | 04 |
| 9 | ¿Cuánto cuesta una licencia municipal en Guadalajara? | 01 |
| 10 | Documentos para inscribir tu acta constitutiva | 02 |
| 11 | Permisos y licencias para abrir un restaurante | 03 |
| 12 | 5 pasos para proteger legalmente tu negocio | 04 |

## Próximos pasos

1. Revisar y aprobar las 4 páginas pilar con la clienta.
2. Publicarlas juntas (subir a producción, enviar sitemap a Search Console).
3. Configurar/optimizar Google Business Profile en paralelo.
4. Empezar redacción del primer artículo de blog (semana 2 del calendario).
