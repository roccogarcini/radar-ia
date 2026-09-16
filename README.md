# RADAR IA

Periódico ejecutivo de IA sin base de datos.

## Archivos
- `index.html`: portada, archivo, temas y buscador.
- `radar.json`: histórico completo. Cada día se agrega una nueva edición al inicio de `editions`.

## Publicar gratis
### Vercel
1. Crea un repositorio en GitHub y sube estos archivos.
2. Importa el repositorio en Vercel.
3. Framework preset: **Other**. No requiere build command.
4. Cada cambio en GitHub se publica automáticamente.

### GitHub Pages
También funciona como sitio estático en GitHub Pages.

## Actualización diaria
Añade un objeto nuevo al principio de `editions` en `radar.json`. Las ediciones anteriores permanecen intactas y aparecen automáticamente en ARCHIVO, TEMAS y BUSCAR.

No requiere Supabase ni otra base de datos para esta V1.
