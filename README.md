# Despliegue en producción — Aplicación Java con CI/CD

Actividad práctica de la asignatura de **Despliegue de Aplicaciones Web** (DAW),
centrada en compilar y desplegar en producción una aplicación **Java** mediante un
flujo de **integración y despliegue continuo (CI/CD)** con **GitHub Actions**.

> Proyecto de aprendizaje. Lo mantengo público como muestra de mis conocimientos de
> build con Maven y de automatización del despliegue.


## Qué demuestra

- Construcción de un proyecto **Java** con **Maven** (incluye Maven Wrapper).
- Automatización del **build y el despliegue con GitHub Actions** (`.github/workflows`).
- Flujo de despliegue a un entorno de producción.

## Tecnologías y herramientas

- Java
- Maven (con Maven Wrapper: `mvnw` / `mvnw.cmd`)
- GitHub Actions (CI/CD)


## Despliegue (CI/CD)

El despliegue está automatizado con GitHub Actions: cada cambio en la rama principal
dispara el flujo definido en `.github/workflows`.


---

Autor: **Aitor Serrano** · [github.com/Aitorser](https://github.com/Aitorser)
