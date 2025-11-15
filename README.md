# Proyecto Modo Ojeador
# Proyecto: Modo Ojeador de Fútbol

Este repositorio contiene el desarrollo del proyecto **Modo Ojeador**, una aplicación destinada a buscar, filtrar y analizar jugadores de fútbol mediante una interfaz moderna y una API estructurada.

---

## 📌 Organización del repositorio

Usamos un flujo de trabajo basado en ramas para mantener un código limpio y organizado:

### 🟦 Ramas principales

- **main**  
  Rama estable. Solo recibe cambios cuando una funcionalidad está terminada y revisada.

- **dev**  
  Rama de desarrollo. Aquí se integran las diferentes funcionalidades antes de pasar a main.

### 🟩 Ramas de funcionalidad (feature)

Cada nueva funcionalidad se desarrolla en su propia rama:

- `feature/busqueda-jugadores`
- `feature/registro`
- `feature/favoritos`
- `feature/presupuesto`
- etc.

Estructura del nombre:

---

## 🧩 Convención de commits

Para mantener claridad en el historial:

- `feat:` para nuevas funcionalidades
- `fix:` para corregir errores
- `docs:` para documentación
- `refactor:` para cambios internos sin modificar funcionamiento

Ejemplos:


---

## 🏗️ Arquitectura del proyecto

El proyecto sigue un modelo cliente-servidor:

### 🔹 Frontend
- Framework: **React**
- Tareas principales:
  - Login y registro
  - Búsqueda de jugadores
  - Pantalla de detalle del jugador
  - Gestión de favoritos

### 🔹 Backend (API REST)
- Tecnología: **Node.js + Express**
- Funcionalidades:
  - Autenticación
  - Búsqueda de jugadores (con filtros)
  - Gestión de favoritos
  - Gestión de presupuesto

### 🔹 Base de datos
- **PostgreSQL/MySQL**
- Tablas principales:
  - USUARIO
  - JUGADOR
  - ESTADISTICA
  - FAVORITO
  - PRESUPUESTO

---

## 🛠️ Modo de trabajo (Scrum + Kanban)

Usamos un tablero digital (Jira) con estas columnas:

- Backlog  
- To Do  
- In Progress  
- In Review  
- Done  

### Roles del equipo:
- **Product Owner**
- **Scrum Master**
- **Equipo de desarrollo (Frontend / Backend / BD)**

---

## 📎 Enlaces del proyecto (se completarán más adelante)

- Repositorio GitHub:  
  https://github.com/xxxxx/modo-ojeador-futbol

- Tablero JIRA:  
  [pendiente]

- Documentación técnica:  
  [pendiente]

---



