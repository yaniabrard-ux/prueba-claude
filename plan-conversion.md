# Plan de Acción CRO: Del 0.3% al 1% — puraletra.com.ar

**Objetivo:** Triplicar la tasa de conversión (0.3% → 1%)
**Sitio:** tienda online de libros + club de lectura (Argentina)
**Benchmark industria:** ecommerce LATAM promedio 1–3%; librerías online ~0.8–1.5%

---

## Diagnóstico de base

Con una tasa de 0.3%, el problema no es el tráfico: es que **el sitio no convierte a quienes ya llegan**. Pasar al 1% significa convertir 1 de cada 100 visitantes en lugar de 3 de cada 1000. No se necesita más tráfico — se necesita reducir la fricción en el camino a la compra.

Las causas más probables en una librería online argentina con esta tasa:

1. Proceso de compra con demasiados pasos o datos requeridos
2. Falta de confianza/prueba social visible
3. UX móvil deficiente (>60% del tráfico argentino es mobile)
4. Velocidad de carga lenta
5. CTAs poco claros o propuesta de valor débil
6. Sin recuperación de carritos abandonados
7. Sin urgencia ni incentivo para comprar "ahora"

---

## Acciones por impacto y esfuerzo

### PRIORIDAD 1 — Impacto alto, esfuerzo bajo (semana 1–2)

#### 1.1 Instalar herramientas de medición
- Configurar **Google Analytics 4** con embudos de conversión (vista producto → carrito → checkout → compra)
- Instalar **Microsoft Clarity** (gratuito): mapas de calor y grabaciones de sesiones
- Identificar en qué paso exacto se van los usuarios

**Por qué:** No se puede mejorar lo que no se mide. Estas herramientas revelarán si el problema está en la página de producto, el carrito, o el checkout.

#### 1.2 Simplificar el checkout
- Reducir a máximo 3 pasos: datos personales → envío → pago
- Habilitar **checkout como invitado** (sin obligar a crear cuenta)
- Autocompletar campos con datos del navegador
- Mostrar **resumen del pedido siempre visible** durante el checkout

**Por qué:** Cada paso adicional en el checkout reduce la conversión ~10–20%. El checkout como invitado puede aumentar conversiones hasta un 35%.

#### 1.3 Agregar prueba social visible
- Mostrar reseñas/calificaciones de compradores en cada página de producto
- Número de unidades vendidas ("Más de 200 enviados")
- Si hay testimonios del club de lectura, ponerlos en la home
- Integrar Google Reviews o reseñas de redes sociales

**Por qué:** El 92% de los compradores online lee reseñas antes de comprar. Sin prueba social, la conversión cae drásticamente.

#### 1.4 Clarificar propuesta de valor en la home
- Titular principal que responda: ¿Por qué comprar acá y no en Mercado Libre?
- Mencionar explícitamente: envío rápido, libros curados, ediciones de calidad, club de lectura
- CTA principal claro: "Ver catálogo" o "Explorar libros" — sin ambigüedad

---

### PRIORIDAD 2 — Impacto alto, esfuerzo medio (semana 2–4)

#### 2.1 Optimización móvil
- Auditar el sitio en Google PageSpeed Insights (mobile)
- Botón "Agregar al carrito" siempre visible sin scroll en mobile
- Imágenes de producto comprimidas (formato WebP)
- Tipografía legible sin zoom (mínimo 16px)
- Carrito accesible con un toque desde cualquier página

**Por qué:** >60% de las compras en Argentina se hacen desde mobile. Una mala UX móvil es la causa #1 de abandono.

#### 2.2 Activar recuperación de carritos abandonados
- Configurar emails automáticos a las 1h, 24h y 72h del abandono
- Asunto directo: "Olvidaste algo en tu carrito 📚"
- Incluir imagen del libro, precio y link directo al carrito
- En el tercer email (72h): ofrecer descuento del 5–10%

**Por qué:** Los emails de carrito abandonado tienen 45% de tasa de apertura y recuperan hasta el 10% de las ventas perdidas.

#### 2.3 Páginas de producto más persuasivas
- Foto de tapa + foto del interior/lomo del libro
- Descripción en 2 niveles: gancho emocional (2 líneas) + sinopsis completa
- Datos clave visibles: autor, editorial, páginas, formato
- Stock limitado si aplica: "Últimas 3 unidades"
- Sección "También te puede gustar" con 3–4 títulos relacionados

