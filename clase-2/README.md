# Clase 2: Construyendo los Cimientos - Diagramas de Clases, Secuencia y Actividad

## Descripción

En esta clase aprendemos a traducir los requisitos funcionales del sistema en una estructura de software mediante **Diagramas de Clases**, modelamos la **interacción entre objetos** con **Diagramas de Secuencia**, y describimos **flujos de trabajo complejos** usando **Diagramas de Actividad**.

La funcionalidad central es la adición del **sistema de comentarios** al blog: visitantes pueden dejar comentarios en artículos, y autores pueden verlos.

## 📊 Diagramas incluidos

### `diagrama-clases.jpg` / `diagrama-clases.drawio`
**Diagrama de Clases UML** que define la estructura del sistema:
- `Usuario`: Entidad con id, nombre, email, password. Métodos: login(), logout()
- `Articulo`: Entidad con id, título, contenido, fechaPublicación. Métodos: publicar(), agregarComentario()
- `Comentario`: Entidad con id, texto, fecha, autor
- **Relaciones**:
  - Un Usuario escribe 1 o más Artículos (1..*)
  - Un Artículo tiene 0 o más Comentarios (*)
  - Un Usuario (Visitante) escribe 0 o más Comentarios (*)

## 🔄 Casos de Uso Documentados

### CU02: Comentar Artículo
- **Actor Principal**: Visitante
- **Descripción**: El visitante puede dejar un comentario en un artículo publicado
- **Flujo Principal**:
  1. El Visitante ve un artículo y presiona "Dejar Comentario"
  2. El sistema muestra un formulario
  3. El Visitante escribe el comentario y presiona "Enviar"
  4. El ComentarioController recibe los datos
  5. Se crea un nuevo objeto Comentario
  6. El Comentario se guarda en base de datos
  7. Se muestra confirmación al Visitante

## 🛠️ Herramientas Utilizadas

- **Diagrams.net**: Para crear los diagramas UML
- **Mermaid** (opcional): Para visualizar diagramas en markdown

## 📚 Conceptos Clave

- **Diagrama de Clases**: Define la estructura estática del sistema (entidades, atributos, métodos, relaciones)
- **Diagrama de Secuencia**: Muestra la interacción dinámica entre objetos (paso a paso)
- **Diagrama de Actividad**: Modela flujos de trabajo con decisiones y bifurcaciones
- **Multiplicidad**: Define cuántos objetos de una clase se relacionan con otra (1, *, 1..*, 0..1)

## 🔗 Referencias

- [Keep a Changelog](https://keepachangelog.com/)
- [Mermaid Diagrams](https://mermaid.live/)
- [Diagrams.net](https://diagrams.net/)

---

**Autora**: Jesica (@Jesica1487)  
**Fecha**: Noviembre 2025
