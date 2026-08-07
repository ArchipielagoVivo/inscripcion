# Archipiélago Vivo — Inscripción

Página pública de inscripción de **Archipiélago Vivo**.

Este repositorio contiene la página web utilizada para facilitar la incorporación de personas, proyectos, iniciativas y entidades al mapa vivo de Canarias.

## Dirección

La página estará disponible en:

**https://inscripcion.archipielagovivo.org**

## Formulario

La inscripción se gestiona mediante Google Forms:

https://forms.gle/5ynUxUWBNJy5okgF9

La página del repositorio actúa como interfaz pública de acceso al formulario, manteniendo una dirección propia de Archipiélago Vivo.

## Objetivo

Crear un punto de entrada sencillo y reconocible para que cualquier persona o proyecto pueda solicitar su incorporación al mapa de Archipiélago Vivo.

La página debe:

- Presentar brevemente el propósito de la inscripción.
- Facilitar el acceso al formulario.
- Mantener la identidad visual de Archipiélago Vivo.
- Ser accesible desde dispositivos móviles.
- Utilizar el dominio `inscripcion.archipielagovivo.org`.
- Mantener una estructura sencilla y fácil de actualizar.

## Arquitectura

```text
inscripcion.archipielagovivo.org
│
├── Página de inscripción
│
└── Google Forms
    └── Registro de personas, proyectos e iniciativas
