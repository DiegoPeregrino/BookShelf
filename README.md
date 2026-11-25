# BookShelf

A full-stack library management system built with .NET and React.

## Technologies

### Backend
- C#
- .NET 11
- ASP.NET Core Web API

### Frontend
- React
- JavaScript
- Vite

## Project Structure

```text
BookShelf/
├── backend/
│   └── BookShelf/
│       ├── BookShelf.Api/
│       ├── BookShelf.Application/
│       ├── BookShelf.Domain/
│       ├── BookShelf.Infrastructure/
│       └── BookShelf.slnx
│
├── frontend/
│   └── bookshelf-client/
│       ├── public/
│       ├── src/
│       ├── package.json
│       └── vite.config.js
│
├── .gitignore
├── .gitattributes
└── README.md
```

## Architecture

The backend is organized into four projects, each with a specific responsibility:

- **Api:** Exposes HTTP endpoints and handles incoming requests.
- **Application:** Contains application services and use cases.
- **Domain:** Defines business entities and domain rules.
- **Infrastructure:** Handles data persistence and external service integrations.

The frontend communicates with the backend through a REST API.

## Project Status

In development. The initial backend and frontend structures have been created.

## Getting Started

Setup and execution instructions will be added as development progresses.

## Author

Diego Peregrino
