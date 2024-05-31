# ST0263 Tópicos Especiales en Telemática

**Estudiante: Miguel Sosa, msosav@eafit.edu.co**

**Profesor: Edwin Montoya, emontoya@eafit.edu.co**

## Proyecto 3: Apache Spark

### 1. Breve descripción de la actividad

La actividad consiste en realizar un análisis exploratorio de datos sobre los datos de covid-19 en Colombia, almacenar los datos en AWS S3 y Google Drive, y responder preguntas de negocio sobre los datos de covid-19 en Colombia utilizando Spark Dataframes y SparkSQL.

#### 1.1. Que aspectos cumplió o desarrolló de la actividad propuesta por el profesor (requerimientos funcionales y no funcionales)

- [x] Leer los datos de covid-19 en Colombia de S3 y Google Drive.
- [x] Realizar un análisis exploratorio de datos.
- [x] Responder preguntas de negocio sobre los datos de covid-19 en Colombia utilizando Spark Dataframes y SparkSQL.
- [x] Almacenar los datos en AWS S3 y Google Drive.

#### 1.2. Que aspectos NO cumplió o desarrolló de la actividad propuesta por el profesor (requerimientos funcionales y no funcionales)

Se cumplieron todos los requerimientos del proyecto.

### 2. Información general de diseño de alto nivel, arquitectura, patrones, mejores prácticas utilizadas.

Para el desarrollo del proyecto se utilizó Google Colab, un entorno de Jupyter Notebook que permite ejecutar código Python en la nube. Se utilizó Google Colab para leer los datos de covid-19 en Colombia, realizar un análisis exploratorio de datos, responder preguntas de negocio sobre los datos de covid-19 en Colombia utilizando Spark Dataframes y SparkSQL, y almacenar los datos en AWS S3 y Google Drive.

### 3. Desarrollo

#### 3.1. Preparación del ambiente

1.  Descargar el archivo `covid19_colombia.csv` con el siguiente comando:

    ```bash
    wget https://www.datos.gov.co/api/views/gt2j-8ykr/rows.csv?accessType=DOWNLOAD -O covid19_colombia.csv
    ```

    _Nota: La descarga del archivo puede tardar unos minutos._

2.  Crear una cuenta de Google y crear un Notebook en Google Colab.

3.  Crear un bucket en AWS S3 que contenga el archivo descargado.

    <p align="center">
    <img src="https://github.com/msosav/st0263-Proyecto-3-Apache-Spark/assets/85181687/6cb02d5f-4540-4e26-96c9-56647ead97d1" />
    </p>

4.  Crear un directorio en Google Drive que contenga el archivo descargado.

    <p align="center">
    <img src="https://github.com/msosav/st0263-Proyecto-3-Apache-Spark/assets/85181687/7ff18726-c173-4143-be7e-7fdaf74c4247" />
    </p>

## Referencias
