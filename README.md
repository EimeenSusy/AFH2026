# Árbol Genealógico — Visor Deep Zoom

Este paquete contiene todo lo necesario para publicar tu árbol genealógico
como una imagen con zoom fluido, visible desde cualquier navegador (celular
o computadora), sin necesidad de descargar el archivo pesado.

## Contenido

- `index.html` — la página del visor (usa la librería OpenSeadragon vía CDN)
- `img.dzi` — el archivo descriptor de Deep Zoom
- `img_files/` — carpeta con los ~18,000 tiles (mosaicos) en 16 niveles de zoom

(Los nombres son genéricos a propósito, para no anunciar el contenido del
repositorio con solo mirar la lista de archivos.)

## Cómo publicarlo en GitHub Pages, manteniéndolo "no listado"

1. Crea un repositorio nuevo en GitHub con un **nombre neutro y no obvio**
   (evita "arbol", "genealogico", "hernandez", el apellido de la familia,
   etc.). Por ejemplo algo como `proyecto-8x2kq` o `archivo-personal-04`.
2. Sube estos 3 elementos (`index.html`, `img.dzi`, `img_files/`) a la
   raíz del repositorio, conservando la estructura de carpetas tal cual.
3. En el repositorio, ve a **Settings → Pages**.
4. En "Source", selecciona la rama (por ejemplo `main`) y la carpeta `/root`.
5. Guarda. GitHub te dará una URL como:
   `https://TU-USUARIO.github.io/TU-REPOSITORIO/`
6. Espera 1-2 minutos y prueba el link.

## Para que se mantenga fuera del radar

- **No lo enlaces desde ningún lado público**: no lo pongas en tu perfil de
  GitHub, no lo marques como "pinned repo", no lo compartas en redes sociales.
- **Comparte la URL directamente** por WhatsApp, email o mensaje privado
  solo a quien quieras que lo vea.
- Ten presente que esto es "no listado", no "protegido con contraseña":
  cualquiera con el link puede entrar, y cualquiera a quien se lo mandes
  podría reenviarlo. Si en algún momento quieres una barrera real de acceso
  (verificación por correo o cuenta), avísame y lo configuramos.

## Notas técnicas

- No necesitas convertir nada más ni instalar nada: los tiles ya están
  generados y son estáticos, GitHub Pages solo los sirve como archivos.
- El repositorio pesará ~94 MB (muchos archivos pequeños), lo cual es normal
  para este formato y no representa ningún problema para GitHub.
- Si en el futuro reemplazas la foto original, tendrás que regenerar los
  tiles y el `.dzi` de nuevo (avísame y te los regenero).
