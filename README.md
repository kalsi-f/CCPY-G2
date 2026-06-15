# CCPY-G2

## Descripción

Proyecto de análisis de factores asociados a la pobreza multidimensional en la Región de Los Ríos, utilizando información proveniente de encuestas CASEN, datos públicos y fuentes complementarias.

El objetivo es estudiar distintas dimensiones relevantes para la caracterización de los hogares, tales como ingresos, educación, composición del hogar, inmigración y vivienda, integrando los resultados en visualizaciones y dashboards interactivos.

---

## Estructura del Proyecto

```text
CCPY-G2/
│
├── analisis_ingresos/
│   ├── Analisis Ingresos.ipynb
│   └── datos_pobreza_valdivia.csv
│
├── Composición Hogar/
│   ├── InmigracionRegionRios.ipynb
│   ├── D4_Inmigracion-Internacional.xlsx
│   └── Inmigración Internacional.png
│
├── Educación/
│   ├── Educacion-checkpoint.ipynb
│   ├── casen_losrios_2017_2024.csv
│   └── Grafico_Educacion.jpg
│
├── Vivienda/
│   ├── notebooks de análisis y visualización
│   ├── datos procesados
│   └── crawler para obtención de información inmobiliaria
│
├── dashboard.ipynb
├── Informe_Factores_Predominantes_PMD.pdf
└── presentacion_CCPY_G2.pptx
```

---


## 🚀 Instalación y Ejecución (Despliegue local)

Para ejecutar este proyecto y explorar los dashboards en tu máquina local, sigue estos pasos:

### 1. Clonar el repositorio

Abre tu terminal y clona este proyecto:

Bash

```
git clone <URL_DE_TU_REPOSITORIO>
cd CCPY-G2
```

### 2. Crear y activar el entorno virtual (Recomendado)

Para evitar conflictos con otras librerías de tu sistema, crea un entorno virtual (`venv`):

**En Linux / Mac (WSL):**

Bash

```
python3 -m venv venv
source venv/bin/activate
```

**En Windows (PowerShell):**

PowerShell

```
python -m venv venv
.\venv\Scripts\activate
```

### 3. Instalar las dependencias

Con el entorno virtual activado `(venv)`, instala todas las herramientas necesarias ejecutando:

Bash

```
pip install -r requirements.txt
```

### 4. Iniciar el Dashboard

Para ver el análisis interactivo, levanta el servidor de Jupyter Notebook:

Bash

```
jupyter notebook
```

Esto abrirá una pestaña en tu navegador. Desde ahí, haz clic en el archivo `dashboard.ipynb` para visualizar el proyecto completo.

## Componentes

### Ingresos

Análisis de indicadores relacionados con ingresos y brechas económicas.

### Composición del Hogar e Inmigración

Estudio de la evolución de la inmigración internacional y su relación con características de los hogares de la Región de Los Ríos.

### Educación

Análisis de indicadores educacionales.

### Vivienda

Análisis de condiciones habitacionales, acceso a servicios básicos y características del mercado inmobiliario regional.

### Dashboard

Notebook que integra los principales indicadores y visualizaciones generados en las distintas etapas del proyecto.

## Tecnologías Utilizadas

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Geopandas
- BeautifulSoup & Requests (Web Scraping)
- Jupyter Notebook

## Fuentes de Datos

- Encuesta CASEN
- Biblioteca del Congreso Nacional (BCN)
- Datos públicos de vivienda e información territorial
- Portales inmobiliarios (Scraping)

## Integrantes

- Cristóbal Espinoza
- Vicente Paredes
- Javier Ramírez
- Fabián Reyes

## Resultados

Los resultados consolidados pueden encontrarse en:

- `Informe_Factores_Predominantes_PMD.pdf`
- `presentacion_CCPY_G2.pptx`
- `dashboard.ipynb`