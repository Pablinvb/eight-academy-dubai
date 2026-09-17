# Rumbo a Dubái — Eight Academy

Sitio informativo para familias sobre la participación de Eight Academy en la
**Final Global de iWISE**, Dubái, del 8 al 12 de marzo de 2027.

**Publicado en:** https://pablinvb.github.io/eight-academy-dubai/

---

## Qué contiene

- Presentación de iWISE, sus aliados y el medallero
- Carta oficial de invitación dirigida a la institución
- Comparación de las tres finales globales de 2027 (Dubái, Boston, Londres)
- Programa diario de los seis días
- Beneficios que aporta el colegio: mentoría, pitch, respaldo académico y kit de viaje
- Tres rutas aéreas cotizadas, con globo terráqueo interactivo por ruta
- Planes de pago que se recalculan según la ruta seleccionada

## Cómo está construido

Un único `index.html` sin dependencias de compilación. Todas las imágenes van
incrustadas como *data URI* y los globos terráqueos se dibujan en `<canvas>`
con geometría de costas simplificada, sin librerías externas.

Lo único que se carga de fuera son las tipografías de Google Fonts.

| Archivo | Para qué |
| --- | --- |
| `index.html` | El sitio completo |
| `og.jpg` | Previsualización al compartir el enlace |
| `favicon.png` | Icono de pestaña |

## Publicación

GitHub Pages sirve la rama `main` desde la raíz. Cada `push` actualiza el sitio
en aproximadamente un minuto.

## Nota sobre las cifras

Los valores de esta página son **referenciales**. La ruta aérea todavía no está
adjudicada y el seguro médico de viaje no está incluido en los montos
mostrados. Antes de comunicar un precio en firme a las familias hay que cerrar
ambos puntos.
