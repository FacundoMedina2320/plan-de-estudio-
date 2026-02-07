# 🎓 Planificador de Carrera Universitaria (Web)

Aplicación web estática para **visualizar, planificar y hacer seguimiento** del avance de una carrera universitaria, con soporte para:

- materias por cuatrimestre  
- correlativas (prerrequisitos)  
- estados (pendiente / cursando / aprobada)  
- **árbol gráfico de dependencias**  
- manejo inteligente de **materias electivas**  

El objetivo es reemplazar planillas, PDFs o listas desordenadas por una **vista clara, interactiva y visual** del plan de estudios.

---

## 🚀 Características principales

- 📋 Vista en **lista** con filtros y búsqueda
- 🌳 Vista **gráfica tipo árbol** (materias + correlativas)
- 🔓 Cálculo automático de materias habilitadas
- 🎓 Sistema de **electivas** (solo 2 necesarias)
- 💾 Progreso guardado en el navegador (localStorage)
- 📦 Importación desde archivos JSON
- 🌐 Compatible con **GitHub Pages**
- ❌ Sin backend, sin base de datos, sin dependencias

---

## 🗂️ Estructura del proyecto

```text
/
├── index.html     # Aplicación web (HTML + CSS + JS)
├── plan.json      # Plan de estudios (materias y correlativas)
├── state.json     # Estado inicial de materias (opcional)
└── README.md      # Documentación
