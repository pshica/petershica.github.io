# Peter Shica - Website Structure

## 📁 Estructura de Archivos

```
petershica.github.io/
├── index.html                          # Página principal con contador de visitas
├── CNAME                               # Configuración de dominio
├── README.md                           # Este archivo
├── img/                                # Imágenes del sitio
│   ├── foto_perfil.jpg
│   ├── fondo_header.png
│   ├── aca.png
│   ├── CV.png
│   └── blog.png
├── academico/                          # Sección académica
│   ├── index.html                      # Página principal académica
│   ├── matematicas/                    # Contenido de matemáticas
│   │   ├── index.html                  # Página de matemáticas
│   │   └── derivadas-parciales.html    # Artículo ejemplo
│   ├── fisica/                         # Contenido de física
│   │   └── index.html                  # Sección completa de física
│   ├── estadistica/                    # Contenido de estadística
│   │   └── index.html                  # Sección completa de estadística
│   └── machine-learning/               # Contenido de ML
│       └── index.html                  # Sección completa de ML
├── curriculum/                         # Sección currículum
│   └── index.html                      # Página de currículum
├── blog/                              # Sección blog
│   ├── index.html                     # Página principal del blog
│   ├── reflexiones-sobre-ia-y-futuro-del-trabajo.html
│   ├── la-importancia-del-pensamiento-critico.html
│   └── mi-experiencia-en-el-master-de-ciencia-de-datos.html
└── docs/                              # Documentos y recursos
    ├── cv-print.html                  # Versión imprimible del CV
    ├── README.md                      # Instrucciones PDF
    └── books/                         # Libros para descarga
        └── README.md                  # Instrucciones de libros
```

## 🔗 Rutas de Navegación

### Principales
- **Inicio**: `/index.html`
- **Académico**: `/academico/index.html`
- **Currículum**: `/curriculum/index.html`
- **Blog**: `/blog/index.html`

### Académicas
- **Matemáticas**: `/academico/matematicas/index.html`
- **Física**: `/academico/fisica/index.html`
- **Estadística**: `/academico/estadistica/index.html`
- **Machine Learning**: `/academico/machine-learning/index.html`

### Blog
- **Artículo IA**: `/blog/reflexiones-sobre-ia-y-futuro-del-trabajo.html`
- **Pensamiento Crítico**: `/blog/la-importancia-del-pensamiento-critico.html`
- **Experiencia Máster**: `/blog/mi-experiencia-en-el-master-de-ciencia-de-datos.html`

## 🎨 Características Implementadas

### ✅ Completadas
- [x] Estructura jerárquica de carpetas limpia y organizada
- [x] Navegación consistente entre secciones
- [x] Breadcrumb navigation
- [x] Página principal académica
- [x] Sección de matemáticas completa con ejemplo optimizado
- [x] Sección de física completa (6 áreas de estudio)
- [x] Sección de estadística completa (6 áreas de estudio)
- [x] Sección de machine learning completa (6 áreas de estudio)
- [x] Blog completo con 3 artículos
- [x] Currículum con descarga PDF
- [x] Contador de visitas en index.html
- [x] Diseño responsive
- [x] **LIMPIEZA COMPLETA**: Eliminados todos los archivos obsoletos
  - ❌ academico.html → ELIMINADO
  - ❌ blog.html → ELIMINADO  
  - ❌ matematicas.html → ELIMINADO
  - ❌ curriculum.html → ELIMINADO
- [x] **MEJORA DE LEGIBILIDAD**: Artículo de derivadas parciales optimizado
  - ✅ Tabla de contenidos no-sticky para mejor navegación
  - ✅ Espaciado mejorado entre secciones
  - ✅ Botón "volver arriba" con scroll suave
  - ✅ Navegación interna optimizada
  - ✅ Rutas de navegación actualizadas

### 🚧 Por Desarrollar
- [ ] Más artículos académicos en cada sección
- [ ] Sistema de búsqueda
- [ ] RSS feeds
- [ ] Más entradas de blog
- [ ] Notebooks de Jupyter interactivos
- [ ] Casos de estudio detallados

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con CSS Variables
- **JavaScript**: Interactividad y contador de visitas
- **MathJax**: Renderizado de ecuaciones matemáticas
- **Google Fonts**: Tipografía Montserrat
- **Responsive Design**: Mobile-first approach

## 📱 Compatibilidad

- ✅ Navegadores modernos (Chrome, Firefox, Safari, Edge)
- ✅ Dispositivos móviles y tablets
- ✅ Accesibilidad web básica
- ✅ SEO-friendly

## 🔄 Actualización de Rutas

Todas las rutas han sido actualizadas para reflejar la nueva estructura:

### Archivos Modificados
1. `index.html` - Rutas de navegación principal
2. `academico/index.html` - Navegación académica
3. `curriculum/index.html` - Enlaces actualizados
4. `blog/index.html` - Navegación del blog
5. Artículos del blog - Breadcrumbs y navegación

### Patrones de Rutas
- **Relativas hacia arriba**: `../` para subir un nivel
- **Relativas hacia abajo**: `folder/` para bajar un nivel
- **Rutas absolutas**: Desde la raíz del sitio

## 📋 Tareas de Mantenimiento

### Regulares
- [ ] Verificar enlaces rotos
- [ ] Actualizar fechas de contenido
- [ ] Optimizar imágenes
- [ ] Revisar responsive design

### Futuras
- [ ] Implementar sistema de comentarios real
- [ ] Agregar analytics
- [ ] Mejorar SEO
- [ ] Agregar sitemap.xml

---

*Última actualización: Julio 2025*