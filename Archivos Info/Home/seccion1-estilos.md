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
