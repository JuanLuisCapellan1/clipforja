# Sitio web de ClipForja (gratis)

TikTok for Developers exige un sitio con Términos y Privacidad visibles sin abrir menús, y una URL de retorno para el login. Estas 4 páginas cubren eso y se publican gratis en GitHub Pages.

| Archivo | URL final (ejemplo) | Para qué |
|---|---|---|
| `index.html` | `https://TU_USUARIO.github.io/clipforja/` | Website URL |
| `terminos.html` | `https://TU_USUARIO.github.io/clipforja/terminos.html` | Terms of Service URL |
| `privacidad.html` | `https://TU_USUARIO.github.io/clipforja/privacidad.html` | Privacy Policy URL |
| `tiktok/callback.html` | `https://TU_USUARIO.github.io/clipforja/tiktok/callback.html` | Redirect URI de Login Kit |

## Antes de publicar

Reemplaza `TU_CORREO` en las tres páginas por un correo de contacto real (puede ser uno nuevo, por ejemplo `clipforja.contacto@gmail.com`).

## Publicar en GitHub Pages

1. Crea un repositorio **público** llamado `clipforja` en github.com.
2. Sube el contenido de esta carpeta `web/` a la raíz del repositorio (index.html debe quedar en la raíz).
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. En 1–2 minutos queda en `https://TU_USUARIO.github.io/clipforja/`.

## Verificar las URLs en TikTok

Para apps creadas después del 9 de septiembre de 2024, TikTok pide verificar las URLs de Términos, Privacidad y Website:

1. En el campo de la URL, haz clic en **Verify** y elige verificar por **URL prefix**: `https://TU_USUARIO.github.io/clipforja/`.
2. TikTok te da un archivo de firma (`tiktokXXXX.txt`). Descárgalo y súbelo a la raíz del repositorio, junto a `index.html`.
3. Espera a que GitHub Pages lo publique y pulsa **Verify** en TikTok.

Con un prefijo verificado quedan cubiertas las cuatro URLs, porque todas cuelgan de él.
