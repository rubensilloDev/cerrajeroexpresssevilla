## ⚡ Sección 2 (Características principales / Beneficios)

### 1. Estructura general de la sección
La sección se compone de un contenedor principal con 2 divs principales en una sola columna.
* El **div superior** contiene el título, un texto y los botones de acción.
* El **div inferior** contiene una agrupación de tres tarjetas de información en una fila.

### 2. Estructura interna de cada div principal

#### **El primer div (Texto y botones)**
Contiene:
* **Un encabezado:** “Cerrajero en Sevilla: rápido, sin destrozos y con precio cerrado”
* **Un texto:** “Cuando te quedas tirado en la puerta de tu casa, lo último que necesitas son sorpresas. Por eso trabajamos con tres compromisos claros, desde el primer minuto hasta el último tornillo.”
* **Un contenedor con 2 botones:** 
  * **Btn Izq** (Estilos Botón 1: “Llamar Ahora”)
  * **Btn Derecha** (Estilos Botón 2: “Pedir Presupuesto”)

Organizados en flex en columna con 3 filas:
* **Fila 1:** Encabezado.
* **Fila 2:** Texto.
* **Fila 3:** Div con 2 botones (flex en fila).

#### **El segundo div (Bloque de columnas / Tarjetas)**
Contiene:
* Tres divs que actúan como tarjetas organizados en flex en fila.
* Las 3 con los mismos estilos de tarjeta (y también de todos los elementos de dentro).
* **Estilo de la tarjeta solo:** fondo color “Color Fondo Cards”, con un borde de 2px de color “Hover Accent”, y un border-radius de 16px.

Cada una de las tres tarjetas sigue la misma estructura interna organizada en flex en columna, alineado a la izquierda de la tarjeta:
* **Fila 1:** Div que contiene un icono (estilos del icono: ancho y altura de 56px, fondo `#F04E23`, sin borde, border-radius 20px, y un icono del color “Accent”).
* **Fila 2:** Encabezado secundario (estilos: color “primary”, black, 26px de tamaño).
* **Fila 3:** Texto (color: Color Secundario al 80% de opacidad).
* **Fila 4:** Botón (estilos del botón del componente “**Botón 3 - Btn Terciario Naranja:**”).
