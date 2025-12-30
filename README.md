# Documento Detallado de Diseño (DDD)
*Una pequeña aclaración es que en mi ID tengo mi otro github añadido y no se por qué pero se creó el proyecto con mis dos usuarios así que el usuario garciiss soy yo, Pablo García Blanco desde mi github personal.

## Descripción del trabajo
El trabajo consiste en realizar una página web con distintas vistas como una página principal, una página de contacto, una página de información personal, una págima del curso que estoy estudiando y de que se trata con sus respectivas asignaturas así como también
información detallada de la asignatura de Fundamentos de Ingeniería Informática. Una vez acabado habrá que publicarlo en el entorno de GitHub pages para hacerlo público a todo el mundo. Mientras tanto cualquier cambio que hagamos en el repositorio se tendrá que comentar y subir al repositorio de GitHub para ver como ha sido cada cambio y cada actualización.
Todo este trabajo será puramente visual lo que quiere decir que no tiene ningun back-end incorporado ya que así se ha pedido.
No se podría especificar que tipo de arquitectura tiene este proyecto pero diría que sigue una arquitectura monolítica ya que es una única unidad e indivisible porque si quitas alguna página el resto podría dar algún fallo.
Este proyecto es fácil escalable porque como es básico y no tiene ni back-end, front-end es muy básico no hay manejo de excepciones ni ciberseguridad pues podría mejorar en gran cantidad.
El flujo de funcionamiento es básicamente que el cliente interactúe con el front-end y visite todo el contenido sin realizar ninguna petición. Lo único que valida por el lado del cliente es un formulario de contacto realizado mediante Javascript.


Principales funcionalidades implementadas:
- Banner con imagen de fondo y fallback `noscript`.
- Formulario de contacto con validación nativa y simulación de envío.
- Embed de PDF para el CV y enlaces de descarga.
- Grid responsivo para las fotos.
- Consideraciones de accesibilidad (atributos ARIA, roles, `aria-live`).

## Problemas durante el desarrollo
Llevaba mucho tiempo sin programar por lo que he tenido que ayudarme de otros proyectos que hice en el pasado para refrescar mi conocimiento. 
Una vez después de revisar los distintos proyectos fue muy asequible realizar este proyecto. 
Otros problemas que han surgido es sobre todo con los estilos ya que a veces se hace un poco complicado como centrar una imagen por ejemplo o encontrar la paleta de colores ideal para el entorno web entero.
También durante la publicación en el entorno de Github Pages he tenido que documentarme un poco ya que nunca lo había hecho y solo había trabajado en servidores locales como montar uno en python o el propio localhost.

## Conclusiones
- Separar contenido, estilos y recursos facilita la mantenibilidad.
- Validación nativa + mensajes accesibles mejora la experiencia del formulario.
- Comprobar rutas relativas desde cada archivo HTML reduce errores al mover ficheros.
- Embebidos (PDF, multimedia) requieren fallback y comprobación cross-browser.


## Instalación y uso local
1. Clonar el repositorio.
2. Abrir el proyecto en el editor o servirlo localmente. Ejemplo con Python (PowerShell / CMD en Windows):
   - `python -m http.server 8000`
   - Abrir `http://localhost:8000/` en el navegador.
3. La otra opción es usar el siguiente link en el navegador: https://pablo-garcia-blanco.github.io/Web_Pablo_Garcia_Blanco/docs/index.html

## Estructura del repositorio.
- `idea` - Contiene las configuraciones básicas del proyecto proporcionado por el ID del Intellij.
- `docs/` - Contiene las carpetas del css, la página principal, la carpeta public, donde se encuentra el resto de las páginas webs, imagenes, donde se encuentran almacenadas todas las imágenes y por último el index.html que corresponde a la página principal.
- `public/` - Contiene el resto de subpáginas web. (`about.html`, `net.html`...)  
- `CSS/` — hojas de estilo (`estilosIndex.css`, `estilosAbout.css`, ...).  
- `imagenes/` — imágenes.  
- `DOC/` — documentos (CV.pdf).  
- `.gitignore` — reglas para Git.  
- `README.md` — este documento.
  

## Tecnologías
- HTML5, CSS3, JavaScript (vanilla).
- ID utilizado: Intellij ques un ID de pago que con el correo de la universidad sale gratis siempre y es muy bueno.
- Control de versiones: GitHub.  
- Recomendado: navegador moderno para pruebas (Chromium/Firefox/Edge) y también he utilizado como método de pruebas el entorno que emplea el ID de IntelliJ.

## Contacto
Autor: Pablo García Blanco


