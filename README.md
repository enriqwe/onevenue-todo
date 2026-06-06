# OneVenue To-Do

Herramienta estatica para ordenar tareas de trabajo, mover prioridades y tachar lo completado.

## Uso

Abre `index.html` en un navegador o publícalo como sitio estatico. Las tareas se guardan en `localStorage` del navegador; el repo solo contiene el codigo de la herramienta, no datos de trabajo.

## Datos

- Funciona sin backend usando `localStorage`.
- Si se sirve desde `enriqwe.es` con `/api/onevenue-todo/tasks`, sincroniza contra ese JSON privado.
- No sube tareas a GitHub.
- Permite exportar/importar una copia JSON desde la interfaz.
