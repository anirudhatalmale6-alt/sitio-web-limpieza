# Sitio web informativo — Empresa de limpieza (maqueta v1)

Maqueta de diseño para el sitio informativo. Contenido de ejemplo: los textos, fotos,
nombre, teléfono, correo y dirección son de relleno y se sustituyen por los definitivos.

## Qué incluye esta maqueta

- **Inicio** — titular, propuesta de valor, dos llamadas a la acción y franja de confianza (4 datos).
- **Servicios** — 6 tarjetas con icono, descripción y detalles.
- **Cómo trabajamos** — 3 pasos + espacio reservado para foto de equipo.
- **Contacto y ubicación** — formulario, teléfono con clic para llamar, correo, horario y mapa.
- **Pie de página** — datos de contacto, horario y enlaces legales.
- **Móvil** — menú desplegable y barra fija inferior con "Llamar" y "Presupuesto".

## Decisiones de diseño

- Paleta neutra: fondo hueso `#F5F3EE`, texto `#14161A`, un único acento verde `#1F5C4D`.
- Tipografía: **Fraunces** (titulares) + **Hanken Grotesk** (texto). Ambas autoalojadas
  (`assets/fonts/`), sin llamadas a Google — más rápido y sin problemas de RGPD.
- Sin librerías externas: 0 dependencias, 0 JavaScript de terceros. Un solo CSS y ~20 líneas de JS.
- Animación de entrada por secciones con `IntersectionObserver` (se desactiva si el
  visitante tiene "reducir movimiento" activado en su sistema).

## Estructura

```
index.html
assets/
  css/style.css
  fonts/          Fraunces + Hanken Grotesk (woff2, subconjuntos latin)
  img/mapa.jpg    imagen provisional del mapa
```

## Cómo verlo

Abrir `index.html` en cualquier navegador. No necesita servidor ni instalación.

## Siguiente paso

Una vez aprobada la estética, se monta como tema propio de WordPress para que los textos,
imágenes, servicios, teléfono y dirección se editen desde el panel de administración.
