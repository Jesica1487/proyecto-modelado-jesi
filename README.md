# jesvqz1487_blog v1.0.0

> Mi proyecto personal de blog desarrollado para el curso de **Modelado de Software** en IES 9-018 "Gobernador Celso Jaque".

Este es un fork independiente del proyecto original [IES9018/proyecto-modelado-2025](https://github.com/IES9018/proyecto-modelado-2025) que ahora tiene su propia identidad, versionado y hoja de ruta.

---

## 🌟 Características Principales

### v1.0.0 (Release Actual)

- ✅ **Sistema de Casos de Uso** documentado con diagramas UML
- ✅ **Diagramas de Clases** para estructura de datos (Usuario, Articulo, Comentario)
- ✅ **Diagramas de Secuencia** para modelar interacciones entre objetos
- ✅ **Diagramas de Actividad** para flujos de negocio complejos
- ✅ **Arquitectura MVC** completamente documentada
- ✅ **Patrones de Diseño** implementados (Facade, Singleton)
- ✅ **Documentación profesional** por cada módulo

### Funcionalidades del Blog

- Sistema base de **CRUD de Artículos**
- Sistema de **Comentarios** para visitantes
- **Autenticación** de autores
- **Dashboard** para gestión de contenido

---

## 🏗️ Estructura del Proyecto

```
jesvqz1487_blog/
├── clase-1/                    # Casos de Uso y Git Básico
│   ├── README.md
│   ├── caso-uso-principal.jpg
│   ├── caso-uso-secundario.jpg
│   └── diagrama-completo.jpg
├── clase-2/                    # Diagramas UML (Clases, Secuencia, Actividad)
│   ├── README.md
│   └── diagrama-clases.jpg
├── clase-3/                    # Arquitectura MVC y Patrones de Diseño
│   ├── README.md
│   └── arquitectura-mvc.jpg
├── README.md                   # Este archivo
├── CHANGELOG.md                # Historial de cambios
├── LICENSE                     # Licencia MIT
└── .gitignore
```

---

## 📊 Diagramas y Documentación

### Clase 1: Introducción a UML y Casos de Uso
📍 [Ver carpeta](./clase-1/)

- Definición de actores principales: Autor, Visitante
- Casos de uso: Publicar Artículo, Leer Artículo, Comentar Artículo
- Diagramas visuales en JPG

### Clase 2: Diagramas de Clases, Secuencia y Actividad
📍 [Ver carpeta](./clase-2/)

- **Diagrama de Clases**: Estructura de Usuario, Articulo, Comentario con relaciones many-to-many
- **Diagrama de Secuencia**: Flujo de "Comentar Artículo" paso a paso
- **Diagrama de Actividad**: Proceso de "Publicar Artículo" con validaciones

### Clase 3: Arquitectura MVC y Patrones de Diseño
📍 [Ver carpeta](./clase-3/)

- **Arquitectura MVC**: Separación de Modelo, Vista, Controlador
- **Principios**: Alta Cohesión, Bajo Acoplamiento
- **Patrones**: Facade (SistemaBlog), Singleton (ServicioAutenticacion)
- Diagrama conceptual de la arquitectura completa

---

## 🔄 Flujo de Trabajo y Versionado

Este proyecto sigue **Semantic Versioning (SemVer)** para versiones:

```
v MAJOR . MINOR . PATCH
  |       |       |
  |       |       └─ Correcciones de bugs
  |       └─────────── Nuevas funcionalidades (compatible)
  └────────────────── Cambios que rompen compatibilidad
```

**Releases publicadas:**

- **v1.0.0** (2025-11-20): Versión inicial con Clases 1-3, diagramas UML, arquitectura MVC

**Roadmap futuro:**

- [ ] v1.1.0 — Sistema de categorías mejorado
- [ ] v1.2.0 — Sistema de etiquetas/tags
- [ ] v2.0.0 — Migración a arquitectura hexagonal

---

## 📚 Recursos y Referencias

- **[Keep a Changelog](https://keepachangelog.com/)**: Estándar de changelog utilizado
- **[Semantic Versioning](https://semver.org/)**: Esquema de versionado
- **[Diagrams.net](https://diagrams.net/)**: Herramienta para crear diagramas
- **[Mermaid](https://mermaid.live/)**: Visualización de diagramas en markdown

---

## 📄 Licencia

Este proyecto está bajo licencia **MIT**. Ver archivo [LICENSE](./LICENSE) para más detalles.

---

## 👤 Autor

**Jesica** — [@Jesica1487](https://github.com/Jesica1487)

Desarrollador de software en formación. Apasionado por arquitectura de software, UML y buenas prácticas de programación.

---

## 🙏 Agradecimientos

- **Profesor Paulo Alvarez** — Por el material pedagógico original
- **IES 9-018 "Gobernador Celso Jaque"** — Por el contexto educativo
- **[Proyecto Original](https://github.com/IES9018/proyecto-modelado-2025)** — Base de este fork