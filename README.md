# Opositests

**Aplicación local multiplataforma para la preparación de oposiciones**, con banco de tests, supuestos prácticos, material PDF asociado, estadísticas de progreso y perfiles de oposición independientes.

> El código fuente de este proyecto es privado. Este repositorio es un escaparate del producto: documentación, capturas y demo. **Código disponible bajo demanda** para procesos de selección: [meterre@gmail.com](mailto:meterre@gmail.com)

## Plataformas

| Plataforma | Formato |
|---|---|
| Escritorio (Windows/Linux/Mac) | Aplicación HTML local |
| Android / tablet | Versión HTML adaptada a táctil |
| Android nativo | APK generada con Capacitor |

El proyecto sigue un flujo de desarrollo controlado: la versión de escritorio es la base del producto, de ella deriva la versión Android validada, y de esta se genera la APK.

## Funcionalidades

- Banco de tests y supuestos prácticos con **editor integrado**
- **Parser/importador** de texto estructurado para crear tests rápidamente
- **Perfiles de oposición independientes**, con progreso separado por oposición
- Exportación e importación de oposiciones completas
- **Biblioteca y visor PDF** con asociaciones por tema, bloque o apunte
- Estadísticas de progreso, preguntas favoritas, difíciles y falladas
- Modo estudio (oculta las herramientas avanzadas)
- Ajustes globales de interfaz, táctil, orden de preguntas, temporizador y visualización
- Panel Android con exportación nativa

## 🖼️ Capturas

### Escritorio

**Pantalla principal** — perfiles de oposición y acceso rápido

<img src="screenshots/01-principal.png" width="800">

**Modo test** — realización de tests y supuestos prácticos

<img src="screenshots/02-test.png" width="800">

**Estadísticas** — progreso, preguntas falladas y favoritas

<img src="screenshots/03-estadisticas.png" width="800">

**Editor de tests** — creación y edición de preguntas

<img src="screenshots/04-editor.png" width="800">

**Gestor de material** — asociación de PDFs por tema o bloque

<img src="screenshots/05-material_pdf.png" width="800">

**Biblioteca** — documentación de la oposición

<img src="screenshots/06-biblioteca.png" width="800">

**Visor PDF** — lectura integrada del temario

<img src="screenshots/07-visor_pdf.png" width="800">

**Gestor de oposiciones** — perfiles independientes con progreso separado

<img src="screenshots/08-oposicion.png" width="800">

### Android

**Interfaz adaptada** a móvil y tablet

<img src="screenshots/09-android_app.png" width="350">

**Modo test** con controles táctiles

<img src="screenshots/10-android_test.png" width="350">

## Arquitectura (resumen)

- **Núcleo modular en JavaScript** reutilizado por las tres variantes (escritorio, Android HTML y Capacitor)
- Dependencias estáticas vendorizadas (sin build tools ni conexión requerida)
- **Scripts de validación** en PowerShell que verifican cada versión antes de release
- Generación automatizada de versión *singlefile* de escritorio
- Proyecto Capacitor semilla para empaquetar la APK
- Flujo de release documentado con checklist y baselines versionadas

## Stack y herramientas

HTML · CSS · JavaScript · Capacitor · PowerShell · Git

Desarrollado con asistencia de IA: **OpenAI Codex** (desarrollo) y **Claude** (generación de temario y exámenes).

## Autor

**Francisco Javier Loscos Gil** — Zaragoza, España
[GitHub](https://github.com/Metr81) · [meterre@gmail.com](mailto:meterre@gmail.com)

© 2026 Francisco Javier Loscos Gil. Todos los derechos reservados.
