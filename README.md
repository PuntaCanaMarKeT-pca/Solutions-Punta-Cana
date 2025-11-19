
# TechTasks Punta Cana - Static Starter

Aplicación estática tipo "Tasks" para servicios técnicos en Punta Cana, Bávaro, Friusa y alrededores.
Listo para desplegar en GitHub Pages como sitio estático.

## Estructura
- index.html: página principal
- services.html: categorías
- technicians.html: listado de técnicos
- technician-profile.html: perfil de técnico (usa ?id=t001)
- contact.html: formulario (envía por WhatsApp)
- assets/css/style.css
- assets/js/main.js
- assets/data/technicians.json

## Cómo desplegar en GitHub Pages
1. Crear nuevo repositorio en GitHub.
2. Subir todo el contenido de esta carpeta a la rama `gh-pages` o `main`.
3. En Settings > Pages, seleccionar la rama usada y habilitar GitHub Pages.
4. En `assets/data/technicians.json` edita o agrega técnicos.

## Personalización recomendada
- Reemplaza los números WhatsApp por los reales (buscar '18091234567' en los archivos).
- Añade fotos reales en assets/img/ y actualiza las rutas.
- Para versión con backend: conectar una API para CRUD de técnicos y autenticación.

## Notas
- Esta es una versión 1.0, enfocada en ser simple, rápida y compatible con GitHub Pages.
