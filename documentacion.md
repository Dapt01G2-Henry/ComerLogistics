# Documentación del Proyecto ComerLogistics

## 1. Introducción
El proyecto ComerLogistics tiene como objetivo optimizar la gestión de inventarios y mejorar la trazabilidad de productos en una compañía de logística, mediante el uso de tecnologías avanzadas de análisis de datos. Se han implementado metodologías y herramientas que permiten un control integral de las operaciones comerciales, desde la adquisición y almacenamiento hasta la venta de productos. 

Para lograrlo, se han utilizado herramientas como **Python**, **SQL** y **Power BI**, integrando el análisis detallado de ventas, compras, y movimientos de inventario con el objetivo de mejorar la toma de decisiones estratégicas y operativas.

El enfoque ha sido diseñado para automatizar y optimizar el flujo de información, de modo que las decisiones relacionadas con los costos, la rotación de inventarios y la predicción de la demanda se tomen basadas en datos confiables y actualizados en tiempo real. Esto ha permitido la creación de **dashboards dinámicos** que facilitan la visualización de métricas críticas.

---

## 2. Configuración Inicial

### 2.1 Creación del Repositorio Público
**Acción Realizada:** Se creó un repositorio público en **GitHub** denominado **ComerLogistics**, el cual actúa como el núcleo colaborativo donde se alojan todos los scripts, notebooks y documentación necesaria para el desarrollo del proyecto. Este repositorio permite la interacción fluida entre los miembros del equipo, facilitando la revisión de código y el seguimiento de las modificaciones realizadas en tiempo real. 

El repositorio se puede encontrar en el siguiente enlace:  
[ComerLogistics - GitHub](https://github.com/Dapt01G2-Henry/ComerLogistics)

---

### 2.2 Estructura de Carpetas
**Acción Realizada:** Para mantener la organización del proyecto, se estructuró el repositorio con las siguientes carpetas:

- **DiagramaEntidadRelacion:** Contiene los diagramas ER (Entidad-Relación) que definen las relaciones entre las tablas principales de la base de datos.
- **Imágenes:** Almacena recursos visuales como logos, íconos y fondos utilizados en el proyecto.
- **Sprint_1:** Dentro de esta carpeta se encuentran los scripts y notebooks del proyecto, divididos en subcarpetas por funcionalidad:
    - **Conexion_SQL_Python:** Scripts relacionados con la conexión entre SQL y Python, permitiendo la automatización de los procesos de carga de datos.
    - **DataSet:** Contiene los archivos de datos utilizados en el proyecto. También incluye un archivo que referencia los datasets alojados en Google Drive.
    - **EDA y ETL:** Notebooks dedicados al análisis exploratorio de datos (EDA) y procesos de Extracción, Transformación y Carga (ETL).
    - **Web_Scraping:** Scripts utilizados para realizar scraping de sitios web, obteniendo datos adicionales necesarios para el análisis.
    - **Documentación.txt:** Archivo de texto que documenta cada paso realizado durante el desarrollo del proyecto.
## 3. Creación y Configuración de la Base de Datos

### 3.1 Creación de la Base de Datos
**Acción Realizada:** Se configuró una base de datos **SQL Server** llamada **COMERLOGISTICS**. Para interactuar con la base de datos desde Python, se utilizó **SQLAlchemy** y **PyODBC**, lo que permitió establecer una conexión robusta entre las aplicaciones. Esto facilita realizar operaciones **CRUD** (Create, Read, Update, Delete) en la base de datos y la manipulación de grandes volúmenes de información de manera automatizada.

---

### 3.2 Identificación de Entidades y Tablas
**Acción Realizada:** Tras un análisis exhaustivo de los datos y del modelo de negocio, se identificaron las principales entidades del sistema y las tablas correspondientes, entre las cuales se encuentran:

| Nombre Original             | Nombre Actual          |
| ----------------------------| -----------------------|
| **2017PurchasePricesDec**    | **Tabla_Producto**      |
| **BegInvFINAL12312016**      | **Tabla_InventarioInicial** |
| **EndInvFINAL12312016**      | **Tabla_InventarioFinal** |
| **InvoicePurchases12312016** | **Tabla_Compras**       |
| **PurchasesFINAL12312016**   | **Tabla_DetalleCompras**|
| **SalesFINAL12312016**       | **Tabla_VentasFinal**   |

- **Tabla_Compras:** Contiene el registro de todas las compras realizadas.
- **Tabla_DetalleCompras:** Incluye los detalles específicos de cada compra, como los productos adquiridos y sus respectivas cantidades.
- **Tabla_InventarioInicial:** Representa el inventario al inicio del período de análisis.
- **Tabla_InventarioFinal:** Representa el inventario al final del período de análisis.
- **Tabla_Producto:** Contiene información detallada de cada producto gestionado por la compañía.
- **Tabla_VentasFinal:** Registra todas las ventas realizadas.

---

### 3.3 Creación de Tablas y Objetos SQL
**Acción Realizada:** Se crearon las tablas mencionadas anteriormente en la base de datos **SQL Server**. Las relaciones entre las tablas fueron definidas mediante el uso de claves primarias y foráneas, con base en el modelo de datos en **copo de nieve**, seleccionado para facilitar las consultas y mejorar el rendimiento del sistema.

Los diagramas ER en la carpeta **DiagramaEntidadRelacion** muestran claramente cómo estas tablas se relacionan entre sí, permitiendo un fácil acceso y comprensión del modelo.

---

## 4. Flujo de Ingesta de Datos

### 4.1 Extracción, Transformación y Carga de Datos (ETL)
**Acción Realizada:** Se implementó un proceso **ETL** utilizando **Python**. Este proceso fue desarrollado y documentado en el notebook **EDA y ETL.ipynb** y se divide en las siguientes fases:

- **Extracción:** Lectura de archivos de datos en diferentes formatos (principalmente CSV), transformando y normalizando la información.
- **Transformación:** Incluye el manejo de valores nulos, la limpieza de datos y la realización de operaciones aritméticas para asegurar la calidad de los datos. Se establecieron estándares en el formato de fechas y se unificaron tipos de datos en todas las columnas.
- **Carga:** Los datos transformados fueron cargados en la base de datos **SQL Server** a través de la conexión establecida previamente.

---

### 4.2 Validación del Proceso
**Acción Realizada:** Para asegurar la calidad del proceso, se realizaron pruebas de acceso para todos los miembros del equipo. Se verificó que el proceso **ETL** funcionara de forma fluida y sin interrupciones, garantizando que los datos fueran cargados de forma correcta y sin duplicaciones.

---
