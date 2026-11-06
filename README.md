# Blog Tech World

Blog personal de noticias y novedades del mundo tecnológico. Proyecto de maquetación web en HTML5 y CSS3 con diseño responsive.

## 📋 Descripción

Sitio web estático de blog tecnológico con diseño moderno y responsive. Incluye páginas de inicio, listado de artículos, posts individuales y perfil de autor. El proyecto se enfoca en compartir las últimas novedades del mundo tech a través de una interfaz limpia y profesional.

## 🏗️ Estructura del Proyecto

```
Proyecto-maquetacion-web/
├── assets/
│   └── img/                 # Imágenes del proyecto
│       ├── Cover.png
│       ├── Logo-negro.png
│       ├── main-news-img.png
│       ├── post-1.png
│       ├── post-2.png
│       ├── post-3.png
│       ├── profile-pic.jpg
│       ├── 013-newsletter.png
│       └── 006-like.png
├── css/
│   ├── font/
│   │   └── flaticon.css     # Iconos de redes sociales
│   └── main.css             # Estilos principales del proyecto
├── index.html               # Página de inicio
├── blogs.html               # Listado de artículos del blog
├── blog.html                # Página individual de artículo
├── perfil.html              # Página de perfil del autor
└── README.md                # Documentación del proyecto
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica del sitio web
- **CSS3**: Estilos y diseño responsive
- **Google Fonts**: Roboto y Roboto Mono para tipografía
- **Flaticon**: Iconos de redes sociales

## 🎨 Características de Diseño

### Paleta de Colores
- **Verde principal**: `#47cfac` - Utilizado en botones, bordes y acentos
- **Gris claro**: `#E6E9ED` - Fondos secundarios y separadores
- **Blanco**: `#ffffff` - Fondos principales
- **Negro**: `#000000` - Texto y elementos oscuros

### Tipografía
- **Roboto**: Fuente principal para texto general
- **Roboto Mono**: Fuente monoespaciada para títulos y elementos destacados
- **Google Fonts**: Importadas desde CDN

### Iconos
- Facebook, Twitter, WhatsApp, LinkedIn, Instagram (Flaticon)
- Newsletter y Like (Imágenes personalizadas)

## 📱 Diseño Responsive

El proyecto incluye tres breakpoints para adaptarse a diferentes dispositivos:

- **Mobile**: `< 767px` - Diseño optimizado para smartphones
- **Tablet**: `768px - 1023px` - Adaptación para tablets
- **Desktop**: `> 1024px` - Diseño completo para computadoras

### Características Responsive
- Menú de navegación adaptativo
- Reorganización de elementos en columnas
- Ajuste de tamaños de texto y espaciados
- Flexbox y Grid para layouts flexibles

## 🚀 Cómo Usar

### Instalación
1. Clona el repositorio:
```bash
git clone https://github.com/IanPortuguez/tech-blog-maquetacion.git
```

2. Navega al directorio del proyecto:
```bash
cd tech-blog-maquetacion
```

### Visualización
Simplemente abre el archivo `index.html` en tu navegador web, o utiliza un servidor local:

```bash
# Usando Python 3
python -m http.server 8000

# Usando Python 2
python -m SimpleHTTPServer 8000

# Usando Node.js (http-server)
npx http-server
```

Luego accede a `http://localhost:8000` en tu navegador.

## 📄 Páginas del Sitio

### 1. Index (`index.html`)
- Página de inicio con hero section
- Enlace a redes sociales
- Navegación principal
- Botón de llamada a la acción

### 2. Blogs (`blogs.html`)
- Listado de artículos del blog
- Artículo destacado principal
- Grid de artículos secundarios
- Footer con newsletter y redes sociales

### 3. Blog Individual (`blog.html`)
- Vista detallada de un artículo
- Imagen destacada
- Contenido completo del post
- Información del autor

### 4. Perfil (`perfil.html`)
- Biografía del autor
- Foto de perfil
- Listado de artículos del autor
- Información de contacto

## 🎯 Componentes Principales

### Header
- Barra de iconos de redes sociales
- Logo del blog
- Navegación principal
- Enlace a perfil del autor

### Footer
- Iconos de newsletter y likes
- Enlaces a redes sociales
- Información adicional

### Blog Posts
- Imagen destacada
- Título y extracto
- Botón de "Leer más"
- Metadatos del artículo

## 🧰 Personalización

### Cambiar Colores
Edita las variables en `css/main.css`:
```css
background-color: #47cfac;  /* Color principal */
background-color: #E6E9ED;  /* Color secundario */
```

### Modificar Imágenes
Reemplaza las imágenes en la carpeta `assets/img/` manteniendo los nombres de archivo originales.

### Ajustar Textos
Edita el contenido directamente en los archivos HTML correspondientes.

## 📝 Notas Técnicas

- El proyecto utiliza `position: fixed` en el body con una clase `.scrollable` para controlar el scroll
- El CSS está organizado en secciones con comentarios claros
- Se utiliza Flexbox y CSS Grid para layouts
- Los iconos de Flaticon requieren el archivo CSS correspondiente
- Las imágenes son cargadas como background images en CSS

## 🔧 Browser Support

- Chrome (últimas 2 versiones)
- Firefox (últimas 2 versiones)
- Safari (últimas 2 versiones)
- Edge (últimas 2 versiones)
- Navegadores móviles modernos

## 📄 Licencia

Este proyecto es un ejercicio de maquetación web con fines educativos.

## 👤 Autor

Tu nombre - https://portafolio-kohl-six-58.vercel.app/

---

**Fecha de creación**: Noviembre 2025
**Versión**: 1.0.0
