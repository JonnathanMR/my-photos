# my-photos

Proyecto móvil/web construido con Ionic, Angular y Capacitor. El estado actual parte de la estructura inicial de Ionic y utiliza la ruta dinámica `folder/:id` como pantalla principal.

## Tecnologías

- Angular 17
- Ionic 7
- Capacitor 5
- TypeScript

## Requisitos

- Node.js LTS y npm.
- Ionic CLI opcional para el flujo de desarrollo.

## Instalación y ejecución

```bash
npm install
npm start
```

La aplicación quedará disponible en la URL local indicada por Angular.

## Comandos útiles

```bash
npm run build   # Compila el proyecto
npm test        # Ejecuta pruebas unitarias
npm run lint    # Ejecuta el análisis estático
```

## Estructura

```text
src/app/
├── folder/                 # Módulo de la vista por carpeta
├── app-routing.module.ts   # Rutas de la aplicación
├── app.module.ts           # Módulo principal
└── app.component.*         # Componente raíz
```

## Próximos pasos

El repositorio conserva la base de Ionic. Documenta aquí las pantallas, fuentes de datos y permisos de dispositivo cuando se incorporen las funcionalidades específicas de gestión de fotos.
