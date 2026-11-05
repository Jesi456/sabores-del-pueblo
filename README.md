# Sabores del Pueblo – Proyecto final

Sitio web del restaurante **Sabores del Pueblo** (Singuil, Catamarca), hecho con HTML y Tailwind CSS (por CDN).

## Estructura

```
mi-proyecto-final-sabores/
├── README.md
├── docs/
│   └── notas.md
├── src/
│   ├── index.html
│   ├── menu.html
│   ├── nosotros.html
│   ├── reservas.html
│   └── contacto.html
└── recursos/
    └── image/
```

- `README.md`: descripción del proyecto.
- `docs/`: documentación complementaria y notas.
- `src/`: páginas HTML.
- `recursos/image/`: imágenes del sitio.

## Cómo verlo

Abrir `src/index.html` en el navegador o con Live Server. Necesita internet para cargar Tailwind y los íconos.

## Páginas

- `index.html`: inicio.
- `menu.html`: platos y bebidas con precios.
- `nosotros.html`: historia y equipo.
- `reservas.html`: formulario de reservas.
- `contacto.html`: formulario de contacto, ubicación y horarios.

## Flujo de trabajo con Git

- Rama principal: `main`.
- Rama de trabajo: `fix/correcciones-contenido` (título, descripción, campos obligatorios y ortografía).
- Los cambios se integraron a `main` mediante el pull request #1.

## Estado del proyecto

En desarrollo. Pendiente: reemplazar el enlace del mapa en `contacto.html` por el de inserción de Google Maps.

## Aprendizajes

- **Commits:** Aprendí que conviene hacer commits chicos, de un solo cambio cada uno, y con un mensaje que diga qué se hizo. Al principio pensaba en subir todo junto, pero con un commit por cada parte (README, imágenes, cada página) el historial se lee como una lista de pasos y es más fácil encontrar algo o volver atrás si algo sale mal.
- **Ramas y pull requests:** Entendí que una rama sirve para hacer cambios sin tocar `main`, que queda como la versión ordenada del proyecto. Hice las correcciones (título, descripción, campos obligatorios y ortografía) en una rama aparte, las subí a GitHub y abrí un pull request para revisarlas antes de integrarlas.

## Autor

Ainara Jesica Gambarte Chayle