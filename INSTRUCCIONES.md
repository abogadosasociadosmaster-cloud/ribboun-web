# Ribboun · Guía de publicación y uso

## 1. Publicar la web en GitHub Pages (gratis, una sola vez)

1. Crear una cuenta en https://github.com (recomendado: una cuenta propia de la marca, ej. usuario "ribboun").
2. Crear un repositorio nuevo → nombre sugerido: `ribboun-web` → marcarlo **Public**.
3. Subir TODOS los archivos de esta carpeta (index.html, admin.html, products.json y la carpeta img/): botón **"Add file → Upload files"** → arrastrar los archivos → **Commit changes**.
4. Ir a **Settings → Pages** → en "Branch" elegir `main` y carpeta `/ (root)` → **Save**.
5. En 1-2 minutos la web queda online en: `https://TUUSUARIO.github.io/ribboun-web/`

## 2. Colocar el link en Instagram

Instagram → Editar perfil → campo "Sitio web" → pegar la dirección del paso anterior.

## 3. Administrar productos (las 2 administradoras)

- Entrar a `https://TUUSUARIO.github.io/ribboun-web/admin.html`
- Correos autorizados: `barrionuevopilar0@gmail.com` y `abogadosasociadosmaster@gmail.com`
- Contraseña inicial: `ribboun2026` → **cambiarla** editando la línea `const CLAVE = "ribboun2026"` en admin.html.
- Desde el panel se puede: agregar/editar/eliminar productos, subir hasta 4 fotos por producto, cambiar precio, stock, descuento por transferencia, cuotas, WhatsApp e Instagram.

### Publicación automática desde el panel (recomendado)
1. En GitHub: foto de perfil → **Settings → Developer settings → Fine-grained personal access tokens → Generate new token**.
2. Nombre: "panel ribboun" · Repository access: solo `ribboun-web` · Permissions → **Contents: Read and write**.
3. Copiar el token en el panel (sección "Configuración de GitHub") junto con usuario y repositorio → Guardar.
4. A partir de ahí, el botón **"Publicar en la web"** sube los cambios solo. Cada administradora lo configura una vez en su navegador/celular.

### Alternativa manual (sin token)
Botón **"Descargar products.json"** → en GitHub abrir `products.json` → ícono de lápiz o "Upload files" → reemplazar → Commit.

## 4. Fotos de productos

Las imágenes actuales son ilustraciones de muestra. Reemplazarlas subiendo fotos reales desde el panel (se comprimen solas). Ideal: fotos cuadradas, fondo claro y buena luz, estilo catálogo Apple.

## 5. Datos pendientes de completar

- Número de WhatsApp de ventas (panel → Configuración): si se completa, el botón de compra abre WhatsApp con el mensaje armado; si queda vacío, la compra se dirige al Instagram @ribboun.
- Cambiar la contraseña del panel (ver punto 3).
