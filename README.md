# ERPiA Agente

> ERP + IA + Agente para autónomos y micropymes en España.
> Verifactu legal RD 1007/2023. Gratis.

**Web:** https://erpiagent.es
**App:** https://erpia.es
**Instagram:** [@erpia_agent](https://www.instagram.com/erpia_agent)

---

## Qué es ERPiA Agente

ERPiA es el primer ERP español con un **agente de IA** que ejecuta órdenes
por voz y por Telegram. Le hablas como a un compañero ("Cobré 350€ del
cliente Pérez", "Hazme factura de 200€ al taller Gómez") y trabaja sobre
tu propio ERP: factura, cobra, contabiliza, te avisa.

Pensado para autónomos de oficio (fontaneros, electricistas, albañiles,
carpinteros, pintores), TPV de hostelería (bares, restaurantes, cafeterías)
y TPV de comercio (tiendas, papelerías, ferreterías).

---

## Características principales

- **Agente de IA** que ejecuta órdenes por voz y por Telegram
- **Verifactu RD 1007/2023** integrado (obligatorio en España desde julio 2027 para autónomos en estimación directa)
- **Contabilidad legal española** completa: IVA, IRPF, modelos 130, 303, 347, 390, 100, 111, 115
- **OCR** de tickets, facturas de proveedor, DNI y cartas de hostelería
- **Portal del gestor** en solo lectura sin login
- **TPV de hostelería** con plano de mesas, comandas y arqueo
- **TPV de comercio** con código de barras, stock y tallas
- **Multi-usuario** sin coste adicional
- **Importador** desde Factusol, Excel y CSV
- **PWA** instalable sin Play Store ni App Store
- **Conciliación bancaria** y links de pago Stripe
- **Firma digital** de presupuestos por el cliente

---

## Planes

### Gratis · 0 € · sin tarjeta · sin permanencia
- Facturas y presupuestos ilimitados
- Verifactu legal
- Clientes, catálogo de artículos y servicios
- Copiloto IA por chat
- PWA instalable
- Firma digital de presupuestos
- Exportación PDF y Facturae XML

### Plus · 5,90 € / mes (o 59 € / año)
Todo lo de Gratis +
- Agente en Telegram
- OCR completo (tickets, facturas, DNI, cartas)
- Portal del gestor
- Multi-usuario
- Importador desde Factusol / Excel
- Contabilidad completa (IVA / IRPF / trimestres)
- TPV Comercio y Hostelería
- Cobros + conciliación bancaria
- Stock, Compras, Proyectos, Agenda, CRM
- Facturas recurrentes y links de pago Stripe

**Cupones:** ERPIA1MES, ERPIA2MES, ERPIA3MES (1, 2 o 3 meses gratis).

---

## Herramientas gratuitas

| Herramienta | Para qué |
|---|---|
| [Calculadora cuota autónomo 2026](https://erpiagent.es/calculadora-cuota-autonomo) | Cuánto pagas a la SS según rendimientos. 15 tramos oficiales RDL 16/2025 con MEI 0,9%. |
| [Guía del autónomo 2027](https://erpiagent.es/guia-autonomo-2027) | Alta, IRPF, IVA, modelos, Verifactu obligatorio julio 2027 y todo el calendario fiscal. |
| [Cómo hacerse autónomo sin miedo](https://erpiagent.es/como-hacerse-autonomo) | Los 7 miedos típicos del nuevo autónomo desmontados + plan de los primeros 90 días. |
| [Ayudas y subvenciones por CCAA 2026](https://erpiagent.es/ayudas-subvenciones-autonomos-ccaa) | ~180 programas activos: cuota cero, Kit Digital, ENISA, ICO y los regionales. |

---

## Stack técnico

- **Frontend:** React 19 + Vite + TypeScript + Tailwind CSS
- **Backend:** Supabase (PostgreSQL + Auth + Storage + RLS + Edge Functions)
- **IA:** Gemini 2.5 Flash (texto, audio, imagen, OCR)
- **Bot:** Telegram Bot API (Edge Function webhook)
- **Pagos:** Stripe
- **PDF:** jsPDF + jspdf-autotable
- **Facturae:** XML RD 1007/2023 conforme AEAT
- **Firma digital:** node-forge (.p12/.pfx) + canvas
- **Deploy:** Vercel

---

## Quién hay detrás

**Jose Miguel García Rodríguez** — técnico comercial y consultor IT con más
de 25 años de experiencia en sistemas, SAP, TPV y digitalización de pymes.
Atención remota a toda España; presencial en Andalucía.

- Email: hola@erpia.es
- Teléfono: +34 634 02 56 37
- [Sobre mí](https://erpiagent.es/sobre-mi)

---

## Licencia

El código de la aplicación es propietario. Este repositorio contiene
únicamente material de marketing, capturas y documentación pública del
producto. Marca registrada **ERPiA Agente® · 2026**.
