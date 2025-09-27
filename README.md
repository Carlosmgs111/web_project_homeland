# Galería de Arte TripleTen

**De patria a patria** es una galería de arte web interactiva que presenta las historias y fotografías de profesionales de tecnología de diferentes rincones del mundo que forman parte de la comunidad TripleTen. El proyecto celebra la diversidad cultural y las experiencias únicas de personas que han viajado desde sus lugares de origen hasta formar parte de esta comunidad tecnológica global.

![Screenrecord](./images/screenrecord.gif)

### Funcionalidades principales:

- Presentación visual de historias personales de diferentes países y culturas
- Galería fotográfica de lugares emblemáticos de cada región representada
- Diseño responsive que se adapta a diferentes dispositivos
- Interfaz intuitiva para explorar las diferentes historias
- Sección interactiva que invita a los usuarios a contribuir con sus propias historias|

### Tecnologías Frontend

- **HTML5**: Estructura semántica y accesible del contenido
- **CSS3**: Estilos visuales, layouts responsive y animaciones
- **JavaScript**: Interactividad y funcionalidades dinámicas

### Tipografía y Diseño

- **Fuente Inter v4.1**: Implementada mediante `@font-face` con archivos locales descargados desde el repositorio oficial de rsms
- **Diseño responsive**: Implementado con CSS Grid y Flexbox para adaptabilidad a diferentes dispositivos
- **Principios de diseño UI/UX**: Siguiendo las especificaciones de diseño de Figma

### Técnicas de Desarrollo

- **Metodología BEM**: Para organización y nomenclatura de clases CSS
- **CSS Custom Properties**: Para mantenimiento eficiente de variables de diseño
- **Optimización de fuentes**: 
  - Uso de formatos WOFF2 y WOFF para mejor compresión
  - `font-display: swap` para mejorar la experiencia de carga
  - Carga selectiva de pesos de fuente según necesidades del diseño

### Estructura del Proyecto

```
web_project_homeland/
├── blocks/
│   ├── content.css
│   ├── footer.css
│   ├── header.css
│   ├── logo.css
│   └── page.css
├── images/
│   └── kalegin-michail-179870-unplash.png
│   └── TRIPLETEN_ART_GALLERY.svg
├── pages/
│   └── index.html
├── vendor/
│   └── fonts/
│       ├── Inter-Regular.woff2
│       └── Inter-Black.woff2
│   ├── fonts.css
│   ├── normalize.css
├── .editorconfig
├── .gitignore
├── .prettierrc
├── index.html
└── README.md
```

### Características Técnicas

- **Semántica HTML**: Uso correcto de etiquetas semánticas para mejorar la accesibilidad
- **Performance optimizada**: Carga eficiente de recursos y optimización de imágenes
- **Cross-browser compatibility**: Compatibilidad con navegadores modernos
- **Código limpio**: Siguiendo mejores prácticas de desarrollo web

---

© 2024. Carlos Muñoz