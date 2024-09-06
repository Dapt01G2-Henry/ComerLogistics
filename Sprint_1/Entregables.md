# Entregables Sprint 1 

# 1. Crear el repositorio público y compartirlo con el equipo

## Descripción:
Uno de los pasos iniciales y fundamentales para la correcta organización del proyecto fue la creación de un repositorio público en GitHub, donde se centralizan todas las actividades de desarrollo y colaboración entre los miembros del equipo. Este repositorio funciona como el espacio de trabajo colaborativo en el que se almacenan todos los recursos del proyecto, incluidos scripts, notebooks, documentación, imágenes, y demás elementos necesarios para el correcto avance del proyecto.

Además, la implementación de control de versiones es esencial en un entorno colaborativo. GitHub permite el seguimiento de los cambios realizados en el código y la documentación, lo que asegura que todos los integrantes del equipo estén trabajando siempre con la versión más actualizada de los archivos y que se pueda retroceder a versiones anteriores en caso de errores.

## Acciones realizadas:

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

## Resultado Final:
Gracias a la creación del repositorio público y su adecuada configuración, el equipo ha logrado trabajar de manera colaborativa y eficiente. El control de versiones ha sido clave para asegurar que el desarrollo se realice de manera estructurada, mientras que la organización del repositorio ha permitido un fácil acceso a todos los recursos y archivos necesarios para el desarrollo del proyecto.

_____