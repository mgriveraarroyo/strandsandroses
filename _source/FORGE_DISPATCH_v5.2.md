---
title: "FORGE-Digital · DISPATCH v5.2 · Angel salón Strands & Roses · 15 cambios consolidados"
status: READY-FOR-DISPATCH
dispatch_target: Manus task v5.2 quirúrgico
created: 2026-05-20 ~7:20 PM AST
authority: Omega Cofundador · post defect honest cadena producción · reactivación wave Angel v5.2
predecessor: v5.1 LIVE `mgriveraarroyo.github.io/strandsandroses/` · feedback "Chefs kiss" Angel 2026-05-18 + PAUSA Soberana levantada implícita 2026-05-20
---

# FORGE-Digital · DISPATCH v5.2 · Angel salón

> Iteración quirúrgica · NO rebuild. v5.1 LIVE en `mgriveraarroyo.github.io/strandsandroses/` con feedback positivo del cliente ("Chefs kiss"). 15 cambios consolidados de request cliente + feedback + info nueva 2026-05-20.

---

## §0 · CONTEXTO

- **Sitio LIVE actual:** `https://mgriveraarroyo.github.io/strandsandroses/` HTTP 200
- **Cliente:** Angel · hermano del Soberano · ATL · salón premium puro hair & lash (post-pivot · NO más pintura)
- **Idioma:** inglés (1er idioma cliente)
- **Backend:** Square (Appointments + bundles · NO duplicar gestión)
- **Marca:** Strands & Roses · warm-brown #B23939 · accent rojo · Fraunces serif + Poppins sans
- **30 fotos IG reales descargadas previas:** `inputs/ig-real-images/` (preservar uso)

---

## §1 · 15 CAMBIOS QUIRÚRGICOS CONSOLIDADOS

### A. Conceptual (preservar base validada · NO romper)

**A1 · Eliminación completa de arte/pintura (verificar)**
- Confirmar en v5.1 LIVE: 0 mención `@angel.paints.atl` · 0 sección Fine Art Gallery · 0 The Crossover · 0 assets artwork-*
- Si queda algún rastro · eliminar
- Concepto solidificado: salón premium puro hair & lash · NO mezcla

**A2 · Preservar base v4/v5 que Angel aprobó**
- Cursor custom · magnetic hover CTAs · parallax hero · reveal coreografiado
- Cormorant + Inter dual · paleta lino/tinta/ámbar/fucsia
- NO romper lo que dijo "Chefs kiss"

### B. Hero quirúrgicos (feedback directo Angel sobre v5.1)

**B1 · Quitar 1er círculo hero "THE ANGEL BEHIND THE CHAIR"**
- Razón cliente verbatim: "redundante, ya aparece bajo el nombre del negocio"
- Eliminar el círculo completo con esa tagline overlay del hero
- Mantener resto del hero limpio

**B2 · Recolorear 2do círculo hero "HAIR · LASH · GENDER NEUTRAL — ATLANTA, GA"**
- Cambiar color del 2do círculo al MISMO rosa del título principal
- Razón cliente: "más visibilidad/contraste"
- Mantener position y forma · solo color

### C. Funcionales · QA Chrome v2 FAILs (3 críticos · cliente-final usa esto)

**C1 · Form contacto B1 · fix comportamiento real**
- v5.1 tiene atributos puestos pero submit nativo gana → NO envía
- Interceptar submit con JS · fetch a Web3Forms (key cliente pending · usar mailto: fallback como paellasymas)
- Aceptación medida ejecutando el form en navegador real · NO grep de strings (CAP-004 vivo)

**C2 · Form newsletter B2 · fix comportamiento real**
- Misma issue que C1
- Misma solución: interceptar + fetch + mailto: fallback

**C3 · Galería Instagram widget B3**
- v5.1 tiene placeholder
- Opción A: Elfsight Instagram Feed widget free tier (placeholder ID · Angel provee post-validación)
- Opción B (preferida R47): self-hosted grid responsive de fotos IG real ya descargadas en `inputs/ig-real-images/`
- Patrón paralelo a paellasymas IG self-hosted (PATTERN-003 ELITE_PATTERNS_LIBRARY)

### D. UX móvil (QA Chrome v2 warnings)

**D1 · W5 overflow móvil**
- Agregar `overflow-x: hidden` al drawer/off-canvas mobile
- Test mobile 320px viewport

**D2 · W6 portrait bleed -16px**
- Revisar bleed del portrait en mobile · -16px aparente en QA Chrome
- Ajustar padding/margin para evitar crop

### E. Geolocalización (feedback Angel punto 6)

**E1 · Google Maps iframe + dirección clickable**
- Hoy dirección es solo texto
- Incorporar Google Maps iframe embed con marker del local
- Dirección textual sigue · pero clickable → abre Google Maps app/web
- Posición: sección Contact/Booking

### F. Toque marca (directiva Soberano)

**F1 · 🌹 Cursor rosa/pétalos (Strands & ROSES)**
- Modificar el cursor custom actual a algo SIMBÓLICO de la marca
- Opciones de craft:
  - Cursor con forma de rosa pequeña SVG
  - Cursor con rastro de pétalos cayendo al moverse
  - Cursor rosa minimalista con micro-shimmer
