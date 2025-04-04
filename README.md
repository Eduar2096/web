# RateMyProf

Sistema web para calificar profesores. Incluye:

- Visualización de profesores
- Calificaciones por conocimiento, pedagogía y puntualidad
- Comentarios de estudiantes
- Edición y eliminación de reseñas

## Backend (API)

Este frontend está conectado a una API REST desarrollada en .NET que debe estar corriendo en:

```
https://localhost:7267/api
```

### Endpoints esperados:

- `GET /api/Profesores` - Lista de profesores
- `POST /api/ReseñasProfesores` - Crear reseña
- `GET /api/ReseñasProfesores/mis-reseñas` - Obtener mis calificaciones
- `PUT /api/ReseñasProfesores/{id}` - Editar reseña
- `DELETE /api/ReseñasProfesores/{id}` - Eliminar reseña

## Requisitos

- Tener backend corriendo en .NET
- Usar navegador compatible (Chrome, Firefox, Edge)

## Créditos

Desarrollado por TaekaCR con ayuda de ChatGPT.
