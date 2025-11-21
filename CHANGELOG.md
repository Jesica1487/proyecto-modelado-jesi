### 🏫 **Institución:** IES 9-018 "Gobernador Celso Jaque"
### 📚 **Carrera:** Tecnicatura Superior en Desarrollo de Software
### 📖 **Materia:** Modelado de Software
### 👨‍🏫 **Profesor:** Paulo Alvarez
---
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## jesvqz1487_blog

Mi versión personal del proyecto "Institución Digital" desarrollada como parte del curso de Modelado de Software.

### [1.0.0] - 2025-11-20

#### Added (jesvqz1487_blog)
- Fork independiente del proyecto original IES9018/proyecto-modelado-2025
- Diagramas UML profesionales para Clases 1, 2 y 3 (6 imágenes)
- Documentación completa de casos de uso, diagramas de clases, secuencia y actividad
- Arquitectura MVC documentada con patrones de diseño (Facade, Singleton)
- Reorganización profesional por carpetas (clase-1/, clase-2/, clase-3/)
- README documentado por cada clase con descripciones de diagramas
- Release v1.0.0 publicada en GitHub
- Estructura normalizada: archivos en kebab-case, diagramas con fuentes .drawio
- LICENSE MIT para proyecto personal

#### Changed (jesvqz1487_blog)
- Estructura de carpetas: de DIAGRAMA/ a clase-1/clase-2/clase-3/
- Nombres de archivos: de MAYÚSCULAS a kebab-case (minúsculas con guiones)
- Documentación orientada a portafolio profesional

---

## [Unreleased] - Proyecto Original IES9018

### Added
- Clase 4: Versionado Semántico, Tags, CHANGELOG y Fork Workflow
- Checklist de evaluación comprehensivo para Clases 1-4

## [1.3.0] - 2025-01-30

### Added
- `clase-4-versionado-tags.md`: Tutorial completo sobre versionado semántico, Git tags, CHANGELOG.md y flujo fork→merge→PR
- `checklist-evaluacion-clases.md`: Checklist de evaluación detallado con rúbrica para las 4 clases
- Conceptos: Semantic Versioning (MAJOR.MINOR.PATCH), Tags anotados vs lightweight, Keep a Changelog format
- Tutorial paso a paso: Sistema de categorías para el blog como nueva funcionalidad (v1.2.0)
- Comandos Git avanzados: tags, remotes upstream, fetch, merge upstream
- Flujo profesional: merge en fork personal antes de abrir PR al repo central
- Explicación detallada de .gitignore con patrones comunes
- Glosario de términos de versionado y releases

### Changed
- Actualización del CHANGELOG.md siguiendo el estándar Keep a Changelog

## [1.2.0] - 2025-01-29

### Added
- GitHub Discussions habilitado como canal oficial de comunicación
- Discussion #6: "Política del Repositorio: NO realizar merges por cuenta propia"
- Discussion #7: "Retrospectiva semanal - Plantilla" para reflexión estudiantil
- Configuración de merge strategy: squash-only, auto-delete branches
- `seguimiento-estudiantes.json`: Sistema de tracking de estudiantes con campos de evaluación

### Changed
- Branch protection en main: require 1 approval, linear history, conversation resolution
- Flujo de trabajo: los estudiantes deben esperar aprobación docente antes de merge

### Fixed
- Revertidos merges no autorizados de PR #2 y PR #3 como medida educativa
- Formato markdown en `clase-2-diagramas-uml.md` (punto 4 - diagrama Mermaid)

## [1.1.0] - 2025-01-28

### Added
- Revisiones educativas completas de PR #1 (VazAlexx), #2 (Milasch23), #3 (Jesica1487), #4 (Anmonte), #5 (ClaudioMPerez)
- Feedback constructivo en cada PR con identificación de áreas de mejora

### Changed
- Enfoque pedagógico: de corrección directa a guía con feedback formativo

## [1.0.0] - 2025-10-31

### Added
- Initial release of the complete course material for "Modelado de Software".
- Creation of all pedagogical documents, including class tutorials, glossaries, and guides.
- `clase-1-introduccion-uml.md`: Tutorial for Use Cases and basic Git.
- `clase-2-diagramas-uml.md`: Tutorial for Class, Sequence, and Activity diagrams.
- `clase-3-principios-patrones-arquitecturas.md`: Tutorial for design principles, patterns, and MVC.
- `glosario-desarrollo-software.md`: Complete glossary of technical terms.
- `herramientas-esenciales.md`: Setup guide for Git, GitHub, and other tools.
- `fundamentos-arquitectura-software.md`: Document explaining high-level architecture concepts.
- `flujo-trabajo-colaborativo.md`: Guide on using the Fork & Pull Request workflow.
- `tarea-proyecto-final.md`: Final project instructions for students.
- `rubrica-evaluacion.md`: Evaluation rubric for the final project.
- `LISTA_ESTUDIANTES.md`: Pre-populated list of students for peer review.
- `guia-uso-ia-aprender.md`: Guide for using AI as a learning tool.
- `.gitignore`: Basic gitignore file for OS and editor-specific files.
- Standardized headers with course information added to all Markdown files.

### Changed
- Refined project structure based on iterative feedback.
- Switched from a collaborator-based workflow to a Fork & Pull Request model.

### Removed
- Deleted initial `.txt` files after migrating their content to structured Markdown.
