📡 Telecom X
📊 Descripción
Analizaremos el comportamiento de los clientes en Telecom X, una empresa que enfrenta una preocupante tasa de cancelaciones. Utilizaremos una base de datos obtenidas de una API. El objetivo es comprender qué factores influyen en la evasión (churn) y aportar información clave para mejorar la retención de los clientes. El proyecto se desarrolló a través de un proceso de extracción, limpieza y transformación de datos (ETL), seguido de un análisis exploratorio detallado para descubrir patrones, correlaciones e indicadores de abandono.

🧰 Tecnologías utilizadas
Python para el procesamiento y análisis y Jupyter Notebook (Google Colab) para trabajar ahí.
Un archivo de datos en formato JSON y la biblioteca Pandas para manipulación de datos.
NumPy para cálculos numéricos.
Matplotlib, Seaborn para visualización gráfica estadística.
Plotly para visualización gráfica interactiva.
🗂️ Estructura del proyecto y organización de los análisis
El proyecto está compuesto por distintas etapas bien diferenciadas:

Importación de los datos desde una API en formato JSON.
Limpieza de datos: eliminación de valores nulos y duplicados.
Creación de nuevas variables para el análisis (como cuentas diarias).
Estandarización: traducción de etiquetas al español y conversión de tipos de datos.
Análisis descriptivo: cálculo de media, mediana, desviación estándar, etc.
Visualización de la distribución de churn mediante gráficos circulares.
Análisis de churn según variables categóricas mediante gráficos de barras.
Análisis de churn según variables numéricas mediante boxplots, violin plots y KDE.
Análisis de correlación con matriz de calor y gráficos interactivos.
Conclusiones finales y recomendaciones estratégicas.
Ejemplos de gráficos e insights obtenidos.
📊 Gráficos de barras para el análisis de las variables categóricas con 'churn'.
🥧 Gráficos de torta para la visualización de la distribución del 'churn'.
📦 Gráficos de cajas para el análisis de las variables numéricas con 'churn' al igual que el uso del gráfico de violín 🎻.
🚀 Instrucciones para ejecutar el notebook
Descarga el archivo .ipynb desde este repositorio.
Súbelo a tu Google Drive
Ábrelo con Google Colab.
Ejecutá las celdas en orden, comenzando por la sección de importación de datos.
Asegurate de tener los archivos o links a la API correctamente configurados.
⚠️ Nota: Es necesario tener una cuenta en Google y GitHub. No olvides conectar el entorno de ejecución en Colab con Google Compute Engine y verificar que los archivos de datos estén correctamente cargados así como la correcta importación de las bibliotecas de Python.
