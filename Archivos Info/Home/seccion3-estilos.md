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
