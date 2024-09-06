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