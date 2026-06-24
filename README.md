# FAC IA — Facturación Electrónica Inteligente

Plataforma SaaS para la emisión de Comprobantes Fiscales Electrónicos (e-CF) en la República Dominicana.

## Stack
- Frontend: HTML/CSS/JS puro + Inter font
- IA: Puter.js (Claude Sonnet 4.5) — sin costo para el desarrollador
- Almacenamiento: localStorage + Puter KV Store
- Hosting: Puter.site / GitHub Pages

## Características
- Landing page con planes de suscripción
- Dashboard de métricas de facturación
- Formulario de nueva factura con validación IA
- Lista de facturas con filtros y exportación CSV
- Gestión de clientes
- Configuración de empresa, DGII y SAP B1
- Autenticación via Puter o usuario/contraseña local
- 100% DGII Compliant

## Deploy
Desplegado en: https://fac-ia.puter.site

## Uso
1. Abrir la URL
2. Iniciar sesión con cuenta Puter para activar la IA gratuita
3. Crear facturas y validar con Claude AI antes de emitir

## Integración Puter.js
- `puter.ai.chat()` → Validación inteligente con Claude Sonnet 4.5
- `puter.net.fetch()` → Llamadas a SAP B1 sin restricciones CORS
- `puter.kv` → Almacenamiento de configuraciones en la nube

## Licencia
Propietario — Domingo Guerra © 2026
