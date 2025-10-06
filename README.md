# Seguridad TP2 - Aplicación Node.js

Una aplicación Node.js simple desarrollada para el curso de seguridad.

## Descripción

Este proyecto es una aplicación web básica construida con Express.js que será utilizada para demostrar conceptos de seguridad en aplicaciones web.

## Características

- ✅ Servidor Express.js básico
- ✅ API REST con endpoints de ejemplo
- ✅ Manejo básico de errores
- ✅ Configuración de GitHub Actions (CI/CD)
- ✅ Estructura de proyecto organizada

## Requisitos

- Node.js >= 14.0.0
- npm o yarn

## Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/seguridad_tp2.git
cd seguridad_tp2
```

2. Instala las dependencias:
```bash
npm install
```

3. Ejecuta la aplicación:
```bash
npm start
```

La aplicación estará disponible en `http://localhost:3000`

## Scripts disponibles

- `npm start` - Ejecuta la aplicación en modo producción
- `npm run dev` - Ejecuta la aplicación en modo desarrollo
- `npm test` - Ejecuta las pruebas (por implementar)

## Endpoints

### GET /
Endpoint principal que devuelve información básica de la aplicación.

### GET /api/health
Endpoint de estado que devuelve información sobre la salud de la aplicación.

## Estructura del proyecto

```
seguridad_tp2/
├── .github/
│   └── workflows/          # GitHub Actions workflows
├── index.js               # Archivo principal de la aplicación
├── package.json          # Configuración del proyecto y dependencias
├── README.md            # Este archivo
└── .gitignore          # Archivos ignorados por Git
```

## Desarrollo

Este proyecto está en desarrollo activo como parte del curso de seguridad. Se irán agregando más características y mejoras de seguridad durante las clases.

## Licencia

MIT License