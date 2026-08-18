# Estilos de la Home

---

## 🎨 Sección Hero (Página de inicio - Cabecera principal)

### 1. Estructura general de la sección
La sección se compone de un contenedor principal en el cual el fondo es un degradado de arriba hacia abajo, que va desde el color **“Accent”** (arriba) hasta el blanco (abajo). El color de arriba está ocupando solo el 30% de todo el contenedor (blanco).

Dentro hay 2 divs principales organizados en una sola columna (uno arriba y otro abajo).

El contenedor utiliza flex en dirección columna para apilar los bloques.

### 2. Estructura interna de cada div principal

#### **Div Superior (Texto y acciones)**
Contiene:
* **Un encabezado:** “Cerrajero Sevilla 24 Horas | Llegada en 20–30 minutos a cualquier zona de Sevilla”
* **Un texto:** “Especialistas en apertura de puertas sin daños, cambio de cerraduras de alta seguridad y urgencias 24h. Servicio profesional, rápido y económico en toda la capital.”
* **Un contenedor con 2 botones:** 
  * **Btn Izq** (Estilos Botón 1: “Llamar Ahora”)
  * **Btn Derecha** (Estilos Botón 2: “Pedir Presupuesto”)

Estos elementos están organizados en flex en columna con 3 filas:
* **Fila 1:** Encabezado.
* **Fila 2:** Texto.
* **Fila 3:** Div contenedor con 2 botones (organizados en flex en fila dentro de este div).

#### **Div Inferior (Composición visual)**
Contiene:
* **Un contenedor de imágenes.**
* Dentro de él hay 3 imágenes las cuales tienen una proporción de 3:4, y hay una principal (la del medio) que es más grande que las otras dos. Las cuales, las otras 2: una de ellas está en la esquina superior derecha de la principal (por detrás de la principal) y la otra está en la esquina inferior izquierda de la principal (por detrás de la principal).

---

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

---

## 🛠️ Sección 3 (Servicios ofrecidos)

### 1. Estructura general de la sección
La sección se compone de un contenedor principal. Dentro hay 2 divs principales en una sola columna:
* El primero contiene el título, un texto y los botones.
* El segundo contiene una lista de ítems de servicio.

### 2. Estructura interna de cada div principal

#### **El primer div (Encabezado centrado horizontalmente)**
Contiene:
* **Un encabezado:** De color “Primary”, está centrado horizontalmente.
* **Un texto:** De color “Color Secundario” al 80% de opacidad.
* **Un div con dos botones:** Mismos estilos que la anterior sección y mismo texto.

Organizados en flex en columna:
* **Fila 1:** Encabezado.
* **Fila 2:** Div con un texto.
* **Fila 3:** Div con 2 botones (flex en fila).

#### **El segundo div (Lista de servicios)**
Contiene múltiples divs de ítems de servicio organizados verticalmente en flex en columna.

Cada ítem de servicio contiene internamente 2 divs principales organizados en flex en fila:
* **Diseño de los divs en general:** Sin color de fondo, 20px de padding arriba y abajo y a la izquierda y derecha, un borde de 2px de color “Color Secundario” y un border-radius de 20px.
* **Div hijo 1 (izquierda):** Contiene una imagen. Todas las imágenes de los divs tienen un border-radius de 16px.
* **Div hijo 2 (derecha):** Contiene un bloque de texto y botones, organizado en flex en columna. Su estructura interna es:
  * **Fila 1:** Encabezado de categoría (en mayúsculas, 14px de tamaño, color “Accent”, un espaciado de letras un poco mayor al texto normal).
  * **Fila 2:** Encabezado principal (igual que los encabezados anteriores solo que de un tamaño de 48px).
  * **Fila 3:** Texto descriptivo (mismo color que el texto definido al principio de esta sección).
  * **Fila 4:** Div con 2 botones (organizados en flex en fila): el de la izquierda con los estilos del botón del componente “Btn principal Azul Marino” y el de la derecha con estilos del “Btn Terciario Naranja” solo que los colores del borde son del color “Color Secundario”, su sombra igual y el texto del color “Primary”; lo demás es igual, solo cambian los colores.

