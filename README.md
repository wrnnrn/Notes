# Notes

# 📝 App de Notas con Django + REST API

Aplicación web de notas tipo Google Keep, con backend en Django y frontend en HTML/CSS/JS puro. Los datos se guardan en servidor (SQLite por defecto) y se sirven vía API REST en `localhost:8000`.

---

## 🎯 Objetivo

Construir una app donde el usuario pueda:
- Crear notas con título, contenido y color
- Editar y eliminar notas
- Fijar notas importantes (aparecen primero)
- Persistencia real en servidor (no `localStorage`)

---

## 🧱 Stack tecnológico

| Capa | Tecnología |
|------|-----------|
| Backend | Django 5 + Django REST Framework |
| Base de datos | SQLite (desarrollo) |
| Frontend | HTML + CSS + JavaScript (fetch API) |
| CORS | django-cors-headers |
| Servidor | Django runserver (`localhost:8000`) |

---
