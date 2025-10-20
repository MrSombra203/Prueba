# BlackHawk Industrial - Proyecto Responsive

## Descripción del Proyecto

Este proyecto es una página web responsive para BlackHawk Industrial, una empresa de suministros industriales. El diseño está basado en las imágenes proporcionadas y implementa todas las técnicas de desarrollo web moderno solicitadas.

## Características Implementadas

### ✅ Técnicas Responsive Aplicadas

1. **Flexbox**: Utilizado para el layout del header, navegación, botones y elementos de contacto
2. **CSS Grid**: Implementado para las secciones de categorías, contenido destacado, productos y footer
3. **Media Queries**: Responsive design completo con breakpoints para tablet, móvil y móvil pequeño

### ✅ Sass Features

1. **Variables**: Colores, tipografía, espaciado, breakpoints y sombras definidos como variables
2. **Nesting**: Estructura anidada para mejor organización del código
3. **Mixins**: Funciones reutilizables para flexbox, botones y grids
4. **Componentes**: Sistema de componentes modulares (botones, cards, etc.)

### ✅ Nomenclatura BEM

Toda la estructura HTML utiliza la metodología BEM (Block Element Modifier):
- **Block**: `.header`, `.hero`, `.category-section`
- **Element**: `.header__nav`, `.hero__title`, `.category-card__image`
- **Modifier**: `.btn--primary`, `.category-card--new`, `.testimonial__indicator--active`

## Estructura del Proyecto

```
BlackHawk-Industrial/
├── 📁 src/                    # Código fuente HTML
│   └── index.html             # Página principal
├── 📁 styles/                 # Archivos de estilos
│   ├── styles.scss            # Archivo Sass principal
│   └── styles.css             # CSS compilado
├── 📁 assets/                 # Recursos estáticos
│   └── 📁 images/             # Imágenes del proyecto
│       ├── Imagen fabrica.png
│       ├── Imagen heramientas.png
│       ├── Imagen masquin.png
│       ├── Imagen puntas de destornillador.png
│       ├── Imagen Ciinta portectora.png
│       ├── Imagen Bodegas.png
│       ├── Imagen Trabajador en bodegas.png
│       ├── Imagen Trabajador en porto.png
│       └── Imagen Tranadador.png
├── 📁 docs/                   # Documentación
│   └── README.md              # Este archivo
├── package.json               # Configuración del proyecto
├── .gitignore                 # Archivos a ignorar en Git
└── sass.config               # Configuración de Sass
```

## Secciones Implementadas

1. **Header**: Barra superior con utilidades y navegación principal
2. **Hero Section**: Banner principal con call-to-action
3. **Shop by Category**: Grid de categorías de productos
4. **Featured Content**: Contenido destacado en cards
5. **Testimonial**: Sección de testimoniales con indicadores
6. **Best Sellers**: Carousel de productos más vendidos
7. **Product Listings**: Grid de productos con formularios
8. **Contact Services**: Sección de contacto con overlay
9. **Blog Section**: Sección del blog con fondo oscuro
10. **Featured Content Bottom**: Contenido adicional en grid
11. **Footer**: Footer completo con información de contacto y enlaces

## Responsive Breakpoints

- **Desktop**: > 1024px (4 columnas en grids)
- **Tablet**: 768px - 1024px (3 columnas en grids principales)
- **Mobile**: 640px - 768px (2 columnas, navegación colapsada)
- **Small Mobile**: < 640px (1 columna, layout vertical)

## Tecnologías Utilizadas

- HTML5 semántico
- CSS3 con Flexbox y Grid
- Sass (SCSS)
- Metodología BEM
- Responsive Design
- Google Fonts (Inter)

## Características Responsive Específicas

### Header
- Navegación colapsa en móvil
- Búsqueda se adapta al ancho completo en móvil
- Logo mantiene proporciones

### Grids Responsive
- **Category Grid**: 4→3→2→1 columnas
- **Featured Content**: 2→1 columnas
- **Product Listings**: 4→2→1 columnas
- **Footer**: 4→2→1 columnas

### Componentes Adaptativos
- Botones mantienen usabilidad en touch
- Cards con hover effects en desktop
- Carousel con scroll horizontal en móvil
- Formularios optimizados para móvil

## Instrucciones de Uso

1. Abrir `src/index.html` en un navegador web
2. El diseño es completamente responsive
3. Probar en diferentes tamaños de pantalla
4. Verificar la funcionalidad de navegación y formularios

### Desarrollo con Sass

Para compilar Sass a CSS:
```bash
npm run build    # Compilar una vez
npm run watch    # Compilar automáticamente al guardar cambios
```

### Servidor de Desarrollo

Para usar un servidor local:
```bash
npm install      # Instalar dependencias
npm run dev      # Iniciar servidor en http://localhost:8080
```

## Notas de Desarrollo

- Todas las imágenes utilizan archivos reales de la carpeta `assets/images/`
- Los colores siguen la paleta de BlackHawk Industrial
- La tipografía utiliza la fuente Inter de Google Fonts
- El código está optimizado para rendimiento y mantenibilidad
- Estructura de carpetas organizada para mejor mantenimiento

## Imágenes Utilizadas

- **Imagen fabrica.png**: Fondo del hero section y contenido destacado
- **Imagen heramientas.png**: Categorías de herramientas y productos
- **Imagen masquin.png**: Maquinaria industrial y productos
- **Imagen puntas de destornillador.png**: Herramientas de precisión
- **Imagen Ciinta portectora.png**: Equipos de seguridad
- **Imagen Bodegas.png**: Operaciones de bodega y logística
- **Imagen Trabajador en bodegas.png**: Fondo de contacto y operaciones
- **Imagen Trabajador en porto.png**: Fondo del blog y operaciones portuarias
- **Imagen Tranadador.png**: Contenido destacado de profesionales

