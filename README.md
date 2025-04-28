# 🛒 Insta-Cart

## 📝 Contexto
Instacart es una plataforma de entregas de comestibles que permite a los clientes hacer pedidos en línea y recibirlos en su domicilio, de forma similar a servicios como Uber Eats o Door Dash.  
Este proyecto tiene como objetivo analizar un conjunto de datos reducido y modificado de Instacart, conservando la distribución de los datos originales, para comprender mejor los patrones de compra de los clientes.

## 🛠️ Herramientas Utilizadas
- **Python**: Análisis de datos y preprocesamiento.
- **Pandas** y **NumPy**: Manipulación y limpieza de datos.
- **Matplotlib** y **Seaborn**: Visualización de datos.
- **Jupyter Notebook**: Documentación del flujo de trabajo.

## 📈 Análisis de Resultados
El proyecto se desarrolló en tres pasos principales:
1. **Descripción de los datos**: Se revisó la estructura y contenido de cinco archivos (`instacart_orders.csv`, `products.csv`, `order_products.csv`, `aisles.csv`, `departments.csv`), identificando claves primarias y relaciones entre tablas.
   
2. **Preprocesamiento de los datos**: 
   - Se eliminaron duplicados y se gestionaron valores ausentes.
   - Se integraron las tablas para un análisis consolidado de pedidos, productos, pasillos y departamentos.

3. **Análisis de los datos**:
   - Se generaron gráficos y tablas para visualizar:
     - Productos más populares.
     - Tiempos y frecuencias de compra (por día de la semana y hora del día).
     - Patrones de reordenamiento de productos.

## 📋 Conclusiones
- La limpieza de los datos fue crucial para garantizar análisis confiables y significativos.
- Se identificaron los productos con mayor demanda y los patrones de reordenamiento, proporcionando insights valiosos sobre la fidelidad de los clientes y sus preferencias de compra.
- Los resultados permiten a la empresa comprender mejor el comportamiento de sus usuarios y optimizar sus estrategias de inventario y marketing.
