# Análisis de ventas - Superstore 🏬

Proyecto de análisis exploratorio de datos (EDA) sobre un conjunto de datos tipo **Superstore**, con información de pedidos, clientes, productos y ventas. El objetivo es practicar análisis de datos con Python y obtener insights sencillos que puedan servir como ejemplo en un portfolio.
Este proyecto se hizo en conjunto con tres personas como simulacro de trabajo en equipo para un entorno real.

---

## Objetivos del análisis

- Explorar las ventas y beneficios por:
  - Categoría y subcategoría de producto.
  - Segmento de cliente.
  - Región / país / ciudad (según columnas disponibles).
- Identificar:
  - Productos o categorías más rentables.
  - Zonas con mejor y peor rendimiento.
  - Posibles patrones en descuentos y beneficios.
- Practicar visualización, limpieza básica de datos y primeras aproximaciones a modelos sencillos.

---

## Conjunto de datos

- **Fuente**: Dataset tipo *Superstore* (ventas de una tienda minorista).
- **Formato**: Archivo `CSV` incluido en el repositorio.
- **Filas**: Cada fila representa un pedido o una línea de pedido.
- **Columnas típicas** (pueden variar según la versión del dataset):
  - Identificadores: `Order ID`, `Customer ID`, `Product ID`.
  - Información de cliente: `Customer Name`, `Segment`, `Country`, `Region`, `City`.
  - Información de producto: `Category`, `Sub-Category`, `Product Name`.
  - Fechas: `Order Date`, `Ship Date`.
  - Métricas: `Sales`, `Quantity`, `Discount`, `Profit`.

Se hace una identificación de variables, revisión de tipos de datos y tratamiento básico de valores faltantes si es necesario.

---

## Herramientas y librerías utilizadas

El análisis está hecho en Python, usando cosas como:

- `pandas` para carga y manipulación de datos.
- `numpy` para operaciones numéricas.
- Librerías de visualización:
  - `matplotlib`
  - `seaborn`
- Opcionalmente:
  - Algún modelo sencillo (por ejemplo, árbol de decisión o RandomForest) para explorar patrones muy básicos en el comportamiento de ventas/beneficios.

También se incluyen:

- **Gráficos**:
  - Histogramas y distribuciones.
  - Gráficos de barras por categoría/segmento.
  - Boxplots para analizar la variabilidad de ventas/beneficio.
  - Scatter plots para ver relaciones entre variables (por ejemplo, descuento vs beneficio).
- **Notas y comentarios** en el notebook para explicar cada paso.

---

## Estructura del proyecto

Este es el ejemplo de la estructura de archivos:

```text
Superstore-Analysis/
├── data/
│   └── superstore.csv
├── notebooks/
│   └── superstore_analysis.ipynb
└── README.md
```

- `data/superstore.csv`: aquí estarían los datos en bruto.
- `notebooks/superstore_analysis.ipynb`: Notebook principal con todo el análisis paso a paso.
- `README.md`: Este archivo, con la explicación del proyecto como bien estas leyendo <3

---

## Cómo puedes ejecutar el análisis

1. Clonar este repositorio:

   ```bash
   git clone https://github.com/NoeliaTJ/ControlStock/
   cd ControlStock
   ```

2. Crear y activar un entorno virtual (opcional, pero recomendado):

   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS / Linux
   # .\venv\Scripts\activate  # Windows
   ```

3. Instalar dependencias (si existe `requirements.txt`):

   ```bash
   pip install -r requirements.txt
   ```

4. Abrir el notebook (o lo que uses):

   ```bash
   jupyter notebook
   ```

   y abrir `notebooks/superstore_analysis.ipynb`.

---

## Estado del proyecto

Este análisis forma parte de mis proyectos de práctica para **aprender análisis de datos con Python** y construir un portfolio honesto
