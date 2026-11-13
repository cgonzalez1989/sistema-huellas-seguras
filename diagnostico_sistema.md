# Diagnóstico y Avance del Sistema - HuellasSeguras

## Unidad 2: Actividad #3 - Resolución de Ejercicios (Maquetación Web)
Se ha implementado el prototipo estructural funcional del sistema web de Control de Rescate y Adopción Animal, basándose en la arquitectura definida en la Unidad 1, cumpliendo estrictamente con los estándares de la W3C y la accesibilidad semántica de HTML5.

### Componentes Desarrollados:
1. **Dashboard Principal (`index.html`)**: 
   - Interfaz de bienvenida con la estructura semántica obligatoria (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
   - Barra de navegación común que asegura el desplazamiento fluido entre las vistas del sistema.

2. **Formulario de Ingreso (`reportar.html`)**:
   - Formulario interactivo de captura de datos para nuevos animales rescatados.
   - Campos de texto (`<input type="text">`), listas desplegables (`<select>`) para categorías (*Perros, Gatos, Fauna Silvestre*), botones de opción (`<radio>`) para el nivel de urgencia médica (*Alta, Media, Baja*) y áreas de texto (`<textarea>`) para la descripción detallada.

3. **Listado de Casos (`rescates.html`)**:
   - Tabla estructurada (`<table>`) para la visualización organizada de los casos activos registrados en el sistema de rescate.

### Control de Versiones (Gitflow):
- Integración de los archivos desarrollados en la rama de trabajo `feature/maquetacion-html` hacia la rama `develop` mediante Pull Requests debidamente documentados.