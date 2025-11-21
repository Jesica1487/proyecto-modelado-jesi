# Clase 3: Refinando la Arquitectura - Principios, Patrones y Arquitectura MVC

## Descripción

En esta clase actuamos como **Arquitectos de Software**. Aprendemos a evaluar y mejorar la calidad de un diseño usando principios de **Alta Cohesión** y **Bajo Acoplamiento**, aplicamos **Patrones de Diseño** probados (Singleton, Facade), y estructuramos la aplicación siguiendo la arquitectura **Modelo-Vista-Controlador (MVC)**.

El objetivo no es añadir más funcionalidad, sino **mejorar la calidad** del diseño actual para que sea robusto, mantenible y escalable.

## 📊 Diagramas incluidos

### `arquitectura-mvc.jpg` / `arquitectura-mvc.drawio`
**Diagrama de Arquitectura MVC** que organiza el sistema en tres capas:

**Capa del Modelo** (Datos y Lógica de Negocio):
- `Usuario`: Representa los datos del usuario
- `Articulo`: Representa un artículo del blog
- `Comentario`: Representa un comentario
- `ServicioAutenticacion`: Gestiona login/logout (separado de Usuario para mayor cohesión)

**Capa de la Vista** (Interfaz de Usuario):
- `FormularioArticulo`: Formulario para crear/editar artículos
- `PaginaArticulo`: Página que muestra un artículo
- `ListaComentarios`: Componente que lista comentarios

**Capa del Controlador** (Intermediarios):
- `ArticuloController`: Recibe acciones del usuario, interactúa con Modelo, actualiza Vista
- `ComentarioController`: Gestiona las acciones de comentarios
- `SistemaBlog` (Facade): Oculta la complejidad, actúa como puerta de entrada principal

## 🔑 Conceptos Clave

### Cohesión (Alta)
Cada clase tiene **una única responsabilidad bien definida**:
- `Usuario` solo maneja datos de usuario
- `ServicioAutenticacion` solo maneja autenticación
- `ArticuloController` solo orquesta operaciones de artículos

### Acoplamiento (Bajo)
Las clases son independientes y comunicarse entre ellas sin conocer detalles internos:
- Los controladores usan interfaces/abstracciones, no implementaciones concretas
- El Modelo no depende de la Vista
- La Vista no depende del Modelo directamente

### Patrones de Diseño Aplicados

#### Patrón Facade (Fachada)
- **Clase**: `SistemaBlog`
- **Propósito**: Proporcionar una interfaz simplificada a un conjunto de subsistemas complejos
- **Ventaja**: Reduce acoplamiento entre cliente y subsistemas internos

#### Patrón Singleton
- Podría aplicarse a `ServicioAutenticacion` para garantizar una única instancia en la aplicación
- Útil para servicios globales

## 🏗️ Arquitectura MVC Explicada

| Capa | Responsabilidad | Ejemplo |
|------|-----------------|---------|
| **Modelo** | Datos y lógica de negocio | Usuario, Articulo, Comentario |
| **Vista** | Interfaz de usuario | Páginas HTML, componentes visuales |
| **Controlador** | Orquesta Modelo y Vista | ArticuloController, ComentarioController |

**Flujo de una acción en MVC**:
1. Usuario interactúa con la **Vista** (ej: llena formulario y presiona "Guardar")
2. La **Vista** envía la acción al **Controlador**
3. El **Controlador** procesa la acción, interactúa con el **Modelo**
4. El **Modelo** actualiza datos/lógica
5. El **Controlador** actualiza la **Vista** con nuevos datos
6. El usuario ve los cambios

## 🛠️ Herramientas Utilizadas

- **Diagrams.net**: Para crear diagrama de arquitectura
- **Mermaid** (opcional): Para visualizar diagramas conceptuales

## 📚 Recursos

- [Design Patterns - Gang of Four](https://en.wikipedia.org/wiki/Design_Patterns)
- [MVC Pattern Explained](https://developer.mozilla.org/en-US/docs/Glossary/MVC)
- [SOLID Principles](https://en.wikipedia.org/wiki/SOLID)

## ✅ Mejoras Esperadas del Diseño

- ✅ Mayor cohesión: Cada clase tiene una única responsabilidad
- ✅ Menor acoplamiento: Las clases son más independientes
- ✅ Mejor mantenibilidad: Más fácil de modificar y extender
- ✅ Escalabilidad: Estructura preparada para crecer
- ✅ Reutilización: Componentes pueden usarse en otros proyectos

---

**Autora**: Jesica (@Jesica1487)  
**Fecha**: Noviembre 2025
