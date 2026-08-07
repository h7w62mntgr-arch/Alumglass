# Demo — Logística Sanitaria LS (Barraca · Ferretería · Sanitaria)

Sitio de demostración para la barraca sanitaria **LS** (Pan de Azúcar 2542 esq. 8 de Octubre, Unión, Montevideo).

## Cómo verlo

Abrí `index.html` en cualquier navegador. **No requiere internet ni servidor**: Bootstrap, los iconos y la
tipografía están servidos desde `assets/`.

## Qué incluye

- Diseño sobrio, fondo blanco, paleta azul institucional (azul/negro del logo LS).
- **Bootstrap 5.3.3** + **Bootstrap Icons 1.11.3** (`bi bi-*`), todo local.
- Responsive verificado sin desborde horizontal en 390 px, 768 px y 1440 px.
- Secciones: barra de datos, hero, rubros, productos, servicios, nosotros, contacto y pie.
- Botón flotante de WhatsApp, menú móvil, animación de aparición al hacer scroll y formulario de
  presupuesto (de demostración: no envía, sólo muestra el aviso de confirmación).

## Datos a reemplazar antes de publicar

| Dónde | Qué cambiar |
|---|---|
| Franja superior amarilla | Quitar el bloque `.demo-note` |
| `https://wa.me/59800000000` | Número real de WhatsApp |
| `tel:+59800000000` / `2000 0000` / `099 000 000` | Teléfonos reales |
| `ventas@ejemplo.com.uy` | Correo real |
| Horarios | Horario real del local |
| `.hero-panel .ph` y `.prod .img` | Fotos reales (local, mostrador, productos) |
| `.map-box` | Iframe de Google Maps con la ubicación |
| Formulario | Conectarlo a un servicio de envío de correo |

## Estructura

```
barraca-sanitaria-ls/
├── index.html
└── assets/
    ├── css/   bootstrap.min.css · bootstrap-icons.min.css
    ├── js/    bootstrap.bundle.min.js
    └── fonts/ bootstrap-icons.woff2/woff · inter-latin-*.woff2
```

El presupuesto comercial (planes y términos) está en [`../presupuesto/`](../presupuesto/).
