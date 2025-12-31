📊 Análisis de Evasión de Clientes – Telecom X (LATAM)
📌 Descripción del Proyecto

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre clientes de Telecom X en Latinoamérica, con el objetivo de identificar patrones y factores asociados a la evasión de clientes (Churn).

A través de técnicas de extracción, transformación y análisis de datos, se estudian variables clave como costos, consumo y comportamiento del cliente, apoyándose en visualizaciones para facilitar la interpretación de los resultados.

🎯 Objetivo del Análisis

Analizar el comportamiento de los clientes que cancelan y no cancelan el servicio.

Identificar diferencias significativas en costos totales y costos diarios.

Apoyar la toma de decisiones mediante insights visuales.

Sentar bases para futuros modelos predictivos de churn.

🛠️ Tecnologías y Librerías Utilizadas

Python

Pandas – Manipulación y análisis de datos

NumPy – Operaciones numéricas

Matplotlib – Visualización de datos

Seaborn – Gráficos estadísticos

Plotly Express – Visualizaciones interactivas

🧩 Estructura del Proyecto
📁 TelecomX-Churn-Analysis
│
├── TelecomX_LATAM.ipynb   # Notebook principal con el análisis completo
├── README.md              # Documentación del proyecto

🔄 Flujo del Análisis

El notebook sigue una estructura clara basada en ETL y análisis:

📌 Extracción

Carga de datos desde un repositorio en GitHub.

Revisión inicial del dataset (head, tail, info).

🔧 Transformación

Limpieza y normalización de datos.

Creación de variables auxiliares (por ejemplo, costos diarios).

Preparación del dataset para análisis.

📊 Carga y Análisis

Análisis descriptivo.

Comparación entre clientes con y sin churn.

Visualización de distribuciones y patrones.

📈 Ejemplos de Análisis y Visualizaciones

Distribución del costo total según la evasión del cliente.

Gráficos violin plot para comparar costos diarios entre clientes churn y no churn.

Análisis visual del impacto del churn en los ingresos.

Estos gráficos permiten detectar tendencias claras y diferencias significativas entre ambos grupos de clientes.

▶️ Instrucciones para Ejecutar el Notebook
Opción 1: Google Colab (Recomendada)

Abre el notebook desde el badge Open in Colab incluido en el archivo.

Ejecuta las celdas en orden.

No requiere instalación local.

Opción 2: Ejecución Local

Clona el repositorio:

git clone <URL_DEL_REPOSITORIO>


Instala las dependencias:

pip install pandas numpy matplotlib seaborn plotly


Abre el notebook:

jupyter notebook TelecomX_LATAM.ipynb

📌 Conclusiones Esperadas

Existen diferencias claras en los costos entre clientes que cancelan y los que permanecen.

La visualización facilita la detección de patrones de evasión.

El análisis puede ampliarse con modelos de machine learning para predicción de churn.

✍️ Autor

Jonathan Guevara Colmenares
