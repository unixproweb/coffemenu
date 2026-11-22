# CAFÉ/9 · Menú digital

Menú de cafetería para celular con carrusel, carrito, total automático y pedido por WhatsApp.
Es un solo archivo (`index.html`) con las fotos incluidas, sin dependencias ni build.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub y sube estos archivos (arrastra `index.html`, `README.md` y `.nojekyll`).
2. Ve a **Settings → Pages**.
3. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
4. En 1–2 minutos tendrás tu menú en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Qué editar (dentro de `index.html`, busca estas líneas)
- `const WHATSAPP="524425827867";` → número de WhatsApp (código de país + número, sin + ni espacios).
- `const ITEMS=[ ... ]` → nombre (`n`), descripción (`d`), precio (`p`), categoría (`c`: "frio" o "caliente"), etiqueta (`t`) y color (`col`) de cada bebida.
- `CAFÉ/9` → nombre de tu cafetería (aparece en el logo, el título y el mensaje de WhatsApp).

## Pedido
El botón de WhatsApp se habilita solo cuando hay productos, la mesa está confirmada y se escribió el nombre.
