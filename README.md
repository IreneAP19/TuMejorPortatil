# TuMejorPortatil

## Descripción del Proyecto
Este proyecto tiene como objetivo predecir el precio de un portátil en euros utilizando técnicas de Machine Learning. Se han utilizado datos con diversas características de los portátiles, como la marca, el tamaño de pantalla, la resolución, la CPU, la RAM, la memoria de almacenamiento, la GPU, el sistema operativo y el peso. Tras realizar un proceso de Feature Engineering y probar varios modelos, se ha seleccionado **Random Forest Regressor** como el modelo final debido a su buen rendimiento.

## Datos
El dataset contiene las siguientes columnas:

1. **Company** (String) - Fabricante del portátil.
2. **Product** (String) - Marca y modelo.
3. **TypeName** (String) - Tipo de portátil (Notebook, Ultrabook, Gaming, etc.).
4. **Inches** (Numeric) - Tamaño de la pantalla en pulgadas.
5. **ScreenResolution** (String) - Resolución de la pantalla.
6. **Cpu** (String) - Unidad Central de Procesamiento (CPU).
7. **Ram** (String) - Memoria RAM del portátil.
8. **Memory** (String) - Capacidad de almacenamiento (HDD/SSD).
9. **GPU** (String) - Tarjeta gráfica.
10. **OpSys** (String) - Sistema operativo.
11. **Weight** (String) - Peso del portátil.
12. **Price_euros** (Numeric) - Precio en euros (Variable objetivo).

## Preprocesamiento de Datos y Feature Engineering
Se realizaron varias transformaciones y limpieza de datos, incluyendo:
- Conversión de valores categóricos en numéricos mediante **One-Hot Encoding**.
- Conversión de unidades (por ejemplo, RAM y peso a valores numéricos).
- Extracción de información clave de CPU y GPU.
- Creación de nuevas características relevantes.



Después de comparar el rendimiento de los modelos con métricas como **MAE y R²**, se seleccionó **Random Forest Regressor** como el modelo final debido a su capacidad de capturar relaciones no lineales y su alto rendimiento en la predicción de precios.

## Implementación y Evaluación
Se utilizó **scikit-learn** para la implementación del modelo. La evaluación se realizó con un conjunto de prueba, obteniendo los siguientes resultados:
- **R² Score**: (valor obtenido)
- **MAE**: (valor obtenido)


