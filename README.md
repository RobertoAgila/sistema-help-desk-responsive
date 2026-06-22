# Actividad #6 - Implementación de Diseño Adaptable y Layout

## Descripción
Este proyecto integra el UI Kit del sistema Help Desk en tres páginas estructurales: `index.html`, `reportar.html` y `tickets.html`. Se aplicó CSS3 puro con Flexbox, CSS Grid y Media Queries para garantizar una visualización correcta en escritorio, tablet y móvil.

## Archivos principales
- `index.html`: Dashboard principal del sistema.
- `reportar.html`: Formulario para reportar incidentes.
- `tickets.html`: Tabla/listado de tickets registrados.
- `style.css`: Librería de estilos, componentes UI Kit y reglas responsive.

## Técnicas utilizadas
- Variables CSS en `:root`.
- `box-sizing: border-box` global.
- Flexbox en encabezado, navegación y footer.
- CSS Grid en Dashboard, estadísticas y formulario.
- Media Queries en 1024px, 768px y 480px.
- Tabla responsive que se transforma en tarjetas en pantallas menores a 768px.
- Metaetiqueta viewport incluida en los tres HTML.

## Rama de GitHub solicitada
```bash
git checkout develop
git pull origin develop
git checkout -b feature/responsive-layout
git add index.html reportar.html tickets.html style.css README.md
git commit -m "Implementar layout responsive del Help Desk"
git push -u origin feature/responsive-layout
```

Luego crear el Pull Request desde `feature/responsive-layout` hacia `develop`.

## Pruebas sugeridas
1. Abrir `index.html` en el navegador.
2. Presionar F12 y activar la vista responsive.
3. Probar escritorio, tablet y móvil.
4. Revisar que el menú se apile verticalmente en móvil.
5. Verificar que el formulario y la tabla ocupen el 100% del ancho disponible sin desbordamiento horizontal.
