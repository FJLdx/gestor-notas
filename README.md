# Gestor de Notas en Python

Este es un pequeño **gestor de notas en Python** que permite agregar, leer, buscar y eliminar notas. Se almacenan en un archivo **pickle** (`notas.pkl`) para persistencia de datos.

## 📌 Características
- Agregar notas fácilmente.
- Leer todas las notas almacenadas.
- Buscar notas por contenido.
- Eliminar notas por índice.

## 📂 Estructura del Proyecto
```
/Notas
│── gestor_notas.py  # Clase para manejar las notas
│── notas.py         # Definición de la clase Nota
│── main.py         # Interfaz principal en consola
│── notas.pkl       # Archivo donde se almacenan las notas (generado automáticamente)
```

## 🚀 Instalación y Uso

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/FJLdx/gestor-notas.git
cd gestor-notas
```

### 2️⃣ Ejecutar el programa
```bash
python3 main.py
```

## 🛠️ Ejemplo de Uso

```bash
-----------------
MENU
-----------------
1. Agregar una nota
2. Leer todas las notas
3. Buscar por una nota
4. Eliminar una nota
5. Salir

[+] Escoge una opcion: 1
[+] Contenido de la nota: Comprar café ☕
```

## 🎯 Mejoras Futuras
- Exportar notas a formato TXT o JSON.
- Interfaz gráfica con Tkinter o PyQt.
- Autoguardado en tiempo real.

---

📌 **Autor:** [FJLdx](https://github.com/FJLdx)  
📅 **Fecha:** Febrero 2025  
🔗 **Repositorio:** [GitHub](https://github.com/FJLdx/gestor-notas)

