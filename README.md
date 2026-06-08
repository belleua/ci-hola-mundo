# Hola Mundo CI - ITLA 2026

Practica de Integracion Continua con GitHub Actions.

## Que hace este repositorio

- Programa **Hola Mundo** en JavaScript (`index.js`)
- Workflow de GitHub Actions (`.github/workflows/alerta.yml`) que:
  - Se activa automaticamente al hacer **push a `main`**
  - Ejecuta el programa Hola Mundo
  - Envia una notificacion a **ntfy.sh/devops-itla**

## Como ver las notificaciones

Visita [https://ntfy.sh/devops-itla](https://ntfy.sh/devops-itla) en el navegador,  
o instala la app de **ntfy** y suscribete al topico `devops-itla`.

## Estructura

```
.
├── index.js
├── README.md
└── .github/
    └── workflows/
        └── alerta.yml
```