#### 2.4 Implementar chat en vivo o bot de consultas
- Integrar WhatsApp Business como canal de consulta rápida
- Botón flotante visible: "¿Tenés dudas? Escribinos"
- Responder consultas sobre envíos y disponibilidad en <2h

**Por qué:** Muchos abandonos ocurren por dudas sin resolver. Un canal de contacto rápido convierte la duda en compra.

---

### PRIORIDAD 3 — Impacto medio, esfuerzo medio (mes 2)

#### 3.1 Optimizar el Club de Lectura como funnel de conversión
- Landing page dedicada con: beneficios claros, precio, qué incluye, testimonios
- CTA de suscripción con formulario en la misma página (sin redirects)
- Ofrecer primer mes con descuento o prueba gratuita
- Comparativa visual: precio club vs. precio individual de los libros

**Por qué:** El club es un producto de ticket recurrente. Una sola conversión vale más que 3 compras puntuales.

#### 3.2 Pop-up de captura de email con incentivo
- Pop-up con exit intent (cuando el usuario va a cerrar la pestaña)
- Oferta: "Suscribite y recibí 10% off en tu primera compra"
- No mostrarlo en las primeras páginas vistas (esperar 30–60 segundos)
- Usar el email para nurturing y recuperación

#### 3.3 Crear urgencia y escasez reales
- Ofertas por tiempo limitado con countdown visible
- Sección "2x1" o "Liquidación" con precio tachado
- "X personas están viendo este libro ahora"
- Envío gratis a partir de cierto monto (mostrar cuánto falta para alcanzarlo)

#### 3.4 Programa de fidelización simple
- Sistema de puntos por compra ("Letras")
- Descuento en la siguiente compra por recomendar a un amigo
- Contenido exclusivo para compradores frecuentes

---

### PRIORIDAD 4 — Mejoras estructurales (mes 2–3)

#### 4.1 SEO y tráfico orgánico de calidad
- Optimizar titles y meta descriptions de páginas de categoría
- Crear contenido (blog/reseñas) que capture búsquedas como "mejores libros de romance 2025"
- Link building desde sitios literarios argentinos

#### 4.2 Velocidad de carga
- Objetivo: <3 segundos en mobile, <2 segundos en desktop
- Comprimir imágenes, usar lazy loading
- Revisar plugins o scripts innecesarios
- Considerar CDN si el hosting es lento

#### 4.3 A/B Testing sistemático
- Testear: colores y texto de botones de CTA
- Testear: orden de elementos en la home
- Testear: imágenes de portada vs. imágenes del libro físico
- Usar Google Optimize o herramienta similar

---

## Roadmap de implementación

| Semana | Acciones |
|--------|----------|
| 1 | GA4 + Clarity, simplificar checkout, añadir prueba social |
| 2 | Optimización mobile, mejorar páginas de producto |
| 3 | Activar emails de carrito abandonado, WhatsApp |
| 4 | Pop-up de captura, urgencia y escasez |
| 5–6 | Landing club de lectura, programa de fidelización |
| 7–8 | A/B tests, SEO técnico, velocidad |

---

## Métricas a monitorear semanalmente

| Métrica | Situación actual | Objetivo |
|---------|-----------------|----------|
| Tasa de conversión | 0.3% | 1% |
| Tasa de abandono de carrito | (medir) | <70% |
| Tasa de apertura emails | (medir) | >35% |
| PageSpeed mobile | (medir) | >70/100 |
| Ticket promedio | (medir) | +20% |
| Tasa de rebote | (medir) | <60% |

---

## Estimación de impacto acumulado

Si el tráfico actual es constante, las mejoras acumuladas pueden estimarse así:

- Checkout simplificado → +30% conversión base
- Prueba social → +20%
- Optimización mobile → +25%
- Recuperación de carritos → +10% sobre ventas perdidas
- Pop-up + email marketing → +15%

**Resultado esperado:** pasar de 0.3% a 0.9–1.1% en 8 semanas con implementación consistente.

---

## Recursos adicionales

- [Guía CRO Shopify](https://www.shopify.com/es/blog/guia-para-mejorar-cro)
- [Tasas de conversión ecommerce 2024](https://www.synolia.com/es/blog/e-commerce/tasa-de-conversion-promedio-ecommerce-2024/)
- [Estrategias CRO avanzadas](https://panamerik.com/optimizacion-de-conversion-en-ecommerce-tecnicas-avanzadas-para-2024/)
- [Oportunidades ecommerce Argentina 2026](https://segundoenfoque.com/oportunidades-ecommerce-argentina-2026)
