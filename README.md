# 📊 Análisis Exploratorio y Preprocesamiento de Pólizas

## 📌 Descripción
Notebook del proyecto integrador orientado al análisis exploratorio y limpieza de datos del sector asegurador, como preparación para identificar pólizas no renovadas.

## 👥 Integrantes
- Juan Carlos Fonseca Florez
- Zarith Dorelly Gómez Vargas
- Erika Fernanda Jiménez Camargo

## 🛠️ Tecnologías
- Python
- Pandas
- Seaborn
- Matplotlib

## ⚙️ Proceso
- Exploración de datos de producción y siniestros.
- Identificación de valores nulos, duplicados y tipos de datos.
- Unión de tablas mediante `Num_Poliza`.
- Eliminación de columnas innecesarias y con exceso de valores nulos.
- Imputación de valores faltantes.
- Análisis univariado y multivariado mediante gráficos.

## 📁 Archivos principales
**Entradas:**
- `siniestros_2025_tokenizado1.csv`
- `libro de producción_tokenizado2.parquet`

**Salida:**
- `Datos_Preprocesamiento.csv`

## 🚀 Ejecución
Instala las dependencias:

```bash
pip install pandas seaborn matplotlib pyarrow
```

Abre `EDA_y_Preprocesamiento_Polizas.ipynb` en Jupyter Notebook o Google Colab, carga los archivos de entrada y ejecuta las celdas en orden.

**Proyecto desarrollado con fines académicos.**
