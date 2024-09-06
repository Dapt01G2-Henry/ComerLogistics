# Entregables Sprint 1 

## 1. Crear el repositorio público y compartirlo con el equipo

### Descripción:
Uno de los pasos iniciales y fundamentales para la correcta organización del proyecto fue la creación de un repositorio público en GitHub, donde se centralizan todas las actividades de desarrollo y colaboración entre los miembros del equipo. Este repositorio funciona como el espacio de trabajo colaborativo en el que se almacenan todos los recursos del proyecto, incluidos scripts, notebooks, documentación, imágenes, y demás elementos necesarios para el correcto avance del proyecto.

Además, la implementación de control de versiones es esencial en un entorno colaborativo. GitHub permite el seguimiento de los cambios realizados en el código y la documentación, lo que asegura que todos los integrantes del equipo estén trabajando siempre con la versión más actualizada de los archivos y que se pueda retroceder a versiones anteriores en caso de errores.

### Acciones realizadas:

- **Creación del Repositorio en GitHub:**
   Se decidió utilizar GitHub como plataforma para alojar el repositorio debido a su amplia adopción en el ámbito profesional y sus funcionalidades de control de versiones, colaboración en tiempo real, y su integración con herramientas de desarrollo como Visual Studio Code. El repositorio fue creado bajo el nombre **ComerLogistics**, accesible en el siguiente enlace: [**ComerLogistics**](https://github.com/Dapt01G2-Henry/ComerLogistics). Desde este punto, todos los miembros del equipo fueron invitados como colaboradores para asegurar el acceso adecuado.

- **Configuración de Permisos de Acceso:**
   Se configuraron los permisos adecuados para garantizar que todos los miembros del equipo puedan clonar, modificar y contribuir activamente al repositorio. Cada colaborador cuenta con los permisos necesarios para realizar operaciones como *pull requests*, revisiones de código, y reportar *issues*. Esta estructura de permisos asegura un flujo de trabajo fluido y controlado, permitiendo a los líderes del proyecto aprobar o rechazar cambios críticos.

- **Control de Versiones:**
   La utilización de GitHub como sistema de control de versiones ha permitido a los desarrolladores mantener un historial detallado de todas las modificaciones realizadas. Esto facilita la identificación de cambios específicos, quién los realizó y cuándo se llevaron a cabo. Además, se han creado ramas (*branches*) para la experimentación y pruebas, lo que garantiza que el código en la rama principal (*main*) esté siempre en un estado funcional y estable.

   El uso de *pull requests* ha sido fundamental para asegurar que cualquier nuevo código o modificación sea revisado por otros miembros del equipo antes de ser fusionado en la rama principal. Esto también ha permitido una mayor colaboración, ya que los desarrolladores pueden comentar sobre los cambios, realizar revisiones de calidad y sugerir mejoras antes de que los cambios se hagan permanentes.

- **Documentación Inicial:**
   Se creó un archivo `README.md` que actúa como la página de inicio del repositorio. Este archivo proporciona información clave sobre el proyecto, como su propósito, cómo clonar el repositorio, y las instrucciones iniciales para la configuración del entorno de desarrollo. Además, incluye enlaces a los principales archivos y carpetas del proyecto, lo que facilita a los nuevos miembros del equipo la comprensión de la estructura del repositorio y el acceso a los recursos. Este archivo se actualiza periódicamente para reflejar el estado actual del proyecto y cualquier cambio relevante.

- **Estructura del Repositorio:**
   Para mantener una organización clara y accesible de los recursos del proyecto, se definió una estructura de carpetas desde el inicio. Las principales carpetas creadas dentro del repositorio incluyen:

   - **DiagramaEntidadRelacion:** Esta carpeta contiene los diagramas ER (Entidad-Relación) que definen las relaciones entre las tablas principales de la base de datos. [Ver carpeta](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/DiagramaEntidadRelacion).
   
   - **Imágenes:** Se almacenan los recursos gráficos necesarios, como logotipos, iconos, y gráficos utilizados en la documentación y visualización de datos. [Ver carpeta](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/Imagenes).

   - **Sprint_1:** Dentro de esta carpeta se organizan todos los scripts y notebooks utilizados durante el primer sprint del proyecto. Entre las subcarpetas más destacadas se encuentran:
      - **Conexion_SQL_Python:** Scripts relacionados con la conexión entre la base de datos SQL y Python. Esta conexión es fundamental para la automatización del flujo de datos. [Ver carpeta](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/be299b2f53546f7104b273e4f546a02a9e0b3559/Sprint_1/Conexion_SQL_Python).
      - **DataSet:** Contiene los archivos de datos utilizados durante el desarrollo del proyecto. Estos archivos fueron procesados y transformados para su carga en la base de datos SQL Server. [Ver carpeta](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/be299b2f53546f7104b273e4f546a02a9e0b3559/Sprint_1/DataSet).
      - **EDA y ETL:** Notebooks donde se realizó el análisis exploratorio de los datos (EDA) y el proceso de Extracción, Transformación y Carga (ETL), fundamental para asegurar la calidad de los datos antes de su análisis. [Ver carpeta](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/Sprint_1/EDA%20y%20ETL).
      - **Web_Scraping:** Carpeta que almacena los scripts desarrollados para la obtención de datos adicionales a través de scraping web, complementando el dataset principal con información relevante. [Ver carpeta](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/Web_Scraping).

- **Colaboración y Seguimiento del Proyecto:**
   A lo largo del proyecto, se utilizaron herramientas de seguimiento de issues y tareas proporcionadas por GitHub, lo que permitió llevar un control detallado de los avances del equipo, los obstáculos encontrados y las soluciones implementadas. Cada tarea asignada a los miembros del equipo estaba relacionada con un issue específico, lo que garantizó una adecuada trazabilidad y resolución de problemas.

- **Integración con Visual Studio Code:**
   Todo el equipo de desarrollo sincronizó el repositorio con **Visual Studio Code**, lo que facilitó la edición y el manejo de código en tiempo real. Esta integración permitió realizar *commits* directamente desde el entorno de desarrollo y mantener un flujo de trabajo ágil.

### Resultado Final:
Gracias a la creación del repositorio público y su adecuada configuración, el equipo ha logrado trabajar de manera colaborativa y eficiente. El control de versiones ha sido clave para asegurar que el desarrollo se realice de manera estructurada, mientras que la organización del repositorio ha permitido un fácil acceso a todos los recursos y archivos necesarios para el desarrollo del proyecto.

_____

## 2. Identificar los archivos a usar y armar la estructura de carpetas a usar en el repositorio

### Descripción:

En esta etapa inicial del proyecto, fue crucial realizar una identificación clara y precisa de los archivos de datos que se utilizarían para llevar a cabo el análisis y las operaciones de inventario, compras y ventas. La correcta identificación y organización de estos archivos permiten un flujo de trabajo eficiente y minimizan el riesgo de errores durante el desarrollo.

Además, se definió una estructura de carpetas en el repositorio que facilitara la colaboración entre los miembros del equipo, organizando los archivos de forma lógica y asegurando que cada sección del proyecto tuviera su propio espacio dentro del repositorio. Este enfoque garantiza que los desarrolladores puedan trabajar en diferentes aspectos del proyecto sin interferencias, manteniendo una separación clara entre scripts, datos, documentación y otros recursos.

### Acciones realizadas:

1. **Identificación de Archivos del DataSet Original:**
   El equipo comenzó con una revisión exhaustiva de todos los archivos disponibles en el dataset original proporcionado por la empresa. Estos archivos contenían información crítica sobre compras, ventas, productos y movimientos de inventario. Se realizó un análisis detallado de los archivos, y se procedió a renombrarlos para reflejar su propósito en el contexto del proyecto. Los archivos identificados fueron:

   - **Archivo Original:** `2017PurchasePricesDec` → **Nombre Actual:** `Tabla_Producto`
   - **Archivo Original:** `BegInvFINAL12312016` → **Nombre Actual:** `Tabla_InventarioInicial`
   - **Archivo Original:** `EndInvFINAL12312016` → **Nombre Actual:** `Tabla_InventarioFinal`
   - **Archivo Original:** `InvoicePurchases12312016` → **Nombre Actual:** `Tabla_Compras`
   - **Archivo Original:** `PurchasesFINAL12312016` → **Nombre Actual:** `Tabla_DetalleCompras`
   - **Archivo Original:** `SalesFINAL12312016` → **Nombre Actual:** `Tabla_VentasFinal`

2. **Revisión de Estructura y Tipos de Datos:**
   Tras la identificación de los archivos, se realizó una revisión exhaustiva de su estructura. El objetivo era asegurar que los tipos de datos fueran correctos y que las columnas estuvieran bien definidas. Se validaron aspectos como:

   - **Fechas:** Se revisaron los formatos de fecha para asegurarse de que fueran uniformes en todos los archivos.
   - **Claves Primarias y Foráneas:** Se identificaron los campos que servirían como claves primarias y foráneas para vincular las tablas entre sí.
   - **Consistencia de las Unidades:** Se verificó que las unidades de medida (como las cantidades de productos en inventario o vendidas) fueran consistentes en todos los archivos.

3. **Transformación de los Datos:**
   Se realizó un proceso de transformación para adecuar los datos a las necesidades del proyecto. Este proceso incluyó la normalización de los nombres de las columnas y la conversión de tipos de datos para facilitar su análisis posterior. Los detalles de esta transformación se documentaron en el notebook **EDA y ETL.ipynb**, donde cada archivo fue procesado, limpiado y preparado para ser cargado en la base de datos.

4. **Estructura de Carpetas en el Repositorio:**
   Una vez identificados y transformados los archivos, se definió una estructura de carpetas en el repositorio para organizar los diferentes aspectos del proyecto. La estructura establecida fue la siguiente:

   - **Sprint_1:**
     - **Conexion_SQL_Python:** Contiene scripts para la conexión entre SQL y Python.
     - **DataSet:** Almacena los archivos de datos originales y procesados.
     - **EDA y ETL:** Contiene notebooks para análisis exploratorio de datos (EDA) y transformación (ETL).
     - **Web_Scraping:** Scripts para obtener datos adicionales mediante scraping.
   
   - **DiagramaEntidadRelacion:** Contiene diagramas ER para las relaciones entre las tablas.
     - [Ver carpeta de Diagrama ER](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/DiagramaEntidadRelacion).

5. **Documentación de Archivos y Procesos:**
   A medida que se iban identificando y procesando los archivos, se documentaron los pasos en el archivo `Documentación.md`. Este archivo contiene un registro detallado de cada paso realizado durante el desarrollo del proyecto.

### Resultado Final:

La identificación precisa de los archivos y la estructuración lógica de las carpetas en el repositorio han sido fundamentales para garantizar la fluidez del proyecto. Gracias a esta organización, el equipo pudo realizar un análisis profundo y coherente de los datos.

### Enlaces Relacionados:
- [Repositorio ComerLogistics en GitHub](https://github.com/Dapt01G2-Henry/ComerLogistics)
- [Carpeta DataSet en el Repositorio](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/be299b2f53546f7104b273e4f546a02a9e0b3559/Sprint_1/DataSet)
- [EDA y ETL Notebooks](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/Sprint_1/EDA%20y%20ETL)

_____

## 3. Creación de la Base de Datos

### 3.1 Creación de la Base de Datos

**Descripción:**

La base de datos es el pilar fundamental sobre el cual se desarrolló todo el sistema de análisis de datos para **ComerLogistics**. En este proyecto, se optó por usar **SQL Server** como gestor de bases de datos por su robustez y capacidad para manejar grandes volúmenes de datos transaccionales.

El enfoque inicial fue crear una estructura de base de datos que permitiera almacenar de forma eficiente los datos de inventarios, compras y ventas, manteniendo una trazabilidad clara de cada operación realizada en el sistema. Se buscó una arquitectura que permitiera realizar consultas rápidas y eficaces, que brindaran insights útiles para la toma de decisiones.

#### Acciones Realizadas:

1. **Configuración del entorno SQL Server:**
   Se configuró un servidor de bases de datos utilizando **SQL Server**, asegurando que estuviera optimizado para realizar cargas de datos masivas y consultas complejas. La configuración inicial incluyó la instalación del servidor, la creación de usuarios y la configuración de permisos adecuados para los diferentes miembros del equipo de desarrollo y análisis.

2. **Creación de la base de datos `COMERLOGISTICS`:**
   Posteriormente, se creó una base de datos llamada **COMERLOGISTICS**. Esta base de datos fue diseñada para gestionar las tablas que contienen datos relacionados con el inventario, las compras y las ventas de productos, además de otras métricas clave.

3. **Conexión a la base de datos desde Python:**
   Se utilizó **SQLAlchemy** y **PyODBC** como intermediarios para establecer una conexión entre Python y SQL Server, lo que permitió integrar el procesamiento y análisis de datos con Python, así como la manipulación y consulta de los mismos directamente desde notebooks en **Jupyter**. Esta conexión facilitó la automatización de procesos que involucraban la manipulación de datos en la base de datos.

   - **SQLAlchemy:** Biblioteca de Python utilizada para la interacción con SQL Server, proporcionando una interfaz para la manipulación de datos y la ejecución de consultas.
   - **PyODBC:** Módulo que facilita la conexión a bases de datos SQL Server desde Python, utilizado en la configuración de las cadenas de conexión y en el manejo de las consultas SQL.

#### Enlaces Relacionados:
- [Carga_Datos_Finales_a_SQL.ipynb](https://github.com/Dapt01G2-Henry/ComerLogistics/blob/main/Sprint_1/Conexion_SQL_Python/Carga_Datos_Finales_a_SQL.ipynb)

---

### 3.2 Identificación de Entidades y Tablas

**Descripción:**

La correcta identificación de las entidades y tablas fue crucial para el éxito del proyecto, ya que esto permitió la creación de un modelo de datos que reflejara con precisión las necesidades operativas y analíticas de **ComerLogistics**. Durante este proceso, se analizaron todos los aspectos del negocio, desde las compras hasta las ventas y la gestión de inventarios.

#### Acciones Realizadas:

1. **Análisis de las Operaciones del Negocio:**
   El equipo realizó un análisis exhaustivo de las operaciones de la empresa para determinar las entidades clave que debían ser modeladas en la base de datos. Se identificaron las operaciones críticas que afectan el inventario, tales como las compras y ventas, y se estableció un modelo de datos adecuado para almacenarlas.

2. **Entidades Identificadas:**
   A partir de este análisis, se identificaron las siguientes tablas principales, que cubren las necesidades de la empresa:

   - **Tabla_Compras:** Registra las compras realizadas por la empresa. Incluye información detallada sobre las transacciones con los proveedores.
   - **Tabla_DetalleCompras:** Registra los detalles de cada compra, desglosando las cantidades de productos comprados.
   - **Tabla_InventarioInicial:** Contiene los registros de los niveles de inventario al inicio del período analizado.
   - **Tabla_InventarioFinal:** Contiene los registros de los niveles de inventario al final del período analizado.
   - **Tabla_Producto:** Proporciona información detallada sobre cada producto, como la descripción y el precio.
   - **Tabla_VentasFinal:** Contiene las ventas realizadas por la empresa.

3. **Renombrado de Archivos y Normalización de Columnas:**
   Los archivos que inicialmente fueron proporcionados en el dataset original se renombraron para alinearse con las convenciones de nombres utilizados en la base de datos. Se revisaron y normalizaron las columnas de estos archivos para asegurar una integración sin problemas.

   - **2017PurchasePricesDec** → `Tabla_Producto`
   - **BegInvFINAL12312016** → `Tabla_InventarioInicial`
   - **EndInvFINAL12312016** → `Tabla_InventarioFinal`
   - **InvoicePurchases12312016** → `Tabla_Compras`
   - **PurchasesFINAL12312016** → `Tabla_DetalleCompras`
   - **SalesFINAL12312016** → `Tabla_VentasFinal`

4. **Diagrama Entidad-Relación (ER):**
   Para visualizar las relaciones entre las diferentes tablas, se generó un **Diagrama Entidad-Relación** (ER) que muestra cómo interactúan entre sí las entidades. Este diagrama fue clave para entender las dependencias y asegurarse de que el modelo de datos fuera coherente y eficiente.

   - [Ver Diagrama ER](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/DiagramaEntidadRelacion)

---

### 3.3 Creación de Tablas y Objetos SQL

**Descripción:**

Una vez definidas las entidades clave, el siguiente paso fue la creación de las tablas en **SQL Server**. Cada tabla fue diseñada para reflejar la estructura de las entidades previamente identificadas. Se aplicaron reglas de normalización para evitar redundancias de datos y asegurar que cada tabla se mantuviera consistente con el modelo de datos establecido.

#### Acciones Realizadas:

1. **Definición de Estructura de Tablas:**
   Se definieron las columnas de cada tabla, asegurando que cada una incluyera la información relevante para el análisis. Se asignaron **tipos de datos** adecuados para cada columna, lo que permitió mejorar el rendimiento en las consultas y operaciones de base de datos.

2. **Implementación de Claves Primarias y Foráneas:**
   Se implementaron claves primarias en cada tabla para identificar de forma única los registros, y se establecieron claves foráneas para asegurar la integridad referencial entre las tablas. Esta relación permitió realizar consultas complejas que involucraban múltiples tablas, manteniendo la consistencia de los datos.

3. **Creación de Objetos SQL:**
   Adicionalmente, se crearon **índices** en las tablas más consultadas para mejorar el rendimiento de las consultas y facilitar el acceso a los datos de manera más rápida y eficiente. También se implementaron **vistas** para proporcionar una visión consolidada de los datos de inventario y ventas.

   El proceso de creación de estas tablas y objetos SQL fue documentado en el notebook **Carga_Datos_Finales_a_SQL.ipynb**.

#### Enlaces Relacionados:
- [Carga_Datos_Finales_a_SQL.ipynb](https://github.com/Dapt01G2-Henry/ComerLogistics/blob/main/Sprint_1/Conexion_SQL_Python/Carga_Datos_Finales_a_SQL.ipynb)

_____


## Punto 4: Identificar las entidades/tablas a usar en la BD

**Descripción:**

El éxito del proyecto depende en gran medida de la correcta identificación de las entidades y tablas que reflejan las operaciones comerciales de **ComerLogistics**. En esta etapa, se llevó a cabo un análisis exhaustivo de los datos proporcionados por la empresa, con el objetivo de modelar el sistema de información a través de una base de datos robusta y eficiente que permitiera gestionar de forma adecuada los datos de inventarios, ventas y compras.

### Acciones Realizadas:

1. **Análisis de Datos y Procesos Operativos:**
   Se comenzó con un estudio detallado de las operaciones diarias de **ComerLogistics**, enfocándose en los procesos críticos de la empresa como el ciclo de compra-venta, la gestión de inventarios y la rotación de productos. El objetivo era asegurarse de que cada entidad de la base de datos representara un aspecto clave del negocio.

2. **Definición de las Entidades:**
   Se identificaron las principales entidades que serían modeladas en la base de datos, basadas en los datos proporcionados. Las entidades principales son:
   - **Productos:** Representa cada uno de los artículos que **ComerLogistics** gestiona, con información como marca, descripción y precio.
   - **Compras:** Contiene los registros de las transacciones realizadas para abastecer los inventarios.
   - **Ventas:** Almacena los registros de todas las ventas, detallando los productos vendidos, las cantidades y las tiendas involucradas.
   - **Inventario Inicial y Final:** Representan los niveles de inventario en un momento específico, permitiendo hacer un seguimiento de la evolución del stock.

3. **Tablas de Base de Datos Derivadas:**
   Una vez identificadas las entidades, se procedió a definir las tablas que albergarían los datos de estas entidades en la base de datos. Las principales tablas son:
   - **Tabla_Producto:** Que almacena información detallada sobre cada producto.
   - **Tabla_Compras:** Almacena las compras realizadas y las transacciones con proveedores.
   - **Tabla_DetalleCompras:** Almacena el desglose de las compras, especificando los productos adquiridos y las cantidades.
   - **Tabla_InventarioInicial y Tabla_InventarioFinal:** Registran los niveles de inventario al inicio y al final de cada periodo.
   - **Tabla_VentasFinal:** Registra todas las ventas realizadas por la empresa, detallando productos, cantidades y montos.

4. **Análisis de Dependencias y Relaciones:**
   Durante este proceso, se analizaron las dependencias entre las diferentes entidades, lo cual ayudó a definir las relaciones que debían existir entre las tablas. Esto incluye las relaciones entre productos y compras, entre productos y ventas, y entre compras y detalles de compras. Se definieron claves primarias y foráneas para asegurar la integridad de los datos, permitiendo un fácil acceso y consulta a través de SQL.

5. **Uso de Diagrama ER (Entidad-Relación):**
   Con el fin de visualizar mejor las relaciones entre las tablas y validar la estructura del sistema, se creó un **Diagrama Entidad-Relación (ER)**. Este diagrama no solo facilita la comprensión del modelo de datos por parte del equipo de desarrollo, sino que también proporciona una representación clara para futuras consultas y mejoras en el sistema.

### Enlaces Relacionados:
- [Identificación de Entidades y Tablas en el Proyecto](https://github.com/Dapt01G2-Henry/ComerLogistics/blob/main/Sprint_1/DataSet/DataSets%20en%20Drive.txt)
- [Diagrama ER](https://github.com/Dapt01G2-Henry/ComerLogistics/tree/4af09eba8ed8b2a3f9a07d60f767dfc9b4cbb47d/DiagramaEntidadRelacion)

_____

## Punto 5: Crear las tablas y objetos SQL necesarios

**Descripción:**

Una vez identificadas las entidades principales y las tablas necesarias, el siguiente paso fue implementar estas tablas en la base de datos **SQL Server**. Este proceso incluyó la definición detallada de las columnas de cada tabla, así como la configuración de relaciones mediante claves foráneas, asegurando la integridad referencial de los datos.

### Acciones Realizadas:

1. **Definición de Estructura de Tablas:**
   Se definieron las tablas en **SQL Server** utilizando las entidades previamente identificadas. Cada tabla fue cuidadosamente diseñada para almacenar los datos clave de **ComerLogistics**, respetando la normalización y asegurando que cada entidad reflejara adecuadamente los procesos de negocio.

   - **Tabla_Producto:** Almacena la información esencial de cada producto, como el nombre, marca, tamaño y precio.
   - **Tabla_Compras:** Registra cada transacción de compra realizada, permitiendo rastrear las fechas de compra y los proveedores.
   - **Tabla_DetalleCompras:** Registra los detalles de cada compra, desglosando los productos comprados y las cantidades.
   - **Tabla_InventarioInicial y Tabla_InventarioFinal:** Estas tablas almacenan los registros de los inventarios al inicio y al final del periodo, respectivamente.
   - **Tabla_VentasFinal:** Registra todas las ventas, proporcionando información detallada sobre las transacciones realizadas con los clientes.

2. **Configuración de Claves Primarias y Foráneas:**
   Para asegurar la integridad de los datos, cada tabla fue configurada con **claves primarias** que garantizan la unicidad de los registros. Adicionalmente, se configuraron **claves foráneas** que aseguran la relación entre diferentes tablas, como la relación entre productos y compras, o entre productos y ventas.

3. **Creación de Vistas e Índices:**
   Con el objetivo de mejorar el rendimiento y facilitar las consultas frecuentes, se crearon **vistas** que permiten tener acceso rápido a datos de múltiples tablas a la vez. Además, se crearon **índices** en las tablas más consultadas, lo que permitió optimizar las consultas y reducir los tiempos de respuesta al ejecutar operaciones en la base de datos.

4. **Documentación del Proceso SQL:**
   Todas las operaciones relacionadas con la creación de las tablas, claves y vistas fueron documentadas en el notebook **Carga_Datos_Finales_a_SQL.ipynb**, el cual detalla paso a paso la creación de las tablas y los scripts SQL utilizados para el despliegue de la base de datos.

### Enlaces Relacionados:
- [Carga_Datos_Finales_a_SQL.ipynb](https://github.com/Dapt01G2-Henry/ComerLogistics/blob/main/Sprint_1/Conexion_SQL_Python/Carga_Datos_Finales_a_SQL.ipynb)

_____

