Proyecto de Automatización API - Karate DSL

1. Objetivo
Crear una suite de pruebas automatizadas para la API de usuarios utilizando Karate DSL, implementando escenarios positivos y negativos y validando respuestas y esquemas JSON.

2. Estrategia de Automatización
- Los escenarios están en feature files en `src/test/java/features/`.
- Se cubren operaciones CRUD: GET, POST, PUT, DELETE.
- Incluye validaciones de estado HTTP y contenido de la respuesta.
- Se manejan diferentes escenarios de usuario (positivos y negativos).

3. Estructura del Proyecto
   │
   ├─ src/test/java/features/usuarios.feature
   ├─ src/test/java/karate/ # helpers opcionales
   ├─ pom.xml
   └─ README.md
4. 