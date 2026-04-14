# 🧩 Widgets App

Una colección de widgets de escritorio para Windows, diseñados para ser simples, accesibles y siempre visibles.

---

## 📌 Descripción

**Widgets App** es un proyecto personal desarrollado con Python y Qt (PyQt6 / PySide6), cuyo objetivo es crear un conjunto de widgets de escritorio útiles para el día a día.

La idea nace de una necesidad real: tener herramientas prácticas siempre a la mano.
Desde seguimiento de hábitos hasta listas de tareas, estos widgets buscan integrarse de forma natural en el flujo diario frente a la computadora.

Muchas veces usamos herramientas físicas o aplicaciones complejas que no siempre están disponibles cuando las necesitamos. Este proyecto busca solucionar eso llevando todo a un lugar central:

> 💻 Tu computadora — la herramienta que usas todos los días para estudiar, trabajar o incluso relajarte.

---

## 🎯 Objetivos

* Crear widgets ligeros y funcionales
* Mantener una interfaz simple y atractiva
* Mejorar la productividad sin agregar complejidad
* Centralizar herramientas de uso diario
* Construir una base escalable para nuevos widgets

---

## 🧱 Estructura del proyecto

```
widgets-app/
├── main.py              # Punto de entrada
├── launcher.py          # Launcher (system tray + menú)
├── core/                # Infraestructura base
│   ├── base_widget.py
│   ├── database.py
│   ├── theme.py
│   └── widget_manager.py
├── widgets/             # Widgets independientes
│   ├── habits/
│   ├── todo/
│   └── pomodoro/
├── assets/              # Iconos y recursos
├── data/                # Base de datos (SQLite)
│   └── app.db
```

---

## ⚙️ Tecnologías

* **Python**
* **PyQt6 / PySide6**
* **SQLite**
* **QSS (Qt Style Sheets)**

---

## 🧩 Widgets planeados

* ✅ To-Do List
* ⏳ Pomodoro Timer
* 🔄 Habit Tracker (rueda de hábitos)
* 📌 Notas rápidas
* ⏰ Reloj / utilidades básicas

---

## 🚀 Estado del proyecto

🛠️ En desarrollo

Actualmente se está trabajando en:

* estructura base del sistema
* arquitectura de widgets
* primeros widgets funcionales

---

## 🔮 Futuro

* Sistema de launcher con icono en bandeja
* Personalización de widgets
* Guardado de posiciones y estado
* Soporte para nuevos widgets modulares
* Animaciones y mejoras visuales


---

## 📄 Licencia

Por definir.

---

## 👨‍💻 Autor

Proyecto desarrollado como parte del crecimiento personal y profesional en el área de computación.

---

> ✨ *La idea no es solo crear widgets, sino construir herramientas que realmente quieras usar todos los días.*
