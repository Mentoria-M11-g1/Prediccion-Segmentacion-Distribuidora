## Práctico 1: Análisis y Visualización de Datos
Este trabajo forma parte del proyecto "Potenciá las ventas con IA", desarrollado en el marco de la Diplomatura en Ciencia de Datos de la FAMAF (UNC). El objetivo principal es aplicar técnicas de análisis exploratorio para detectar patrones comerciales, tendencias y comportamientos en datos reales de ventas mayoristas.

# 📂 Contenido del práctico
El análisis se basó en un conjunto de datos transaccionales, donde cada fila representa la venta de un ítem de producto a un cliente. Se abordaron los siguientes ejes:

- Revisión de estructura del dataset y calidad de datos.

- Análisis univariado y bivariado de variables clave: precios, cantidades, productos, clientes y fechas.

- Exploración de ventas por punto de venta, producto y cliente.

- Visualización de la evolución temporal y estacionalidad.

- Estudio de granularidad temporal para futuras predicciones.

# 🛠️ Instrucciones para correr la notebook
1. Requiere entorno Python 3.8+.

2. Instalar las siguientes librerías: pandas matplotlib seaborn plotly numpy

3. Correr la notebook secuencialmente desde el inicio para garantizar consistencia.

# 🔍 Hallazgos y observaciones

- Los **productos más vendidos** corresponden principalmente a golosinas, alfajores y turrones.

- Se observa una relación entre la **frecuencia de compra y el volumen total vendido**, útil para segmentar clientes.

- Algunos clientes compran con baja frecuencia pero en grandes volúmenes.

- Se detecta un impacto de la **inflación en los precios**.

- Las ventas muestran **estacionalidad anual**, con picos en ciertos meses y recesos en otros.

- La **granularidad mensual o trimestral** son más adecuadas para el análisis y modelado, ya que reducen el ruido y mejorar la interpretación.

💡 Hipótesis iniciales para etapas futuras

- Los clientes con mayor frecuencia podrían tener un mayor valor a largo plazo.

- Algunos productos no se venden lo suficiente como para incluirse en modelos de recomendación.

- Estandarizar códigos y descripciones de productos podría mejorar la capacidad predictiva de los modelos.

- Es necesario ajustar precios por inflación.

- Deben tratarse adecuadamente las series temporales incompletas, considerando que cada cliente posee un rango temporal de actividad distinto.


✅ Conclusiones generales
El análisis exploratorio permitió comprender en profundidad la base de ventas mayoristas y sentó las bases para el desarrollo futuro de modelos de segmentación, predicción de demanda y sistemas de recomendación personalizados.
