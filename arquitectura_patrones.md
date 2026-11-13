# Arquitectura y Patrones de Diseño - HuellasSeguras

## 1. Introducción
Para garantizar un diseño modular, limpio y preparado para futuras ampliaciones, se integran cuatro patrones de diseño de software orientados a resolver necesidades específicas del refugio.

## 2. Patrones seleccionados
- **Factory Method:** Se aplica mediante la clase `GestorEspecies` para estructurar y aislar la creación de expedientes según el tipo de animal rescatado, evitando duplicar lógica de construcción.
- **Singleton:** Implementado en la clase central `SistemaRefugio` para asegurar que exista una única instancia de conexión y control global del sistema, optimizando recursos.
- **Observer:** Utilizado mediante `NotificadorVoluntarios` para automatizar el sistema de alertas; cada vez que un reporte cambia de estado o se crea un nuevo caso, los voluntarios suscritos reciben una notificación instantánea.
- **MVC (Modelo-Vista-Controlador):** Separa de forma estricta la gestión de datos, las reglas del negocio y la interfaz de usuario.