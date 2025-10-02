# reto3_DataBase_monicaAlvarenga
Reto3: Database de biblioteca escolar

# Biblioteca C++ - Proyecto Reto3

## Descripción
Este proyecto es un sistema básico de biblioteca en C++.  
Permite:
- Agregar libros y autores.
- Agregar estudiantes.
- Prestar y devolver libros.
- Guardar y cargar los datos en archivos `.txt` (CSV simple).

Los autores se almacenan solo una vez y los libros los referencian mediante un ID.

---

## Archivos del proyecto
- `main.cpp` → Código principal.
- `models.h` → Estructuras (`struct`) para libros, autores, estudiantes y préstamos.
- `diagrama_ER.png` → Diagrama Entidad-Relación.
- `normalizacion.pdf` → Documento de normalización.
- `README.md` → Este archivo.

---

## Cómo compilar y ejecutar

### Usando VSCode
1. Abre la carpeta del proyecto en VSCode.
2. Asegurarse de tener instalado **g++**.
3. Presiona `Ctrl+Shift+B` para compilar `main.cpp` y generar `main.exe`.
4. Ejecuta en el terminal integrado:
   ```powershell
   .\main.exe