> ℹ️ Cada div tiene el mismo estilo, tanto en el contenido como en la tarjeta en sí, solo cambia la estructura en ellos: es decir, el primer ítem/div del primer servicio tiene la imagen a la izquierda y el contenido a la derecha, el segundo ítem/div tiene el contenido a la izquierda y la imagen a la derecha y así sucesivamente.

#### **Contenido de cada servicio:**

##### **Servicio 1**
* **Etiqueta:** APERTURA DE PUERTAS
* **Título:** Apertura de puertas de urgencia sin daños
* **Texto:** El servicio más solicitado. Si te has dejado las llaves dentro o las has perdido, abrimos tu puerta de día, de noche o en festivo, priorizando siempre el no dañar la cerradura.
* **Botones:** Llamar Ahora | Más Detalles →

##### **Servicio 2**
* **Etiqueta:** CAMBIO DE CERRADURAS
* **Título:** Cambio y sustitución de cerraduras
* **Texto:** Ya sea porque te han robado las llaves, quieres reforzar la seguridad o simplemente el bombín está gastado, instalamos cerraduras básicas, de seguridad media y de alta seguridad, adaptadas a tu puerta, necesidad y a tu presupuesto.
* **Botones:** Llamar Ahora | Más Detalles →

##### **Servicio 3**
* **Etiqueta:** PRECIOS CLAROS
* **Título:** Apertura de puertas blindadas y acorazadas
* **Texto:** Las puertas blindadas requieren herramientas y experiencia específicas. Abrimos este tipo de puertas sin dañar el mecanismo de seguridad, y si hace falta sustituir el bombín, te ofrecemos piezas de alta seguridad con garantía oficial.
* **Botones:** Llamar Ahora | Más Detalles →

##### **Servicio 4**
* **Etiqueta:** CAMBIO DE CERRADURAS
* **Título:** Apertura de vehículos
* **Texto:** Llaves dentro del coche o perdidas en la calle. Abrimos turismos estándar y vehículos de gama alta sin dañar la carrocería ni el sistema de cierre.
* **Botones:** Llamar Ahora | Más Detalles →

##### **Servicio 5**
* **Etiqueta:** PRECIOS CLAROS
* **Título:** Asesoramiento en seguridad residencial
* **Texto:** Si quieres reforzar la seguridad de tu vivienda, hacemos un diagnóstico in situ y te recomendamos las mejores opciones para tu puerta: desde cerraduras de mayor resistencia hasta refuerzos adicionales.
* **Botones:** Llamar Ahora | Más Detalles →

---

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

---

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

---

## 🚀 Sección final CTA

### Estructura general
Sección general con un div dentro con el contenido de la sección. El contenido de la sección se divide en un flex de dos filas y 1 columna:
* **Fila de arriba:** Contiene un encabezado a la izquierda y un párrafo a la derecha.
* **Fila de abajo:** Se compone de un encabezado a la izquierda y un div a la derecha con 2 botones.

### Estilos del contenido de la sección:
* Imagen de fondo con un div en lo alto con un color degradado de izquierda a derecha yendo del color **“Accent”** a **Negro** (derecha) (el div del degradado con los 2 colores al 80%).

#### **Fila 1:**
* Encabezado con los mismos estilos generales del `h2`.
* A la derecha, el párrafo alineado a la derecha de color `#E6E6E6` al 85%, en black a 20px y -1.5px de espacio entre líneas.

#### **Fila 2:**
* En flex con space between.
* Fondo de color primary.
* Texto de estilos a un `h2`, pero es un `p` normal y de color Accent en 36px de tamaño.
* Los dos botones iguales que la sección anterior.
