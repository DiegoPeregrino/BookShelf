# BookShelf

Aplicación web para la gestión de una biblioteca. El proyecto está desarrollado con una arquitectura separada entre frontend y backend.

## Tecnologías

### Backend
- C#
- ASP.NET Core Web API
- .NET 11

### Frontend
- React
- JavaScript
- Vite

## Estructura del proyecto

```text
BookShelf/
├── backend/
│   ├── BookShelf.Api/
│   ├── BookShelf.Application/
│   ├── BookShelf.Domain/
│   └── BookShelf.Infrastructure/
│
├── frontend/
│   └── bookshelf-client/
│
├── .gitignore
└── README.md
```

## Arquitectura

El backend está organizado en cuatro proyectos:

- **Api:** exposición de endpoints HTTP.
- **Application:** casos de uso y servicios de aplicación.
- **Domain:** entidades y reglas de negocio.
- **Infrastructure:** persistencia y servicios externos.

El frontend consume los servicios del backend mediante una API REST.

## Estado del proyecto

En desarrollo. Actualmente se encuentra creada la estructura inicial del backend y frontend.

## Ejecución

Las instrucciones de instalación y ejecución se incorporarán conforme avance el desarrollo.

## Autor

Diego Peregrino