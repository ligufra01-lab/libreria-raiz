# Librería Independiente Raíz

## 1. Descripción del proyecto

Librería Independiente Raíz es un sitio web estático de carácter académico, diseñado para presentar la identidad de la librería, compartir reseñas de libros, informar sobre eventos y ofrecer un formulario de contacto con validación en el navegador.

El proyecto busca ofrecer una experiencia de navegación sencilla, visualmente atractiva y adaptable a diferentes dispositivos.

## 2. Publicación

- **Repositorio:** https://github.com/ligufra01-lab/libreria-raiz
- **Sitio web:** https://ligufra01-lab.github.io/libreria-raiz/

## 3. Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Git y GitHub
- GitHub Pages

El proyecto es estático y no requiere un backend ni dependencias adicionales para su ejecución básica.

## 4. Estructura del proyecto

```text
libreria-raiz/
├── index.html
├── css/
│   └── main.css
├── js/
│   └── main.js
├── img/
│   └── logo.webp
├── blog/
│   └── index.html
├── eventos/
│   └── index.html
├── contacto/
│   └── index.html
├── ACTA_CIERRE.md
├── RETROSPECTIVA.md
├── .gitignore
└── README.md
```

## 5. Cómo ejecutar el proyecto localmente

1. Clonar el repositorio:

   `git clone https://github.com/ligufra01-lab/libreria-raiz.git`

2. Ingresar a la carpeta:

   `cd libreria-raiz`

3. Abrir el archivo `index.html` en un navegador web.

4. También se puede utilizar Visual Studio Code con la extensión Live Server para visualizar los cambios durante el desarrollo.

5. Antes de comenzar a trabajar, actualizar la versión local:

   `git pull origin main`

## 6. Convención de ramas

Para organizar el desarrollo y evitar modificaciones directas sobre la rama principal, se propone utilizar las siguientes convenciones:

- `main`: versión estable y publicada.
- `feature/nombre-funcionalidad`: desarrollo de nuevas funcionalidades.
- `fix/descripcion-error`: corrección de errores.
- `docs/descripcion`: cambios en documentación.

Los cambios deben integrarse mediante Pull Requests y revisión antes de fusionarse con `main`.

## 7. Conventional Commits

Se utiliza como referencia la convención Conventional Commits para identificar el propósito de cada modificación.

| Prefijo | Descripción |
|---|---|
| `feat:` | Nueva funcionalidad |
| `fix:` | Corrección de errores |
| `docs:` | Cambios en documentación |
| `style:` | Ajustes de formato y presentación |
| `refactor:` | Mejoras internas del código |

Ejemplos:

- `feat: agregar calendario de eventos`
- `fix: corregir enlaces de navegación`
- `docs: actualizar documentación del proyecto`

## 8. Integrantes y responsabilidades del caso

Los siguientes personajes representan los roles definidos en el escenario académico:

- **Laura Restrepo:** coordinación del equipo y seguimiento del sprint.
- **Carlos Méndez:** desarrollo e integración.
- **Sofía Álvarez:** diseño UX/UI y adaptación responsive.
- **Andrés Ramírez:** documentación y apoyo en pruebas.

## 9. Funcionalidades y alcance

El sitio cuenta con página principal, sección de reseñas, eventos y contacto.

El formulario realiza validaciones en el navegador. No dispone de un servicio backend para enviar o almacenar mensajes.

La integración de redes sociales, la versión en inglés y los podcasts se consideran mejoras para futuras versiones.

## 10. Documentos de cierre

- `ACTA_CIERRE.md`: decisiones y registro del cierre académico.
- `RETROSPECTIVA.md`: aprendizajes, oportunidades de mejora y acciones futuras.

## 11. Publicación y mantenimiento

El sitio se publica mediante GitHub Pages desde el repositorio. Después de integrar cambios en la rama principal, se debe verificar el estado del despliegue en GitHub Actions o en la sección de GitHub Pages y comprobar la navegación en la URL pública.
