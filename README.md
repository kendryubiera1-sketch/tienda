# Aromas Art — Catálogo de Perfumes

Catálogo web de perfumes (masculinos y femeninos) con carrito y pedido por WhatsApp.

## Contenido

- `index.html` — página principal (todo el sitio)
- `blottles/` — imágenes de las botellas (130 fotos)

## Cómo publicar en GitHub Pages

### 1. Crear el repositorio
1. Entra a [github.com](https://github.com) e inicia sesión.
2. Pulsa **New repository**.
3. Nombre sugerido: `aroma-tienda` (o el que prefieras).
4. Déjalo **público** y crea el repositorio (sin README si ya tienes estos archivos).

### 2. Subir los archivos
Sube **todo** el contenido de esta carpeta:

- `index.html`
- carpeta `blottles/` completa
- este `README.md` (opcional)

**Importante:** sube la carpeta `blottles` junto al `index.html`. Si solo subes el index, las imágenes no se verán.

Puedes hacerlo:
- Arrastrando los archivos en la web de GitHub, o
- Con Git:

```bash
git clone https://github.com/TU-USUARIO/aroma-tienda.git
cd aroma-tienda
# Copia aquí index.html y la carpeta blottles/
git add .
git commit -m "Sitio Aromas Art listo"
git push
```

### 3. Activar GitHub Pages
1. En el repositorio ve a **Settings** → **Pages**.
2. En **Source** elige **Deploy from a branch**.
3. Branch: `main` (o `master`) y carpeta `/ (root)`.
4. Guarda. En 1–2 minutos la página estará en:

```
https://TU-USUARIO.github.io/aroma-tienda/
```

### 4. Probar
Abre la URL. Deberías ver el catálogo con las fotos de las botellas. Si alguna imagen no carga, revisa que la carpeta `blottles` esté en el mismo nivel que `index.html`.

## Uso local

Abre `index.html` en el navegador (doble clic) o sirve la carpeta con cualquier servidor estático. Las rutas son relativas (`./blottles/...`), así que funcionan igual en local y en GitHub Pages.

## Notas

- El carrito y los datos de “Mi cuenta” se guardan solo en el navegador del cliente.
- El botón de pedido abre WhatsApp con el detalle del carrito.
- Las imágenes que aún no tienen archivo muestran “Imagen pendiente”.