- Mantener device-aware INV-5 · solo desktop `pointer:fine and hover:hover`
- Mobile/tablet: oculto por completo
- Sutil · premium · NO recargado

### G. Lash Packages NUEVO (info 2026-05-20 · Opción C híbrida criterio Omega)

**G1 · Sección Lash Packages con anchor pricing + push Square**

**Decisión criterio R38 (Opción C híbrida · si Soberano discrepa P1 corrige):**
- 3 categorías visibles (Classic Girlie · Mega Gorgeous · Volume Queen)
- 1 precio anchor por categoría · "Desde $408 · 3 meses · 6 refills" (Classic Girlie ejemplo)
- Botón "Ver todas las opciones →" → link Square con los 6 packages completos
- NO listar los 6 precios planos (viola Fase 6b regla 8 NO catálogo)
- Pattern paralelo paellasymas precios anchored

**Data verbatim del cliente (Angel pasó via Soberano):**

| Package | 3 Meses | 6 Meses |
|---|---|---|
| Classic Girlie | $408 | $832 |
| Mega Gorgeous | $510 | $1,056 |
| Volume Queen | $450 | $944 |

- 3 meses: incluye 6 lash refills
- 6 meses: incluye 10 lash refills + 2 lash full sets

### H. Schedule nuevo (info 2026-05-20)

**H1 · Schedule semanal visible · sección Contact/Booking**

```
Sunday    9:00 AM – 6:00 PM
Monday    2:00 PM – 8:00 PM
Thursday  2:00 PM – 8:00 PM
Friday    2:00 PM – 8:00 PM
```

- No trabaja: Tuesday · Wednesday · Saturday (mostrar como "Closed")
- CTA "Book Appointment in Square →" debajo del schedule
- Schedule visible · NO confunde · NO sobre-elabora

### I. Testimonios reales Google (info 2026-05-20 · reemplazar actuales)

**I1 · Reemplazar 2 testimonios actuales por 2 reales Google verbatim**

**Testimonial 1 · Kenya:**
> *"Angel's lash services are absolutely top notch! I got a hybrid cat eye set today and I am obsessed! Her attention to detail, conversation, and wonderful spirit really sets her apart from any other stylist I've seen."*
> — Kenya

**Testimonial 2 · Natalie:**
> *"I've been coming to Angel to get my lashes done for almost 2 years and her services never disappoint. She's so kind and attentive and her energy is always on point. She makes you feel comfortable from the moment you walk in. Her salon is always clean and so inviting. The service is great, the conversation is great. I wouldn't go anywhere else for my lashes."*
> — Natalie

- Atribución "Google Reviews" sutil (verificable)
- Mantener componente visual existente de testimonios (Angel aprobó base)

---

## §2 · RESTRICCIONES (heredadas v5.1 · NO romper)

- INV-1 (0 IA visible) · INV-3 (0 placeholder defectuoso) · INV-5 (device-aware mobile 320px) · INV-9 (sigilo SVG · 0 emoji crudo)
- 0 frases vibra Soberano/Omega como copy literal (regla canon ELITE_PATTERNS · "VOZ del cliente · COMO nuestro")
- Branding real del intake preservado: #F5EFEF · #CC0000 · Fraunces · Poppins (NO revertir a placeholder genérico)
- Cero atribución IA/Manus en cualquier output cliente-facing
- Mailto: fallback en forms · Web3Forms key pending Angel (placeholder vacío trigger fallback)

---

## §3 · ENTREGABLE v5.2

ZIP `strandsandroses-v5.2.zip` con:
- `index.html` con 15 fixes aplicados
- `assets/` heredados (preservar fotos reales Angel · cursor custom · sigilo)
- `sitemap.xml` + `robots.txt` heredados
- `README_FORGE_DEPLOY_v5.2.md` con:
  - Cada fix · cómo lo resolviste · decisiones de craft
  - Para G1 packages: cómo implementaste Opción C híbrida + URL Square placeholder
  - F1 cursor rosa: qué forma exacta elegiste y por qué
  - C3 IG widget: Opción A (Elfsight) o B (self-hosted) elegida y por qué
  - QA self-report honest

---

## §4 · TARGET DOCTRINA 100%

Soberano canon: "demo cliente 100% o inaceptable · gap solo CLIENTE legítimo"

Gaps CLIENTE legítimos pre-aceptables (NO bloquean envío):
- C3 widget IG app-id real (Angel provee)
- C1/C2 Web3Forms key real (Angel provee · mailto fallback funciona desde día 1)
- F1 cursor rosa: si propones forma específica · Soberano valida

Gaps NUESTROS · inaceptables: cualquier de los 15 fixes no resuelto.

Post-entrega Code: QA local grep + Chrome multimodal obligatorio (doctrina QA cada versión) antes de envío Angel.

---

*FORGE-Digital DISPATCH v5.2 · Omega FORGE Ω orquesta · Manus craft quirúrgico · 15 fixes consolidados request cliente + Soberano + Omega criterio · target v5.2-final-pre-Angel-aprobación · cadena producción reactivada post defect honest · barco firme.*
