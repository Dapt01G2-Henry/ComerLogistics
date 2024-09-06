
# **Entregables Sprint 2**

## Objetivo General del Sprint 2

El objetivo principal de este sprint fue desarrollar un informe interactivo y funcional en Power BI que permitiera a los usuarios realizar un análisis detallado de las operaciones de ComerLogistics. El informe debía proporcionar visualizaciones claras y concisas de los datos clave, permitiendo tomar decisiones informadas basadas en métricas precisas.

Para lograr este objetivo, se realizaron una serie de pasos que abarcan desde la creación del archivo .pbix hasta la validación final del informe. Este sprint se enfocó en asegurar que todas las etapas, desde la importación de datos hasta la generación de reportes y gráficos, se llevaran a cabo con la máxima precisión y profesionalismo.

_____

## **1. Crear el archivo .pbix**

En el inicio del **Sprint 2**, el primer paso crítico fue la creación del archivo **.pbix** en **Power BI Desktop**. Este archivo es fundamental, ya que funciona como el contenedor que almacena todos los datos, cálculos, y visualizaciones necesarias para desarrollar el dashboard interactivo y los informes finales.

El archivo **.pbix** no solo es un archivo de datos, sino que también sirve como el entorno de desarrollo dentro del cual se lleva a cabo todo el trabajo de análisis, transformación de datos y diseño visual. Es aquí donde se establecen las conexiones a las distintas fuentes de datos, se crean las medidas calculadas utilizando el lenguaje **DAX**, y se diseñan los gráficos e informes que permiten a los usuarios finales interactuar de manera efectiva con los datos.

### **Detalles de la acción realizada:**
- **Creación del archivo**: Se creó un archivo en blanco en **Power BI Desktop** con el nombre **ComerLogisticsDashNube.pbix**. Este archivo fue configurado desde el principio para organizar los datos y facilitar su posterior procesamiento y análisis.
- **Configuración inicial**: El archivo se configuró con el formato de proyecto adecuado, permitiendo múltiples conexiones a fuentes de datos externas, tales como bases de datos **SQL Server**, **archivos Excel**, y **archivos CSV**. Cada fuente de datos fue seleccionada de acuerdo con los requisitos de análisis de **ComerLogistics**.
- **Estructura del archivo**: Dentro del archivo **.pbix**, se crearon secciones organizadas para gestionar los datos importados, las transformaciones aplicadas, y las medidas calculadas. Además, se incluyeron áreas específicas para los distintos dashboards y páginas de informes que se desarrollarían a lo largo del proyecto. Esta estructura ordenada permite que los desarrolladores trabajen de manera eficiente y coherente, asegurando que todos los componentes del análisis estén bien integrados.

### **Valor de este paso para el proyecto:**
- **Base para el análisis**: Este archivo es la base para todo el análisis y visualización que se lleva a cabo en Power BI. Sin un archivo **.pbix** bien estructurado, el proyecto carecería de un marco que conecte los datos con las visualizaciones y los cálculos.
- **Facilita la colaboración**: La creación de este archivo no solo permite que un desarrollador trabaje en los datos, sino que facilita el trabajo colaborativo, ya que múltiples personas pueden agregar, modificar y actualizar las visualizaciones, medidas, y cálculos, manteniendo la coherencia del análisis.
- **Preparación para la interacción**: Con la estructura base establecida en el archivo **.pbix**, se puede comenzar a trabajar en los elementos interactivos que permitirán a los usuarios finales explorar los datos en profundidad. El archivo **.pbix** está diseñado para soportar filtros, segmentadores y otros elementos visuales que ayudan a personalizar el análisis según las necesidades del negocio.

### **Conexión con otros pasos del sprint:**
Este paso inicial es crucial porque, una vez que el archivo está creado, se puede proceder con las siguientes etapas del desarrollo, como la importación de datos, limpieza, transformación, creación de medidas y visualizaciones. Cada una de estas acciones se lleva a cabo dentro del entorno proporcionado por el archivo **.pbix**, lo que asegura que todo el proceso esté centralizado y sea fácil de gestionar.

### **Siguiente paso:**
Tras la creación del archivo, el siguiente paso fue la **importación de datos** desde diferentes fuentes, que permitió comenzar a trabajar con la información real de **ComerLogistics** y llevar a cabo el análisis necesario.

