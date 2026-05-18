# Proyecto-Analisis-de-una-empresa-de-telecomunicaciones

# 🎯 Descripcion del proyecto
Procesamiento e  identificacion de patrones de uso, comportamientos atípicos y caracterizacion de segmentos de clientes, respecto a las diferentes necesidades de los clientes  y las actuales y potenciales ofertas comerciales, con el fin de mejorar la experiencia de los  usuarios

# fuentes de datos (Datasets)

plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

# 🛠️ Herramnientas empleadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

# 📌 Procesos de analisis
Limpiar y preparar los datos para el análisis
Identificar valores nulos y problemas de calidad
Explorar patrones de comportamiento de los clientes
Segmentar usuarios según edad y nivel de uso
Detectar clientes de alto valor
Encontrar patrones extremos de consumo
Generar recomendaciones estratégicas para ConnectaTel.

# 🧩 Contenido del proyecto
- Limpieza de datos
  Tratamiento de valores nulos, Conversión de tipos de datos, Eliminación de duplicados, Validación de columnas
- Análisis exploratorio
  Estadísticas descriptivas, Histogramas, Boxplots, Distribucion de variables
- Segmentación de clientes
  Clasificación por edad, Segmentación por nivel de uso, Identificación de clientes de alto valor
- Detección de outliers
  Método IQR, Análisis de consumo extremo, Impacto potencial en el negocio
- Visualizaciones
  Histogramas, Gráficos de dispersión, Boxplots, Comparaciones entre segmentos

# 📈 Principales Hallazgos
Se identificaron valores nulos en columnas críticas del dataset.
Evidencia de clientes con niveles de uso extremadamente altos.
Segmentacion de consumo con oportunidades importantes de fidelización.
Diferencia de uso y consumo entr usuarios de segmentojóvenes Vs usuarios mayores.
EPotenciales oportunidades de optimizacion de planes y servicios.

# 💡 Recomendaciones de Negocio
Modificar y generar nuevos planes con opcoion de personalizacion para clientes de alto consumo.
Crear campañas específicas según segmento de edad.
Seguimineto y monitoreo de usuarios con consumo extremo.
Mejorar procesos de captura de datos para reducir valores faltantes.

# 🚀 Cómo Ejecutar el Proyecto
1️⃣ Clonar el repositorio
git clone [https://github.com/tu-usuario/connectatel-analysis.git](https://github.com/jftobonp-Nasua/Proyecto-Analisis-de-una-empresa-de-telecomunicaciones.git)
2️⃣ Entrar a la carpeta
Analisis-de-una-empresa-de-telecomunicaciones
3️⃣ Instalar dependencias
pip install -r requirements.txt
4️⃣ Ejecutar Jupyter Notebook
jupyter notebook

Abrir el archivo:
Analisis-de-una-empresa-de-telecomunicaciones.ipynb
