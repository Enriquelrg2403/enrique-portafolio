PORTAFOLIO ENRIQUE LA ROSA — NUEVA WEB ONLINE EDITABLE
===================================================

ESTA VERSIÓN YA ESTÁ PREPARADA PARA:
  A) Publicarse gratis en Netlify con dirección pública .netlify.app.
  B) Editarse desde Pages CMS en línea, sin escribir código.
  C) Guardar los cambios en GitHub, que avisa a Netlify para actualizar la web.

NECESITAS CREAR 3 CUENTAS (o iniciar sesión con las que ya tengas)
  - GitHub: https://github.com
  - Netlify: https://app.netlify.com
  - Pages CMS: https://app.pagescms.org (acceso con GitHub)

PASO 1 — CREAR EL REPOSITORIO DE GITHUB
1. Entra en https://github.com/new
2. Nombre sugerido: enrique-portafolio
3. Configura la visibilidad como Public.
4. Selecciona Create repository (puedes inicializar con un README).
5. Entra al repositorio y pulsa Add file > Upload files.
6. Descomprime el ZIP y arrastra TODOS LOS ARCHIVOS DE SU INTERIOR a GitHub:
       index.html, .pages.yml, netlify.toml, media/, content/, README_PUBLICAR.txt
   ¡IMPORTANTE! Deben quedar en la RAÍZ del repositorio, no dentro de otra carpeta.
   La carpeta media contiene las imágenes iniciales y content los textos/proyectos.
7. Confirma con Commit changes.

PASO 2 — PUBLICAR EN NETLIFY (gratis)
1. Abre https://app.netlify.com y crea una cuenta gratuita.
2. En tu dashboard pulsa Add new project > Import an existing project.
3. Elige GitHub y autoriza acceso a tu repositorio enrique-portafolio.
4. Selecciona la rama main. En las opciones de publicación usa:
       Build command: VACÍO (no necesita compilación)
       Publish directory: .  (un punto = raíz del repositorio)
   Si Netlify detecta el archivo netlify.toml, dejará esa carpeta como publicación.
5. Pulsa Publish / Deploy.
6. Si Netlify crea el sitio como privado, cambia su visibilidad a pública desde
   el panel de Netlify; el plan gratuito puede crear proyectos privados por defecto.
7. Ve a Site configuration > Domain management / Production domains para ver
   tu dirección pública, normalmente https://NOMBRE.netlify.app.
   Puedes renombrar tu sitio a un nombre disponible que te guste.

PASO 3 — CONECTAR EL PANEL DE EDICIÓN ONLINE
1. Abre https://app.pagescms.org/
2. Pulsa Sign in with GitHub y autoriza la app de Pages CMS.
   Por seguridad, es preferible dar permiso solo al repositorio enrique-portafolio.
3. Selecciona el repositorio enrique-portafolio y la rama main.
4. Si el archivo .pages.yml está bien subido, verás estos dos menús:
       Mi perfil y contacto
       Mis proyectos y fotografías
5. Edita un texto en Mi perfil y contacto, guarda/publica.
6. Pages CMS guardará la edición como cambio en GitHub.
7. Netlify detectará el cambio y publicará automáticamente la nueva versión.
8. Comprueba el cambio visitando tu dirección .netlify.app.

TUS PRIMERAS ACTUALIZACIONES RECOMENDADAS
- En Mi perfil y contacto: agrega correo profesional y WhatsApp para activar el contacto.
- En Mis proyectos y fotografías: sube portadas que realmente te pertenecen.
- Añade enlaces de YouTube/Vimeo para los videos grandes, en lugar de subir MP4.
- Desmarca "Es una portada de muestra" cuando agregues imágenes propias.
- Publica una selección pequeña pero excelente, con proyectos para marcas y empresas.

ARCHIVOS
- index.html           Página principal, adaptada a escritorio y móvil.
- content/perfil.json  Nombre, presentación, servicios y contacto.
- content/proyectos.json  Proyectos en video y fotografía.
- media/               Carpeta para fotos y portadas (al comienzo son ilustrativas).
- .pages.yml           Configuración del panel CMS (archivo oculto con punto).
- netlify.toml         Configuración de publicación de Netlify.

CONSIDERACIONES
- Aún no está alojada en internet: eso ocurre al hacer los pasos de Netlify.
- El editor online NO es un archivo editor.html. Es https://app.pagescms.org.
- GitHub almacena el código en repositorio público: no subas claves, contraseñas
  ni archivos confidenciales.
- El formulario de contacto prepara un mensaje para WhatsApp o correo, no guarda
  ni envía información directamente a un servidor.
- Las primeras portadas son imágenes DE MUESTRA, no obras tuyas; reemplázalas.
- El portafolio inicial conserva enlaces a tu página de Wix para los trabajos.
- Netlify Free tiene límite de créditos mensuales. Un portafolio ligero suele ser
  apropiado, pero revisa el consumo si recibes muchas visitas o actualizas seguido.
- Este ZIP abre la versión de respaldo al hacer doble clic en index.html; publicado
  como sitio web lee content/perfil.json y content/proyectos.json automáticamente.

DOCUMENTACIÓN OFICIAL
  https://docs.netlify.com/start/quickstarts/deploy-from-repository/
  https://pagescms.org/docs/quick-start/
  https://www.netlify.com/pricing/
