# Librería Independiente Raíz

Sitio estático académico para presentar la librería, reseñas de libros, agenda de actividades y formulario de contacto con validación en el navegador.

## Publicación
- Repositorio: https://github.com/ligufra01-lab/libreria-raiz
- GitHub Pages: https://ligufra01-lab.github.io/libreria-raiz/

Verificar la URL y el resultado del despliegue en **Settings > Pages** y **Actions** después de fusionar cambios a `main`.

## Tecnologías
HTML5, CSS3, JavaScript, Git, GitHub y GitHub Pages. No requiere dependencias ni backend para ejecutarse como prototipo.

## Estructura
```text
libreria-raiz/
├── index.html
├── README.md
├── .gitignore
├── css/main.css
├── js/main.js
├── img/logo.webp
├── blog/index.html
├── eventos/index.html
└── contacto/index.html
```

## Ejecutar en local
1. `git clone https://github.com/ligufra01-lab/libreria-raiz.git`
2. `cd libreria-raiz`
3. Abrir `index.html` en el navegador o usar Live Server en Visual Studio Code.

## Rutas
La página principal usa `css/main.css`, `js/main.js` e `img/logo.webp`. Las páginas internas usan rutas `../css/main.css`, `../js/main.js` y `../img/logo.webp`, compatibles con la publicación dentro de `/libreria-raiz/` en GitHub Pages.

## Funcionalidades
- Navegación adaptable a móviles.
- Blog con búsqueda por título, autor y palabras clave.
- Agenda de actividades.
- Formulario con validación de nombre, correo, asunto, mensaje y confirmación.

**Limitaciones:** el formulario no envía ni almacena mensajes; se debe conectar un servicio externo o backend para recibirlos. Las reseñas y las fechas de eventos son contenido de ejemplo y deben ser revisadas por el cliente antes de anunciarse como información real.

## GitHub Flow
1. `git switch main` y `git pull origin main`.
2. Crear una rama por tarea, por ejemplo `git switch -c feature/blog-resenas`.
3. Hacer cambios pequeños y probar localmente.
4. Publicar la rama con `git push -u origin feature/blog-resenas`.
5. Abrir Pull Request hacia `main`, solicitar revisión y verificar rutas, vista móvil y consola.
6. Fusionar solo después de la revisión y eliminar la rama.

Coordinar previamente los archivos que se modificarán para evitar que dos integrantes editen simultáneamente el mismo bloque de estilos.

## Conventional Commits
Formato: `tipo(alcance): descripción breve`
- `feat(blog): agrega reseñas`
- `feat(eventos): crea agenda`
- `feat(contacto): incorpora formulario`
- `fix(navegacion): corrige rutas internas`
- `style(web): ajusta diseño adaptable`
- `docs(readme): documenta instalación`
- `refactor(js): organiza validaciones`

Tipos: `feat`, `fix`, `docs`, `style`, `refactor`.

## Verificación antes del despliegue
- [ ] `index.html` está en la raíz.
- [ ] Navegación abre las cuatro páginas.
- [ ] Logo, CSS y JavaScript cargan sin 404.
- [ ] Menú móvil funciona.
- [ ] Búsqueda filtra reseñas.
- [ ] Formulario valida entradas.
- [ ] Se informa que el formulario no envía datos.
- [ ] Agenda de muestra se identifica como contenido ilustrativo.
- [ ] Actions y URL pública se revisan tras la fusión.

## Equipo
- Santiago Escobar Vasco
- Juan José Gutiérrez Franco

Proyecto académico — Metodología de Software, Politécnico Internacional.
