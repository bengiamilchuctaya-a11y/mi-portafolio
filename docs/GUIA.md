# Guía del Laboratorio: Trabajo Colaborativo

Este documento explica cómo colaboramos en el proyecto "tienda-tecsup" sin tocar el código original del docente.

## Conceptos Principales

En este laboratorio aprendimos el flujo de trabajo estándar en equipos de desarrollo:

- **Fork:** Es tu propia copia exacta del repositorio original.
- **Issue:** Sirve para reportar un error detallando qué se esperaba y qué ocurrió.
- **Pull Request (PR):** Es la petición formal para que el dueño del proyecto acepte tus correcciones.

### Pasos de clonación y corrección

Para poder trabajar y arreglar errores (como el problema matemático o la ruta del CSS), seguimos este orden:

1. Hacer clic en _Fork_ en el repositorio original de GitHub.
2. Descargar la copia a la computadora ejecutando `git clone <url-de-tu-fork>`.
3. Crear una rama nueva aislada para no dañar el proyecto principal.
4. Subir la corrección y abrir un _Pull Request_ desde GitHub.

## Tareas del Laboratorio 03

- [x] Hacer un fork y clonar el repositorio tienda-tecsup.
- [x] Solucionar el problema de la multiplicación en el carrito (Issue #106).
- [x] Corregir la ruta del archivo de estilos CSS (Issue #137).
- [ ] Integrar los cambios en el proyecto original (depende del docente).

### Captura de mi trabajo

![Pantalla principal del proyecto](/img/captura2.png)

## Archivos y Comandos Usados

| Elemento          | ¿Para qué sirve en el proyecto?                                |
| ----------------- | -------------------------------------------------------------- |
| `script.js`       | Archivo modificado para multiplicar el precio por la cantidad. |
| `git switch main` | Comando que usamos para regresar a la rama principal.          |
| `git checkout -b` | Comando para crear una rama nueva y movernos a ella.           |

## Ejemplo de Sincronización

Es vital actualizar tu repositorio local antes de crear una rama nueva para evitar conflictos de versiones. Esto se hace usando comandos en la terminal:

```bash
git switch main
git pull
git checkout -b nombre-de-tu-rama
```

## Enlaces utiles

- [Mi Pull request 1](https://github.com/jeisson-tecsup/tienda-tecsup/pull/137)
- [Mi Pull request 2](https://github.com/jeisson-tecsup/tienda-tecsup/pull/124)
- [El repositorio](https://github.com/bengiamilchuctaya-a11y/tienda-tecsup.git)
- [Mi perfil de GitHub](https://github.com/bengiamilchuctaya-a11y)
