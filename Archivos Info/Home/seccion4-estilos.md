## 💳 Sección 4 (Tarifas y precios)

### 1. Estructura general de la sección
La sección se compone de un contenedor principal con 3 divs principales en una sola columna:
* **El primer div** es la cabecera.
* **El segundo div** es la agrupación de tarjetas de precios.
* **El tercer div** es un aviso legal.

### 2. Estructura interna de cada div principal

#### **El primer div (Encabezado)**
Contiene encabezado, texto y botones organizados en flex en columna (3 filas).

#### **El segundo div (Tarjetas de precios)**
Contiene tres divs (tarjetas) organizados en flex en fila:
* **Tarjetas izquierda y derecha:** Color de fondo “Color Fondo Cards”, el borde de color `#C4C6CE` y un border-radius de 20px.
* **Tarjeta del medio (Destacada):** Border-radius igual que las anteriores, color de fondo `#F04E23` al 15% de opacidad y borde de 2px con el color de “Hover Accent”.

**Estructura interna en flex en columna de cada tarjeta:**
* **Fila 1:** Pre-encabezado (nombre del servicio). Mismos estilos que todos los encabezados pero tamaño de 20px.
* **Fila 2:** Encabezado precio: Mismo estilo que el anterior pero con un tamaño a 36px.
* **Fila 3:** Div contenedor con varias filas de texto (lista de características con icono de tick + característica) organizadas en columna. Color de `#44474D`; el icono tiene un fondo totalmente redondo transparente y el color del borde y del propio icono del color del “Accent”.
* **Fila 4:** Botón de acción (las tarjetas de la izquierda y derecha usan el estilo del botón “Btn principal Azul Marino” y la del medio el estilo del “Btn Principal Naranja”).

#### **El tercer div (Aviso inferior)**
Contiene un div con un icono y un texto largo, organizados en flex en fila.
