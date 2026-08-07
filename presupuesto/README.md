# Presupuesto — Sitio web Logística Sanitaria LS

- **`presupuesto-web-ls.pdf`** — documento final (2 páginas, A4) listo para enviar o imprimir.
- **`presupuesto-web-ls.html`** — fuente editable del PDF.

## Resumen comercial

| Concepto | Precio |
|---|---|
| Plan Básico (one page, hasta 20 productos, 2 revisiones, soporte 15 días) | **USD 400** |
| Plan Completo (5 secciones, 60 productos con filtros, Google Empresa/Analytics, 4 revisiones, soporte 30 días) | **USD 500** |
| Mantenimiento mensual opcional (hasta 30 actualizaciones de productos) | **USD 50 / mes** |

Pago: 50 % de anticipo y 50 % contra entrega. Validez de la oferta: 15 días.

**Dominio, hosting y correo corporativo no están incluidos** y quedan a cargo del cliente: se contratan a su
nombre y no nos hacemos cargo de su funcionamiento, caídas, renovaciones ni vencimientos (punto 4 y
cláusula 3 del documento).

## Antes de enviarlo

Editar en el HTML el número de presupuesto y la fecha (bloque `.doc-meta`).

## Regenerar el PDF

```bash
chromium --headless --no-pdf-header-footer \
  --print-to-pdf=presupuesto-web-ls.pdf presupuesto-web-ls.html
```
