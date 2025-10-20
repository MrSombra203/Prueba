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
├── index.html          # Estructura HTML con BEM
├── styles.scss         # Archivo Sass con variables, nesting y mixins
├── styles.css          # CSS compilado
└── README.md          # Documentación del proyecto
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

1. Abrir `index.html` en un navegador web
2. El diseño es completamente responsive
3. Probar en diferentes tamaños de pantalla
4. Verificar la funcionalidad de navegación y formularios

## Notas de Desarrollo

- Todas las imágenes utilizan placeholders de `via.placeholder.com`
- Los colores siguen la paleta de BlackHawk Industrial
- La tipografía utiliza la fuente Inter de Google Fonts
- El código está optimizado para rendimiento y mantenibilidad


