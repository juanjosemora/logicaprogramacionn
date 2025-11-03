# 🧠 Módulo de Interacción y Reportes — Juan José Bocanegra Mora

## 👨‍💻 Autor
**Juan José Bocanegra Mora**  
Programa: Técnico en Programación de Software — SENA  

---

## 📘 Descripción General
Este módulo forma parte del proyecto grupal **“Sistema de Gestión de Tareas con Roles (Jefe/Empleado)”**, desarrollado para el área de Procesos Estratégicos.

Mi responsabilidad dentro del equipo fue implementar el **menú de interacción en consola** y el **módulo de reportes**.  
Estos componentes permiten que el usuario (según su rol) pueda navegar por las opciones del sistema y que, al finalizar, se genere un reporte automático en formato **CSV** con todas las tareas registradas.

---

## 🧩 Archivos Entregados

| Archivo | Descripción |
|----------|--------------|
| **main.py** | Contiene el menú principal de interacción con el usuario. Permite ingresar como jefe o empleado, acceder a las funciones del sistema, manejar errores y mostrar mensajes informativos. |
| **report.py** | Genera un archivo `reporte_tareas.csv` al finalizar el programa. Exporta las tareas registradas (nombre, responsable, estado, fecha, hora, etc.) en formato legible. |

---

## ⚙️ Funcionalidades Principales

### `main.py`
- Muestra el menú principal con opciones interactivas.
- Permite iniciar sesión como **Jefe** o **Empleado**.
- Accede a las funciones de gestión de usuarios y tareas.
- Valida entradas erróneas (manejo de excepciones).
- Llama al módulo `report.py` al salir del sistema.

### `report.py`
- Genera automáticamente un archivo CSV con todas las tareas.
- Incluye campos: **ID, Nombre, Responsable, Fecha, Estado**.
- Guarda el archivo dentro de la carpeta `datos/`.

---

## 🧾 Ejemplo de Ejecución

```bash
> python main.py

=== Sistema de Gestión de Tareas ===
1. Iniciar sesión como Jefe
2. Iniciar sesión como Empleado
3. Salir

Seleccione una opción: 1
