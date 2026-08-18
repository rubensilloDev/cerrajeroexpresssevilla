# `:root` de la web

---

## 🎨 Colores

| Variable / Nombre | Valor HEX / Especificación |
| :--- | :--- |
| **Color Accent Secundario** | `#F04E23` (Opacidad: 5%) |
| **Color Fondo Cards** | `#F5F3F6` |

### Color Scheme 1
| Variable | Valor HEX |
| :--- | :--- |
| **Background** | `#FFFFFF` |
| **Primary** | `#0B1F3A` |
| **Color Secundario** | `#13315C` |
| **Normal Text** | `#E6E6E6` |
| **Primary Text** | `#0F1720` |
| **Accent** | `#F04E23` |
| **Hover Accent** | `#D63E17` |

---

## 🔤 Tipografías

### Tamaños
| Elemento | Tamaño |
| :--- | :--- |
| **H1** | `96px` |
| **H2** | `64px` |
| **H3** | `36px` |
| **H4** | `32px` |
| **Normal Text** | `16px` |
| **Large Text** | `18px` |

### Fuentes
* **Encabezados:** Expose
* **Todo lo demás:** Inter

---

## 📐 Estilos

Los `H1` pueden variar según la página, pero los `H2` tienen el siguiente diseño:

* **Estilos `H2`:**  
  Color primary de la fuente, en “black”, altura de línea de un 85% y -1.8px de espaciado de letras (y según la sección estará alineada a la izquierda, derecha, centro…).

* **Estilos de los párrafos (general, algunos pueden variar):**  
  Color Secundario a un 70% de opacidad, y lo demás se deja por defecto.

---

## 🧱 Componentes

### Hero
Contenedor general que ocupa un 80% de la pantalla a lo ancho (fondo: `#0B1F3A`), y está centrado horizontalmente. Luego otro div dentro de él que es donde está el contenido:
> **Logo - Inicio - Servicios - Sobre Nosotros - Contacto - CTA Naranja (Llamar Ahora)**

Los navegadores (inicio, servicios…) son de color blanco.

---

## 🔘 Botones

* **Botón 1 - Btn Principal Naranja:**  
  Div en el que dentro de él se encuentra un texto de color `#0B1F3A`, cuyo fondo del div es `#F04E23` y el trazo de 1px es del color `#D63E17` con una sombra de color `#D63E17` la cual es X: 0, Y: 0 y desenfoque: 10px. El botón tiene un padding de 20px arriba y abajo y 30px a izquierda y derecha.

* **Botón 2 - Btn Secundario Naranja:**  
  Igual que el Botón 1 pero sin fondo el div; lo demás todo igual.

* **Botón 3 - Btn Terciario Naranja:**  
  Igual que el Botón 2, pero con el texto del color `#F04E23`. Además, el botón está compuesto de un texto + flecha hacia la derecha.

* **Botón 4 - Btn Principal Azul Marino:**  
  Igual que el Botón 1, pero el fondo del botón es de color `#0B1F3A`, el texto de color blanco, el trazo de color `#13315C` y el color de la sombra igual que el color del trazo. El resto es igual al Botón 1.

---

## ❓ FAQs

* Encabezados del mismo estilo que los `H2` mencionados anteriormente.
* Un contenedor general del contenido en el que dentro tiene 2 contenedores más (uno el encabezado y otro con todas me las preguntas).
* El contenedor de las preguntas tiene un ancho de un 70% de la pantalla y cada tarjeta es un div compuesto de 2 filas en flex.

**Cada tarjeta:**  
La primera fila contiene la pregunta en Inter, pero lo demás igual a los estilos de los `H2` pero con un tamaño de 18px y a la derecha un icono de una flecha hacia abajo para abrir la pregunta. La fila de abajo es un párrafo el cual tiene los mismos estilos que el estilo del párrafo en general. El fondo de la tarjeta es de color `#F5F3F6` y un borde de 2px de color **Accent** con un radio de 20px.
