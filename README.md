# Simulador 3D: Potencial y Campo Eléctrico de un Disco Cargado

Simulador 3D interactivo de electrostática desarrollado con **Three.js**, **KaTeX** y **Chart.js**[cite: 5]. Modifica carga, radio y sensor en tiempo real para visualizar campos, potenciales y anillos diferenciales de un disco cargado[cite: 5]. Incluye gráficas dinámicas de $V(x)$ y exportación de datos a CSV para análisis académico[cite: 5].

---

## 🚀 Características Principales

* **Visualización 3D Interactiva:** Renderizado en tiempo real de un disco cargado, líneas de campo con gradiente de opacidad y un sensor móvil sobre el eje central.
* **Desglose Diferencial ($dr, dq$):** Representación visual de anillos concéntricos para comprender el cálculo integral de la distribución de carga.
* **Gráfica Dinámica $V(x)$:** Panel flotante independiente con Chart.js que grafica el potencial eléctrico en el intervalo $0 \le x \le 2R$ junto con la posición exacta del punto evaluado.
* **Fórmulas en Tiempo Real:** Actualización matemática automatizada impulsada por KaTeX para la densidad superficial ($\sigma$), el potencial ($V$) y el campo ($E$).
* **Exportación de Datos:** Capacidad de exportar los pares de datos $(x, V(x))$ a formato CSV para reportes y prácticas de laboratorio.

---

## 🛠️ Tecnologías Utilizadas

* **Three.js** (Motor de gráficos 3D y renderizado WebGL)
* **Chart.js** (Generación de gráficas interactivas)
* **KaTeX** (Renderizado tipográfico de fórmulas matemáticas)
* **JavaScript / HTML5 / CSS3** (Lógica y diseño de interfaz flotante)

---

## 📖 Instrucciones de Uso

1. **Clonar o descargar** el repositorio en tu computadora, asegurándote de que el archivo principal.
2. **Abrir el archivo** en cualquier navegador web moderno (se recomienda Google Chrome, Brave o Firefox). *(Nota: No requiere instalación de servidores locales ni dependencias complejas de Node.js).*
3. **Interactuar con los controles:**
   * **Controles 3D:** Clic izquierdo y arrastrar para orbitar alrededor del sistema; rueda del ratón para hacer zoom.
   * **Paneles flotantes:** Puedes arrastrar los paneles de la interfaz desde sus cabeceras para acomodarlos a tu gusto.
   * **Sliders:** Modifica el radio del disco ($R$), la carga total ($Q$) y la distancia del sensor ($x$) para ver los cambios instantáneos en la simulación y en la gráfica superior derecha.

---

## 👨‍💻 Autor

Proyecto desarrollado con fines académicos y de divulgación científica para el estudio del electromagnetismo.