[Repositorio ComerLogistics en GitHub](https://github.com/Dapt01G2-Henry/ComerLogistics)

_____

## **Punto 2: Importación de Datos a Power BI**

La importación de datos en Power BI fue un paso fundamental para comenzar a trabajar con la información disponible de **ComerLogistics** y dar inicio al análisis de los datos. Este proceso involucró la importación de archivos CSV, bases de datos SQL y otros orígenes de datos, de manera que se pudiera trabajar con ellos en el entorno de Power BI.

### **2. Importación de Datos a Power BI**

**Objetivo**: El objetivo de esta fase fue centralizar y cargar todos los datos relevantes en Power BI para realizar las transformaciones necesarias, análisis y posteriormente diseñar las visualizaciones interactivas.

### **Detalles de la acción realizada**:

1. **Selección de orígenes de datos**:
   - Los datos fueron recopilados de múltiples fuentes, entre ellas archivos CSV que contenían los datos históricos de inventarios, ventas, compras y productos, así como de una base de datos SQL que almacenaba registros clave del negocio.
   - El equipo decidió cargar todos los datos en Power BI desde estas fuentes para poder trabajar con ellos de manera centralizada.

2. **Importación de datos clave**:
   - **Inventario Inicial (BegInvFINAL12312016.csv)**: Representa el inventario al comienzo del período de análisis. Estos datos fueron esenciales para tener una referencia de las unidades disponibles y el valor del inventario en ese momento.
   - **Inventario Final (EndInvFINAL12312016.csv)**: Inventario registrado al final del período de análisis. Estos datos permitieron comparar la evolución del inventario y analizar su rotación.
   - **Compras (PurchasesFINAL12312016.csv)**: Registros de todas las compras realizadas por ComerLogistics durante el período. Se importaron los detalles de cada transacción, como las cantidades adquiridas, precios y fechas.
   - **Ventas (SalesFINAL12312016.csv)**: Datos de las ventas realizadas en el período. Estos archivos contienen información como productos vendidos, cantidades, precios y tiendas involucradas.
   - **Precios de Compra (2017PurchasePricesDec.csv)**: Archivo que contiene los precios de compra de los productos adquiridos, esencial para calcular los costos y márgenes.

3. **Estructuración y unificación de los datos**:
   - Durante la importación, se realizaron algunas modificaciones para asegurar que los datos de diferentes fuentes fueran compatibles entre sí y estuvieran listos para su análisis. Se realizó un mapeo de campos para asegurarse de que las tablas compartieran las claves necesarias (por ejemplo, *MarcaID* y *Tienda*).
   - Cada archivo fue importado como una tabla independiente en **Power BI**, y se crearon relaciones entre ellas utilizando campos comunes, como *InventarioInicialID* o *MarcaID*. Esta estructura permitió realizar análisis cruzados entre las diferentes fuentes de datos.

4. **Integración de bases de datos SQL**:
   - Se estableció una conexión directa a la base de datos **SQL Server** donde se almacenan los registros históricos de la empresa. A través de esta conexión, los datos de **ComerLogistics** fueron importados automáticamente, asegurando que estuvieran siempre actualizados sin la necesidad de cargar manualmente archivos CSV adicionales.
   - Las tablas de SQL importadas incluyen:
     - **Tabla_InventarioInicial**
     - **Tabla_InventarioFinal**
     - **Tabla_Compras**
     - **Tabla_VentasFinal**
     - **Tabla_Producto**

5. **Documentación de la importación**:
   - Se generó documentación en el archivo `documentacion.md` del repositorio de GitHub, explicando los pasos seguidos para la importación de datos, las tablas involucradas, y las relaciones creadas entre ellas. Este archivo de documentación es clave para que todos los miembros del equipo comprendan cómo se ha estructurado la información dentro de Power BI.
   - [Consulta el archivo de documentación en GitHub](https://github.com/Dapt01G2-Henry/ComerLogistics/blob/main/documentacion.md).

### **Importancia de este paso en el proyecto**:

- **Centralización de datos**: Al importar todos los datos relevantes a Power BI desde diferentes fuentes, se logró centralizar la información en una única plataforma. Esto facilita el análisis y permite a todos los miembros del equipo trabajar con los mismos datos actualizados.
  
- **Relaciones entre tablas**: La creación de relaciones entre las diferentes tablas importadas permitió realizar análisis más complejos y cruzados, como el impacto de las compras en el inventario final o la relación entre las ventas y los niveles de inventario en las tiendas.

- **Automatización de la actualización de datos**: La conexión a la base de datos **SQL Server** permitió que los datos estuvieran siempre actualizados en **Power BI** sin necesidad de carga manual. Esto mejora la eficiencia del análisis y asegura que los informes siempre se basen en los datos más recientes.

### **Siguientes pasos**:
Con los datos ya importados y listos para su uso en **Power BI**, el siguiente paso fue la limpieza y transformación de los datos para asegurar su calidad y adecuarlos a los análisis que se realizarán en los reportes.

[Repositorio ComerLogistics en GitHub](https://github.com/Dapt01G2-Henry/ComerLogistics)

_____

