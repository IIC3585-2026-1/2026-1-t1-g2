# 2026-1-t1-g2

## Elementos de CSS

- [ ] Media queries
  - Cambiar según tamaño de la vista/browser
- [ ] Container queries
  - Cambiar según tamaño del contenedor
- [ ] Flexbox
- [ ] Grid
- [ ] Variables
- [ ] Funciones
- [ ] Anidación de reglas
- [ ] Transformaciones
- [ ] Transiciones
- [ ] Animaciones

## Estructura

(Propuesto por Gemini)

```text
/css
├── main.css            # Punto de entrada (Importa todo)
├── _variables.css      # Colores, fuentes y gaps
├── _base.css           # Resets (Box-sizing) y estilos globales
└── /components
    ├── _navbar.css
    ├── _hero.css
    ├── _gallery.css
    ├── _features.css
    └── _footer.css
```

### Hero

Elementos:

- Animaciones
- Transformaciones

### Gallery

Galería de imágenes con distintos tamaños

Elementos:

- Grid

### Features

Lista de funcionalidades/características

Elementos:

- Flex-box
