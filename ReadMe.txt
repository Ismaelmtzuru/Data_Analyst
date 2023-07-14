Proyecto individual #2  (Empresa de telecomunicaciones)
El propósito de este proyecto es la demostración de conocimientos adquiridos sobre el área de data analytics. Se centrará en la realización de visualizaciones, KPI´s y análisis sobre datos obtenidos desde la web.
En el archivo main, se encuentra el EDA realizado a todos los archivos CSV descargados, son su respectiva limpieza y con algunos gráficos realizados para un mejor análisis.

Para la instalación, solo es necesario la descarga de toda la información y ejecutar el archivo "main". 
Para su ejecución, solo es necesario ir ejecutando cada celda de código para ver como se fue realizando la limpieza y tomando decisiones sobre todos los datos que se encuentran en cada archivo y explicación de cada gráfico.

librerias necesarias para su correcto funcionamiento:
-Pandas
-Seaborn
-Matplotlib.pyplot
-Numpy

La estructura del proyecto es la siguiente:
En la carpeta Data Analytics se encuentran carpetas "Datasets" y "Datasets Sucios", en las cuales, en "Datasets" se encuentran los archivos ya limpiados y/o con el EDA realizado, mientras que en "Datasets Sucios", son los archivos originales descargados desde la web.
Todos estos archivos que se encuentran dentro de "Datasets" son usados dentro de un motor SQL donde se harán las consultas para obtener la información deseada desde PowerBI.

Al termino del EDA, se tomó la decisión de hacer los siguientes KPI´s para mostrarlos en un dashboard interactivo:

- Crecimiento de servicios: 
Aquí se calcula el crecimiento trimestral o anula de cada tipo de servicio de telecomunicaciones. Esto es para identificar las tendencias de adopción de los servicios a lo largo del tiempo.

-Distribución de velocidades:
Se calcula la distribución de las velocidades de internet, es decir, la proporción de clientes que tienen diferentes rangos de velocidad.

-Ingresos por trimestre o año:
Se calculan los ingresos totales de la empresa por trimestry y/o por año, de esta forma se evalua el rendimiento financiero.

-Retención de clientes:
Se calcula la retención anual de clientes para cada servicio. Se mide la cantidad de clientes que se mantuviero durante un año determinado en comparación de otro año determinado.

Un dato lógico y quizá no tanto, fue que, durante el año 2020 la tecnología "Dial up" mantuvo sus clientes estables, mientras que la tecnología "Banda ancha", siguió su crecimiento de forma constante.

Todo sobre este análisis sea código o gráficos, se encuentran dentro del archivo "main", el cual es un notebook de Jupyter y así se pueda ver el análisis realizado sobre todo este proyecto.