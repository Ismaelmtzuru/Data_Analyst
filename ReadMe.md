# Proyecto individual #2 (Empresa de telecomunicaciones) 📊

El propósito de este proyecto es la demostración de conocimientos adquiridos sobre el área de data analytics. Se centrará en la realización de visualizaciones, KPI's y análisis sobre datos obtenidos desde la web.

En el archivo main, se encuentra el EDA realizado a todos los archivos CSV descargados, son su respectiva limpieza y con algunos gráficos realizados para un mejor análisis.

## Instalación 🛠️

Para la instalación, solo es necesario la descarga de toda la información y ejecutar el archivo "main". Para su ejecución, solo es necesario ir ejecutando cada celda de código para ver cómo se fue realizando la limpieza y tomando decisiones sobre todos los datos que se encuentran en cada archivo y explicación de cada gráfico.

**Librerías necesarias para su correcto funcionamiento:**
- Pandas
- Seaborn
- Matplotlib.pyplot
- Numpy

## Estructura del proyecto 📂

La estructura del proyecto es la siguiente:

```
Data Analytics/
├── Datasets/
│ ├── Archivos_limpiados.csv
│ ├── Otro_archivo_limpiado.csv
│ 
├── Datasets Sucios/
│ ├── Archivo_original_1.csv
│ ├── Archivo_original_2.csv
│ 
├── main.ipynb
```


## Análisis y KPI's 📈

Al término del EDA, se tomó la decisión de hacer los siguientes KPI's para mostrarlos en un dashboard interactivo:

- **Crecimiento de servicios:**
  Aquí se calcula el crecimiento trimestral o anual de cada tipo de servicio de telecomunicaciones. Esto es para identificar las tendencias de adopción de los servicios a lo largo del tiempo.

- **Distribución de velocidades:**
  Se calcula la distribución de las velocidades de internet, es decir, la proporción de clientes que tienen diferentes rangos de velocidad.

- **Ingresos por trimestre o año:**
  Se calculan los ingresos totales de la empresa por trimestre y/o por año, de esta forma se evalúa el rendimiento financiero.

- **Retención de clientes:**
  Se calcula la retención anual de clientes para cada servicio. Se mide la cantidad de clientes que se mantuvieron durante un año determinado en comparación con otro año determinado.

Un dato lógico y quizás no tan obvio fue que, durante el año 2020 la tecnología "Dial up" mantuvo sus clientes estables, mientras que la tecnología "Banda ancha", siguió su crecimiento de forma constante.

Todo sobre este análisis, sea código o gráficos, se encuentran dentro del archivo "main", el cual es un notebook de Jupyter y así se pueda ver el análisis realizado sobre todo este proyecto.

