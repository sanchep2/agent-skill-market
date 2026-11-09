# Skills disponibles en Talent Academy

He recopilado los **skills visibles en la página de Recursos de Talent Academy**. En la columna **IA compatible / dónde instalar** se indican únicamente las plataformas mencionadas explícitamente en la página.

> **Nota:** No se incluye **CLAUDE.md + AGENTS.md**, porque la propia página aclara que es una plantilla y no un skill. **Talent Factory** aparece en una sección separada porque se presenta como un toolkit que contiene un motor y 17 skills.

| Título | Descripción | IA compatible / dónde instalar |
|---|---|---|
| Linear — Gestión de issues, cycles y projects | Gestiona Linear de extremo a extremo: issues, ciclos, proyectos, milestones, initiatives, triage, sub-issues, backlog, API GraphQL, MCP y webhooks. | **Claude Code**. Instalar en `~/.claude/skills/` o `.claude/skills/`. |
| Talent Issue Craft — Issues de calidad para agentes | Convierte ideas en issues ejecutables mediante nueve tipos de tareas, plantillas, rúbricas de verificación, decisiones estructuradas y un auditor de calidad. | **Claude Code**. |
| Convex — Backend reactivo en TypeScript | Cubre base de datos reactiva, queries, mutations, actions, esquemas, autenticación, sincronización en tiempo real, RAG, almacenamiento, cron y testing. | **Claude Code**. Instalar como `convex-skill`. |
| Railway — Deploy e infraestructura | Permite crear proyectos y servicios, provisionar bases de datos, configurar entornos, variables, volúmenes, dominios, buckets, health checks y despliegues. | **Claude Code**. Instalar la carpeta `railway`. |
| Next.js — Skill de App Router | Desarrollo con Next.js 16 y App Router, incluyendo Server Components, Server Actions, caché, internacionalización, Playwright, Vitest y Core Web Vitals. | **Claude Code**. Instalar como `nextjs-web`. |
| Supabase — Skill completa | Cubre Auth, PostgreSQL, PostgREST, RLS, Storage, Edge Functions, Realtime, pgvector, RAG, cron, colas e integración móvil y web. | **Claude Code**. Instalar como `supabase-skill`. |
| Nano Banana Pro — Imágenes con Gemini e Imagen 4 | Genera, edita y combina imágenes con Gemini 3 Pro Image e Imagen 4. Incluye selección de modelos, prompts, Batch API, autenticación y control de errores. | **Claude Code**. |
| CodeRabbit — Revisión automática de PRs | Configura CodeRabbit, clasifica comentarios de revisión por severidad, aplica correcciones, resuelve hilos y automatiza controles antes del merge. | **Claude Code**. Instalar como `coderabbit-review`. |
| Docs-as-Code — Documentación con Diátaxis, ADRs y CI | Implementa documentación como código con Diátaxis, ADRs MADR 4.0, Markdownlint, Vale, cspell, Lychee y validación mediante CI. | **Claude Code**. Instalar como `docs-as-code`. |
| Tech-Debt Audit — Auditoría de deuda técnica | Audita mantenibilidad, estructura y deuda técnica con referencias `archivo:línea`, severidad, esfuerzo, confianza y operación de solo lectura por defecto. | **Claude Code**. Instalar como `tech-debt-audit`. |
| Stripe — Pagos, suscripciones y facturación | Implementa PaymentIntents, Checkout, suscripciones, Stripe Elements, Connect, webhooks, Stripe Tax, seguridad PCI y pruebas. | **Claude Code**. |
| Google Analytics 4 — Reporting y configuración | Maneja Data API, Admin API, Measurement Protocol y BigQuery Export para reportes, configuración, eventos server-side y datos sin muestreo. | **Claude Code**. |
| Google Tag Manager — Tracking y píxeles | Crea tags, triggers y variables con GTM API v2. Integra Meta, GA4, LinkedIn, TikTok, X, Google Ads, Consent Mode v2 y server-side tagging. | **Claude Code**. |
| NOWPayments — Pagos en criptomonedas | Integra pagos, invoices, webhooks IPN, suscripciones en cripto, payouts, cuentas de custodia, conversiones y widgets para más de 350 monedas. | **Claude Code**. |
| Android Nativo — Apps modernas en Kotlin puro | Construye aplicaciones Android con Kotlin, Jetpack Compose, Material 3, MVVM/MVI, Coroutines, Retrofit, Room, Hilt, CameraX y WorkManager. | **Claude Code**. Instalar como `android-native`. |
| iOS Nativo — Apps modernas en Swift puro | Construye aplicaciones iOS con SwiftUI, TCA o MVVM, async/await, actors, URLSession, SwiftData, widgets, Live Activities y testing. | **Claude Code**. Instalar como `ios-native`. |
| Hyperliquid — Trading de perpetuos y DeFi | Construye bots y herramientas para Hyperliquid, con órdenes, datos de mercado, posiciones, apalancamiento, WebSocket, EIP-712 y controles de riesgo. | **Claude Code**. |
| Amazon SES — Infraestructura de email | Implementa email profesional con Amazon SES v2, DKIM, SPF, DMARC, BIMI, warm-up, webhooks, bounces, supresión y arquitecturas multi-tenant. | **Claude Code**. |
| IA local — Tu propio modelo corriendo en tus GPU | Monta un servidor local con un modelo de 35.000 millones de parámetros, cinco usuarios, modos rápido y razonamiento y medición de consumo. | **Claude Code**. Requiere Ubuntu, dos GPU NVIDIA RTX 50 idénticas con al menos 16 GB cada una y 70 GB libres. |
| Google Ads — API v24, campañas y creatividades | Trabaja con Google Ads API v24, GAQL, OAuth, campañas Search, Performance Max, Demand Gen, Shopping, Video y App, reporting y conversiones. | **Claude Code**. Instalar como `google-ads-api`. |
| Memoria de Claude — Establece, limpia y repara la memoria | Crea, diagnostica, repara y compacta la memoria persistente de proyectos, incluyendo `CLAUDE.md` y `.claude/memory/`, con snapshots y verificación. | **Claude Code**. Instalar como `talent-memoria`. |
| Buzz — Tu propio chat de agentes IA self-hosted | Despliega un chat de agentes sobre Nostr, con relay local, orquestador, identidades propias, Tailscale, kill switches y aplicación Android. | **Claude Code**. Instalar como `talent-buzz`. |
| Talent PRD — De la idea al PRD aprobado con su backlog | Convierte una idea, repositorio o PRD existente en un PRD validado y un backlog trazable mediante un pipeline de siete fases. | **Claude Code**. Instalar como `talent-prd`. |
| GPT Image 2 — Ads y creatividades de campaña | Produce creatividades para feeds, stories, banners y heros, incluyendo texto, CTA, personajes consistentes, safe zones y dimensiones por plataforma. | **Claude Code**. Puede utilizar un puente con **Codex CLI** o la API de OpenAI, pero la página lo presenta como skill instalable para Claude Code. |
| Barra de estado de Claude Code — Con tu consumo por modelo | Muestra proyecto, rama, PR, modelo, nivel de esfuerzo, tokens, límites de uso y consumo semanal en la barra de estado. | **Claude Code** en macOS, Linux y Windows. |
| Resend — Skill de email transaccional y marketing | Implementa correos transaccionales y campañas con Resend, incluyendo lotes, idempotencia, dominios, DKIM, SPF, DMARC, webhooks y MCP. | **Claude Code**. Instalar como `resend-skill`. |
| Reddit Search — Investiga en Reddit con citas literales | Investiga Reddit y entrega citas literales con enlace, subreddit, autor, fecha y votos. Puede usar You.com, Arctic Shift, Redlib, Brave, Perplexity y Firecrawl. | **Claude Code, Codex y Hermes**. Requiere Python 3.9 o superior. |
| Grok Search — Busca en X con posts literales | Busca en X y devuelve publicaciones literales, autor, fecha y métricas. Funciona con Grok Build o mediante OpenRouter y modelos de xAI. | **Claude Code, Codex y Hermes**. Probado principalmente con Claude Code en macOS. Requiere Python 3.9 o superior. |
| LinkedIn Search — Busca en LinkedIn con publicaciones literales | Busca publicaciones de LinkedIn y devuelve texto, autor, fecha y métricas, utilizando buscadores externos y proveedores como Apify o Bright Data. | **Claude Code, Codex y Hermes**. Probado con Claude Code en macOS. Requiere Python 3.9 o superior. |
| Meta Search — Busca en Instagram, Threads y Facebook | Busca contenido público en las plataformas de Meta y entrega publicaciones, autores, fechas y métricas mediante buscadores, Apify y Bright Data. | **Claude Code, Codex y Hermes**. Probado con Claude Code en macOS. Requiere Python 3.9 o superior. |
| Exa Search — Busca y lee la web con Exa | Busca noticias, publicaciones científicas, empresas, personas y código. Lee páginas completas y devuelve citas literales, fuentes y coste de la consulta. | **Claude Code, Codex y Hermes**. Probado en macOS y mediante pruebas automáticas en Linux. Requiere Python 3.9 o superior. |
| Perplexity Search — Busca en la web con filtros finos | Utiliza la Search API y Agent API de Perplexity con filtros de dominio, fecha, país e idioma, citas, fuentes y controles de presupuesto. | **Claude Code, Codex y Hermes**. Probado en macOS y Linux. Requiere Python 3.9 o superior. |
| Firecrawl Search — Busca, lee y recorre sitios web | Busca páginas, noticias e imágenes; lee sitios y PDF; genera mapas de URLs; procesa lotes y recorre sitios con límites de páginas y créditos. | **Claude Code, Codex y Hermes**. Probado en macOS y Linux. Requiere Python 3.9 o superior. |
| Brave Search — Busca en web, noticias, vídeos e imágenes | Utiliza el índice de Brave para buscar distintas clases de contenido, extraer contexto, devolver citas literales y controlar el gasto por búsqueda. | **Claude Code, Codex y Hermes**. Probado en macOS y Linux. Requiere Python 3.9 o superior. |

## Toolkit adicional

| Título | Descripción | IA compatible / dónde instalar |
|---|---|---|
| Talent Factory — Fábrica de software con agentes | Toolkit con instalación guiada, motor de controles locales, recibos sellados, plantillas, pruebas y **17 skills para Claude Code**. Configura la fábrica en fases F0 a F8 y valida cada etapa antes de continuar. | **Claude Code**. Se descomprime el ZIP, se abre Claude Code en la carpeta y se inicia la instalación guiada. |

## Resumen de compatibilidad

- **Exclusivos o dirigidos principalmente a Claude Code:** la mayoría de los skills de desarrollo, infraestructura, documentación, pagos, analytics, aplicaciones nativas, email y gestión de proyectos.
- **Claude Code + Codex + Hermes:** Reddit Search, Grok Search, LinkedIn Search, Meta Search, Exa Search, Perplexity Search, Firecrawl Search y Brave Search.
- **No es un skill:** `CLAUDE.md + AGENTS.md` es una plantilla para colocar en la raíz de un repositorio y usarla con Claude Code.

## Fuente

Información extraída de la página **Recursos** de Talent Academy el 6 de noviembre de 2026.
