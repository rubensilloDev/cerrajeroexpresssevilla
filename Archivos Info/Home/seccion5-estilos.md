## 🛡️ Sección 5 (Garantías y servicios adicionales)

### 1. Estructura general de la sección
La sección se compone de un contenedor principal con 2 divs principales organizados en flex en fila (dos columnas):
* El **div izquierdo** contiene el texto y los botones.
* El **div derecho** contiene una lista de tres características en columna.

### 2. Estructura interna de cada div principal

#### **El primer div (Columna izquierda)**
Contiene:
* Un encabezado (`h2`).
* Un texto.
* Un div con botones:
  * El de la izquierda pone **“Llamar Ahora”** con los estilos del botón “Btn Principal Naranja”.
  * El de la derecha pone **“Pedir Presupuesto”** con los estilos del “Btn Secundario Naranja”.

Organizados en flex en columna con 3 filas.

#### **El segundo div (Columna derecha - Características)**
Contiene tres bloques de características organizados verticalmente en flex en columna.

Cada bloque de característica está organizado en flex en fila:
* **Estilos de cada tarjeta:** Fondo `#F5F3F6`, trazo de 2px de color `#C4C6CE`, border-radius de 20px.
* **Hijo 1 (izquierda):** Div que contiene un icono (mismos estilos que los iconos de la sección 2).
* **Hijo 2 (derecha):** Div con texto organizado en flex en columna, compuesto por un encabezado (mismos estilos que un `h2` pero a 20px de tamaño) y un texto.
