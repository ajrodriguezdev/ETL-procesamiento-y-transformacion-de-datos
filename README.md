# 📊 ETL - Procesamiento y Transformación de Datos

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data_Processing-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-Database-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/ETL-Data_Pipeline-6C63FF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

<p align="center">
  Proyecto de procesamiento de datos enfocado en la extracción, transformación, validación y almacenamiento de información mediante procesos ETL.
</p>

---

## 📌 Descripción del proyecto

ETL - Procesamiento y Transformación de Datos es un proyecto orientado a desarrollar un flujo de trabajo que permita extraer información desde diferentes fuentes, transformarla y almacenarla en una base de datos estructurada.

El objetivo es implementar procesos que permitan limpiar datos, detectar inconsistencias, estandarizar formatos y preparar información para su posterior análisis.

El desarrollo utilizará Python y SQL, aplicando técnicas de procesamiento y transformación de datos.

## 🎯 Objetivos

- Implementar procesos ETL.
- Extraer datos desde archivos y fuentes estructuradas.
- Limpiar y transformar información.
- Identificar y tratar datos duplicados o inconsistentes.
- Validar la calidad de los datos.
- Almacenar información procesada en una base de datos SQL.
- Generar resultados que faciliten el análisis de información.

## 🔄 Flujo ETL

<details>
<summary><b>1. Extract - Extracción</b></summary>

Obtención de información desde fuentes como:

- Archivos CSV.
- Archivos Excel.
- Archivos JSON.
- Bases de datos SQL.

</details>

<details>
<summary><b>2. Transform - Transformación</b></summary>

Procesamiento de los datos mediante:

- Limpieza de registros.
- Eliminación de duplicados.
- Tratamiento de valores nulos.
- Estandarización de formatos.
- Validación de estructuras.
- Conversión de tipos de datos.

</details>

<details>
<summary><b>3. Load - Carga</b></summary>

Almacenamiento de los datos transformados en una base de datos SQL para facilitar su consulta y análisis posterior.

</details>

## 🛠️ Tecnologías utilizadas

**Lenguaje y procesamiento**
- Python
- Pandas
- NumPy

**Bases de datos**
- SQL
- PostgreSQL o MySQL (motor por definir)

**Herramientas**
- Git y GitHub
- Jupyter Notebook (opcional)
- Visual Studio Code
- SQL client

## 🏗️ Estructura del proyecto

```text
etl-procesamiento-datos/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── src/
│   ├── extract/
│   ├── transform/
│   ├── load/
│   └── main.py
│
├── config/
│
├── notebooks/
│
├── tests/
│
├── requirements.txt
├── .gitignore
└── README.md
```

### Responsabilidad de cada componente

| Componente | Responsabilidad |
|---|---|
| data/raw | Almacenar datos originales de prueba |
| data/processed | Guardar datos transformados |
| extract | Extraer información desde las fuentes |
| transform | Limpiar y preparar los datos |
| load | Almacenar los datos procesados |
| config | Centralizar configuraciones |
| notebooks | Explorar y analizar información |
| tests | Validar los procesos ETL |

## 📥 Fuentes de datos

El proyecto podrá utilizar conjuntos de datos de prueba provenientes de:

- Archivos CSV.
- Archivos Excel.
- Archivos JSON.
- Bases de datos relacionales.

Se documentarán las fuentes y sus estructuras cuando se seleccionen los conjuntos de datos definitivos.

## ⚙️ Funcionalidades

| Funcionalidad | Descripción | Estado |
|---|---|---|
| Extracción de datos | Lectura de archivos y fuentes de información | 📋 Pendiente |
| Limpieza | Tratamiento de datos incompletos | 📋 Pendiente |
| Normalización | Estandarización de formatos y valores | 📋 Pendiente |
| Detección de duplicados | Identificación de registros repetidos | 📋 Pendiente |
| Validación | Comprobación de calidad y consistencia | 📋 Pendiente |
| Transformación | Preparación de datos para su almacenamiento | 📋 Pendiente |
| Carga | Inserción de datos en SQL | 📋 Pendiente |
| Reporte | Resumen del resultado del procesamiento | 📋 Pendiente |

## 🚀 Instalación y ejecución

### Requisitos previos

- Python 3.10 o superior.
- pip.
- Motor de base de datos SQL (cuando se implemente la carga).
- Git.

### 1. Clonar el repositorio

```bash
git clone https://github.com/ajrodriguezdev/etl-procesamiento-datos.git
```

### 2. Ingresar al proyecto

```bash
cd etl-procesamiento-datos
```

### 3. Crear un entorno virtual

```bash
python -m venv venv
```

Activar en Windows:

```bash
venv\Scripts\activate
```

Activar en Linux o macOS:

```bash
source venv/bin/activate
```

### 4. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 5. Ejecutar el proceso

```bash
python src/main.py
```

*Los comandos y dependencias se ajustarán cuando implementemos el proyecto.*

## 📈 Resultados esperados

Al finalizar el proceso ETL se espera obtener:

- Datos limpios y estructurados.
- Registros sin duplicados según las reglas definidas.
- Información validada y normalizada.
- Datos almacenados en una base de datos SQL.
- Resumen de registros procesados, descartados y transformados.

## 🧪 Pruebas

Se contemplan pruebas para verificar:

- Lectura correcta de las fuentes.
- Tratamiento de valores nulos.
- Detección de registros duplicados.
- Transformaciones aplicadas.
- Integridad de los datos almacenados.
- Manejo de errores durante la ejecución.

## 🗺️ Roadmap

- [ ] Selección de un conjunto de datos.
- [ ] Configuración del entorno Python.
- [ ] Implementación de extracción.
- [ ] Exploración y análisis inicial.
- [ ] Limpieza de datos.
- [ ] Transformación y normalización.
- [ ] Validación de calidad de datos.
- [ ] Configuración de base de datos SQL.
- [ ] Implementación de carga.
- [ ] Automatización del flujo ETL.
- [ ] Pruebas y documentación de resultados.

## 👩‍💻 Autora

**Andrea Rodriguez**  
Ingeniera de Sistemas | Backend Developer

- GitHub: [@ajrodriguezdev](https://github.com/ajrodriguezdev)
- LinkedIn: [Perfil profesional](https://www.linkedin.com/in/aj-rodriguez-g)

---

<p align="center">
  Desarrollado con Python y SQL.
  <br/>
  <b>De los datos en bruto a información estructurada. 📊</b>
</p>
